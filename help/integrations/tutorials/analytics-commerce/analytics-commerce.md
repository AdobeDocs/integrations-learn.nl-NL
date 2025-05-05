---
title: Integreer  [!DNL Analytics]  met  [!DNL Commerce]  leerprogramma
description: Leer hoe te om  [!DNL Analytics]  met  [!DNL Commerce] te integreren.
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

# [!DNL Analytics] integreren met [!DNL Commerce]

## Eerste instapkaartsysteem

Deze instructies zijn bedoeld voor het Adoben van [!DNL Commerce] via de cloud gehoste projecten. Zelf-ontvangen kan tot op zekere hoogte variëren, maar het algemene proces zou gelijkaardig moeten zijn.

1. Bekijk de code in uw lokale omgeving
1. Composer- en installatiemodule gebruiken
1. Volg de individuele instructies hier en keer terug wanneer voltooid om de resterende stappen te voltooien
   [ installeer en vorm de 1&rbrace; schakelaar van de Ervaring ](https://experienceleague.adobe.com/docs/commerce-merchant-services/experience-platform-connector/fundamentals/install.html?lang=nl-NL){target="_blank"}  [!DNL Platform] 


1. Composer.json vastleggen en, indien beschikbaar, composer.lock-bestanden in de cloud
1. Controleren of de module zich op de testomgeving en/of productieomgeving bevindt
U kunt dit doen door u aan te melden bij de beheersectie van de Adobe [!DNL Commerce] en deze nieuwe secties te zoeken onder Systeem > Services
   ![ Ervaring [!DNL Platform] schakelaaruitbreiding ](./assets/analytics-commerce/admin-view-experience-platform-commector-extension.png)

1. Vorm de module met uw geloofsbrieven van binnen de Adobe [!DNL Commerce] achterbureau.
   * Eerst de [!DNL Commerce] de schakelaarconfiguraties van de Diensten, zoals hieronder getoond.

     ![[!DNL Commerce] Instellen van serviceconnector ](./assets/analytics-commerce/commerce-services-connector-setup.png)
   * Dan de Ervaring [!DNL Platform] schakelaarmontages, zoals hieronder getoond.

     ![ Ervaring [!DNL Platform] schakelaar ](./assets/analytics-commerce/experience-platform-connector.png)

Voor grotere details op elke fase en stap van het onboarding proces, volg de instructies op het [ overzicht van de Ervaring  [!DNL Platform]  schakelaar ](https://experienceleague.adobe.com/docs/commerce-merchant-services/experience-platform-connector/overview.html?lang=nl-NL){target="_blank"} . De verbindingszelfstudie Experience [!DNL Platform] behandelt elke sectie in detail en beantwoordt alle vragen die u hebt. Gebruik deze zelfstudie voor de rest van de snelle stappen die u uitvoert.

## Configuratie van Experience Edge en Adobe [!DNL Analytics]

1. Controleer of uw organisatie toegang heeft (en hebt) tot Adobe [!DNL Analytics] . Dit kan worden bevestigd door naar de [ homepage van Adobe Experience Cloud ](https://experience.adobe.com/) te gaan en op de toepassingsschakelaar (negen punten) in de hoogste navigatie te klikken.

1. Maak een nieuwe rapportsuite in Adobe [!DNL Analytics] of identificeer de id van de rapportsuite waarnaar u [!DNL Commerce] -gegevens wilt doorsturen. Voor meer info, bekijk een leerprogramma bij [ het creëren van een nieuwe rapportreeks ](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/intro-to-analytics/analytics-basics/understanding-and-creating-report-suites.html?lang=nl-NL). U hebt deze rapportsuite-id nodig in de onderstaande gegevensstroomstap.

1. Navigeer aan de  [!DNL Platform]  interface [&#128279;](https://platform.adobe.com) van de Ervaring van de Adobe 0&rbrace; als u toegang tot Ervaring [!DNL Platform] hebt.  Als u geen toegang tot die interface hebt, kunt u alle noodzakelijke stappen uitvoeren hieronder in de ervaring van de Adobe [!DNL Platform] [ de interface van de Inzameling van Gegevens ](https://experience.adobe.com/#/data-collection) worden vermeld.

1. Maak of werk uw XDM-schema bij met [!DNL Commerce] specifieke veldgroepen. Voor meer informatie over hoe te om een schema tot stand te brengen, te zien gelieve [ &quot;schema&#39;s&quot;creëren ](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-schemas.html?lang=nl-NL) leerprogramma.
   * U moet dit schema selecteren uit de opties in de onderstaande gegevensstroomstap. Om een schema tot stand te brengen, kijk in de linkerkolom onder **het Beheer van Gegevens** en vind **Schema&#39;s**. Nu op het hoogste recht van de interface, klik **creeer schema**. Selecteer XDM ExperienceEvent.
   * Nadat u een nieuw schema hebt gemaakt, voegt u de [!DNL Commerce] -veldgroepen toe. Op de linkerkant van UI, vind de groepen van het Gebied, en klik **toevoegen**
      * In de zoekopdracht kunt u filteren door `ExperienceEvent Commerce` in te voeren
      * Selecteer de **Adobe [!DNL Analytics] ExperienceEvent[!DNL Commerce]** door het selectievakje in te schakelen
      * Dan klik **voeg gebiedsgroepen** op het hoogste recht toe om te bewaren en verder te gaan

1. Optioneel (en alleen als u in de interface Experience [!DNL Platform] werkt) - Een nieuwe dataset maken
   * Met deze stap kunt u de [!DNL Commerce] -gegevens overbrengen naar de Experience [!DNL Platform] (los van de gegevens over te brengen naar de Adobe [!DNL Analytics] ). Voer deze stap uit als u toegang hebt tot Experience [!DNL Platform] en u de [!DNL Commerce] data in de Experience [!DNL Platform] -ondersteunde toepassingen wilt gebruiken, zoals Real-Time Customer Data [!DNL Platform] , Customer Journey [!DNL Analytics] of Journey Optimizer.
   * U zult deze dataset van de opties in de gegevensstroomstap hieronder moeten selecteren.
   * Onder de linkerkolom **rubriek van het Beheer van Gegevens** in de linkernavigatie, uitgezochte **Datasets**.
   * Klik **creëren dataset** in het hoogste recht. Kies **dataset van schema** optie creëren.
   * Zoek naar en gebruik het schema dat u in de laatste stap creeerde

1. Maak de DataStream om de [!DNL Commerce] -gegevens naar de Adobe te verzenden [!DNL Analytics]
   * Onder de **rubriek van de Inzameling van Gegevens** in de linkerkolom, uitgezochte **Gegevensstromen**.
   * Klik **Nieuwe Datastream** op het hoogste recht van de interface.
   * Geef een naam en een optionele beschrijving op.
   * Zoek en selecteer het schema dat u in de vorige stap hebt gemaakt/geïdentificeerd.
   * Voeg de gewenste geavanceerde opties toe. Voor meer informatie over de geavanceerde opties, gelieve de [ documentatie ](https://experienceleague.adobe.com/docs/experience-platform/datastreams/configure.html?lang=nl-NL) te bezoeken.
   * Klik **sparen** om verder te gaan.
   * Klik **toevoegen de Dienst** en kiezen **Adobe[!DNL Analytics]** op het drop-down gebied.
   * Klik **toevoegen de Reeks van het Rapport** en gaan identiteitskaart van de rapportreeks in die u in een vorige stap creeerde/identificeerde. U kunt meer dan één rapportreeks toevoegen als u de gegevens in veelvoudige rapportreeksen zou willen stromen.
   * Naar keuze, en als u een dataset in een vorige stap creeerde, klik **voegt de Dienst** opnieuw toe, het kiezen van **Ervaring van de Adobe[!DNL Platform]** van het drop-down gebied. Selecteer in het veld Gebeurtenisgegevensset de gegevensset die u eerder hebt gemaakt.
   * Sla de DataStream op.

1. Als u ten slotte uw [!DNL Commerce] -gegevens wilt weergeven, moet u in Adobe [!DNL Analytics] naar Analysis Workspace navigeren, een project maken, uw rapportsuite kiezen en vrije-vormtabellen en andere visualisaties toevoegen om uw [!DNL Commerce] -gegevens te rapporteren en te analyseren. In de volgende afbeelding ziet u een voorbeeld van een tabel die u kunt maken in Analysis Workspace.

   ![[!DNL Analytics] Screenshot van sommige handelsgegevens ](./assets/analytics-commerce/analytics-screenshot-commerce-items.png)

   Hier volgen enkele aanvullende bronnen die u helpen bij het werken in Analysis Workspace:

   * [ overzicht van Analysis Workspace ](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/analysis-workspace-overview.html?lang=nl-NL)
   * [ Bouwend een project van Workspace van kras ](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/building-a-workspace-project-from-scratch.html?lang=nl-NL)
   * [ Gebruikend Lijsten, Visualizations, en Deelvensters in Analysis Workspace ](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/using-panels/using-tables-visualizations-and-panels.html?lang=nl-NL)
   * [ het gebruiksgevallen van het visualisatiegebruik ](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/visualizations/visualization-use-cases.html?lang=nl-NL)

   Bovendien zijn er gratis cursussen beschikbaar op Experience League. Zie [!DNL Analytics] beschikbare cursussen [ HIER ](https://experienceleague.adobe.com/nl?lang=en&amp;Solution=Analytics#courses).
