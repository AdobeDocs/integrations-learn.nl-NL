---
title: Integreren [!DNL Analytics] with [!DNL Commerce] zelfstudie
description: Leer hoe u kunt integreren [!DNL Analytics] with [!DNL Commerce].
solution: Analytics, Commerce
feature: Integrations
topic: Integrations
role: Leader, Architect, Admin, Developer
level: Beginner
index: true
hidefromtoc: true
kt: null
thumbnail: null
last-substantial-update: 2023-04-11T00:00:00Z
badgeIntegration: label="Integratie" type="positive"
exl-id: ef50b6b3-1e2b-4fe9-98d5-555bc14ae8d6
source-git-commit: 46803595cf8e199e0c331ea8b82f7fe4a2afc801
workflow-type: tm+mt
source-wordcount: '821'
ht-degree: 0%

---

# Integreren [!DNL Analytics] with [!DNL Commerce]

## Eerste instapkaartsysteem

Deze instructies zijn bedoeld voor Adobe [!DNL Commerce] Door cloud gehoste projecten. Zelf-ontvangen kan tot op zekere hoogte variëren, maar het algemene proces zou gelijkaardig moeten zijn.

1. Bekijk de code in uw lokale omgeving
1. Composer- en installatiemodule gebruiken
1. Volg de individuele instructies hier en keer terug wanneer voltooid om de resterende stappen te voltooien
   [De ervaring installeren en configureren [!DNL Platform] connector](https://experienceleague.adobe.com/docs/commerce-merchant-services/experience-platform-connector/fundamentals/install.html){target="_blank"}


1. Composer.json vastleggen en, indien beschikbaar, composer.lock-bestanden in de cloud
1. Controleren of de module zich op de testomgeving en/of productieomgevingen bevindt U kunt dit doen door u aan te melden bij de beheersectie van de Adobe [!DNL Commerce] en deze nieuwe secties zoeken onder Systeem > Services
   ![Ervaring [!DNL Platform] connectorextensie](./assets/analytics-commerce/admin-view-experience-platform-commector-extension.png)

1. Vorm de module met uw geloofsbrieven van binnen de Adobe [!DNL Commerce] achterkantoor.
   * Eerste [!DNL Commerce] De schakelaarconfiguraties van de diensten, zoals hieronder getoond.
     ![[!DNL Commerce] Instellen van serviceconnector](./assets/analytics-commerce/commerce-services-connector-setup.png)
   * Dan de Ervaring [!DNL Platform] de verbindingsmontages, zoals hieronder getoond.
     ![Ervaring [!DNL Platform] connector](./assets/analytics-commerce/experience-platform-connector.png)

Volg de instructies op het tabblad [Ervaring [!DNL Platform] connectoroverzicht](https://experienceleague.adobe.com/docs/commerce-merchant-services/experience-platform-connector/overview.html){target="_blank"}. De ervaring [!DNL Platform] de schakelaarzelfstudie behandelt elke sectie in detail en beantwoordt om het even welke vragen u kunt hebben. Gebruik deze zelfstudie voor de rest van de snelle stappen die u uitvoert.

## Configuratie van de Experience Edge en Adobe [!DNL Analytics]

1. Controleren of uw organisatie toegang heeft (en hebt) tot Adobe [!DNL Analytics]. Dit kan worden bevestigd door naar de [Homepage van Adobe Experience Cloud](https://experience.adobe.com/) en klikken op de toepassingsschakeloptie (negen punten) in de bovenste navigatie.

1. Nieuwe rapportsuite maken in Adobe [!DNL Analytics]of identificeer de id van de rapportsuite waarop u wilt aandringen [!DNL Commerce] gegevens in. Voor meer informatie bekijkt u een zelfstudie op [het creëren van een nieuwe rapportreeks](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/intro-to-analytics/analytics-basics/understanding-and-creating-report-suites.html). U hebt deze rapportsuite-id nodig in de onderstaande gegevensstroomstap.

1. Ga naar de [Ervaring met Adobe [!DNL Platform] interface](https://platform.adobe.com) als u toegang hebt tot Experience [!DNL Platform]. Als u geen toegang tot die interface hebt, kunt u alle hieronder vermelde noodzakelijke stappen in de Ervaring van de Adobe uitvoeren [!DNL Platform] [Interface voor gegevensverzameling](https://experience.adobe.com/#/data-collection).

1. Uw XDM-schema maken of bijwerken met [!DNL Commerce]-specifieke veldgroepen. Voor meer informatie over hoe te om een schema tot stand te brengen, gelieve te zien [&quot;Schema&#39;s maken&quot;](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-schemas.html) zelfstudie.
   * U moet dit schema selecteren uit de opties in de onderstaande gegevensstroomstap. Als u een schema wilt maken, zoekt u in de linkerkolom onder **Gegevensbeheer** en zoeken **Schemas**. Klik nu rechtsboven in de interface op **Schema maken**. Selecteer XDM ExperienceEvent.
   * Nadat u een nieuw schema hebt gemaakt, voegt u de opdracht [!DNL Commerce] veldgroepen. Zoek links in de gebruikersinterface veldgroepen en klik op **Toevoegen**
      * In de zoekopdracht kunt u filteren door `ExperienceEvent Commerce`
      * Selecteer de **Adobe [!DNL Analytics] ExperienceEvent[!DNL Commerce]** door het selectievakje in te schakelen
      * Klik vervolgens op **Veldgroepen toevoegen** in de rechterbovenhoek opslaan en doorgaan

1. Optioneel (en alleen als u ervaring hebt) [!DNL Platform] interface) - een nieuwe dataset maken
   * Met deze stap kunt u de [!DNL Commerce] gegevens over de ervaring [!DNL Platform] (afzonderlijk van de gegevens in Adobe te brengen [!DNL Analytics]). Doe deze stap als u toegang hebt tot Experience [!DNL Platform]en zijn van plan de [!DNL Commerce] gegevens in de ervaring [!DNL Platform]-ondersteunde toepassingen, zoals realtime klantgegevens [!DNL Platform], Klantenreis [!DNL Analytics], of Journey Optimizer.
   * U zult deze dataset van de opties in de gegevensstroomstap hieronder moeten selecteren.
   * Onder de linkerkolom **Gegevensbeheer** in de linkernavigatie selecteert u **Gegevenssets**.
   * Klikken **Gegevensset maken** rechtsboven. Kies de optie **Gegevensset maken van schema** -optie.
   * Zoek naar en gebruik het schema dat u in de laatste stap creeerde

1. Maak de DataStream om de [!DNL Commerce] gegevens naar Adobe [!DNL Analytics]
   * Onder de **Gegevensverzameling** in de linkerkolom selecteert u **Gegevensstromen**.
   * Klikken **Nieuwe DataStream** in de rechterbovenhoek van de interface.
   * Geef een naam en een optionele beschrijving op.
   * Zoek en selecteer het schema dat u in de vorige stap hebt gemaakt/geïdentificeerd.
   * Voeg de gewenste geavanceerde opties toe. Ga voor meer informatie over de geavanceerde opties naar de [documentatie](https://experienceleague.adobe.com/docs/experience-platform/datastreams/configure.html).
   * Klikken **Opslaan** om door te gaan.
   * Klikken **Service toevoegen** en kiest u **Adobe[!DNL Analytics]** in het vervolgkeuzeveld.
   * Klikken **Rapportsuite toevoegen** en voer de rapportsuite-id in die u in een vorige stap hebt gemaakt/geïdentificeerd. U kunt meer dan één rapportreeks toevoegen als u de gegevens in veelvoudige rapportreeksen zou willen stromen.
   * Naar keuze, en als u een dataset in een vorige stap creeerde, klik **Service toevoegen** nogmaals, kiezen **Ervaring met Adobe[!DNL Platform]** in het vervolgkeuzeveld. Selecteer in het veld Gebeurtenisgegevensset de gegevensset die u eerder hebt gemaakt.
   * Sla de DataStream op.

1. Tot slot kunt u uw [!DNL Commerce] gegevens, moet u in Adobe naar Analysis Workspace navigeren [!DNL Analytics], maakt u een project, kiest u uw rapportsuite en voegt vrije-vormtabellen en andere visualisaties toe om uw [!DNL Commerce] gegevens. In de volgende afbeelding ziet u een voorbeeld van een tabel die u kunt maken in Analysis Workspace.

   ![[!DNL Analytics] Screenshot van sommige handelsgegevens](./assets/analytics-commerce/analytics-screenshot-commerce-items.png)

   Hier volgen enkele aanvullende bronnen die u helpen bij het werken in Analysis Workspace:

   * [Analysis Workspace-overzicht](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/analysis-workspace-overview.html)
   * [Een werkruimteproject helemaal vanaf het begin maken](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/building-a-workspace-project-from-scratch.html)
   * [Tabellen, visualisaties en deelvensters gebruiken in Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/using-panels/using-tables-visualizations-and-panels.html)
   * [Gebruiksgevallen voor visualisatie](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/visualizations/visualization-use-cases.html)

   Bovendien zijn er gratis cursussen beschikbaar op Experience League. Zie [!DNL Analytics] cursussen beschikbaar [HIER](https://experienceleague.adobe.com/?lang=en&amp;Solution=Analytics#courses).
