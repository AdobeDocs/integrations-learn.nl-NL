---
title: Integreer Adobe  [!DNL Analytics]  en de Reizen van de Klant  [!DNL Analytics]  met de ervaring  [!DNL Platform]  zelfstudie van Edge
description: Leer hoe te om Adobe  [!DNL Analytics]  met de Reis van de Klant  [!DNL Analytics]  te integreren gebruikend AEP Web SDK, AEP Mobiele SDK, of de Server API van de Edge Network.
solution: Customer Journey [!DNL Analytics], [!DNL Analytics]
feature: Integrations
topic: Integrations
role: Developer
level: Experienced
index: true
hidefromtoc: true
kt: null
thumbnail: 13728
last-substantial-update: 2023-04-11T00:00:00Z
badgeIntegration: label="Integratie" type="positive"
exl-id: e39dac5d-6ad5-47c8-94e8-070011233161
source-git-commit: d35dc06c56c117cffe70542b6713f275877e4879
workflow-type: tm+mt
source-wordcount: '236'
ht-degree: 1%

---

# Adobe [!DNL Analytics] en Klantenreis [!DNL Analytics] integreren met de zelfstudie Experience [!DNL Platform] Edge

<ol>
    <li><a href="https://experienceleague.adobe.com/nl?lang=en#dashboard/learning" _target="_blank" rel="noopener noreferrer"> creeer schema's </a> voor gegevens die moeten worden opgenomen.</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/create-datasets-and-ingest-data.html?lang=nl-NL" _target="_blank" rel="noopener noreferrer"> creeer datasets </a> voor gegevens die moeten worden opgenomen.</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/identities/label-ingest-and-verify-identity-data.html?lang=nl-NL" _target="_blank" rel="noopener noreferrer"> vorm de correcte identiteiten en de identiteitsnamespaces op het schema </a> om zeker te zijn dat de ingebedde gegevens aan een verenigd profiel kunnen verbinden.</li> 
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/bring-data-into-the-real-time-customer-profile.html?lang=nl-NL" _target="_blank" rel="noopener noreferrer"> laat de schema's en datasets voor profiel </a> toe.</li>
    <li>U kunt gegevens op een van de volgende manieren in Experience opnemen: [!DNL Platform]</li>
        <ul>
            <li>Experience [!DNL Platform] Web SDK:</li>
                <ul>
                    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/implement-web-sdk/overview.html?lang=nl-NL" _target="_blank" rel="noopener noreferrer">Tutorial</a></li>
                    <li><a href="https://experienceleague.adobe.com/docs/analytics/implementation/aep-edge/web-sdk/overview.html?lang=nl-NL" _target="_blank" rel="noopener noreferrer">Checklist</a></li>
                </ul>
            <li>Geniet van [!DNL Platform] Mobile SDK:</li>
                <ul>
                    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/data-collection/mobile-sdk/create-mobile-properties.html?lang=nl-NL" _target="_blank" rel="noopener noreferrer">Tutorial</a></li>
                    <li><a href="https://experienceleague.adobe.com/docs/analytics/implementation/aep-edge/mobile-sdk/overview.html?lang=nl-NL" _target="_blank" rel="noopener noreferrer">Checklist</a></li>
                </ul></li>
            <li>Server-API van Edge Network:</li>
                <ul>
                    <li><a href="https://experienceleague.adobe.com/docs/experience-platform/edge-network-server-api/interacting-other-adobe-solutions/interacting-adobe-analytics.html?lang=nl-NL" _target="_blank" rel="noopener noreferrer">Tutorial</a></li>
                </ul>
       </ul>
    <li><i> (Facultatief) </i>. Als het gebruiken van veelvoudige datasets, verbind persoonlijk identiteitskaart samen aan <a href="https://experienceleague.adobe.com/docs/analytics-platform/using/cja-connections/combined-dataset.html?lang=nl-NL" _target="_blank" rel="noopener noreferrer"> een gecombineerde dataset </a> produceren. Als u één [!DNL Analytics] dataset gebruikt of als er een gemeenschappelijke id bestaat voor alle datasets die u wilt gebruiken in Reis van de Klant [!DNL Analytics] , slaat u deze stap over.</li>
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/connections/connecting-customer-journey-analytics-to-data-sources-in-platform.html?lang=nl-NL" _target="_blank" rel="noopener noreferrer"> creeer een verbinding </a> in de Reis van de Klant [!DNL Analytics].</li>
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/basic-configuration-for-data-views.html?lang=nl-NL" _target="_blank" rel="noopener noreferrer"> creeer een gegevensmening </a>, <a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/configuring-component-settings-in-data-views.html?lang=nl-NL" _target="_blank" rel="noopener noreferrer"> vorm de componentenmontages </a>, en <a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/formatting-metrics-in-data-views.html?lang=nl-NL" _target="_blank" rel="noopener noreferrer"> formaatmetriek </a> in de Reis van de Klant [!DNL Analytics].
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/analysis-workspace/workspace-projects/build-a-new-project.html?lang=nl-NL" _target="_blank" rel="noopener noreferrer">Een project maken op reis van klant [!DNL Analytics] .</a></li>
</ol>

>[!NOTE]
>
>De standaardwerkstroomstappen voor de Adobe [!DNL Analytics] bronschakelaar leiden tot het schema en de dataset die worden gebruikt om de gegevens van [!DNL Analytics] &quot;as-is&quot; in te voeren. Daarom worden de eerste twee stappen behandeld door het systeem. Voor de toewijzingsworkflow moeten aangepaste kenmerken worden gemaakt. Volg daarom de stappen volledig.
