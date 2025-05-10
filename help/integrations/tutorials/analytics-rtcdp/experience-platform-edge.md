---
title: Integreer  [!DNL Analytics]  en Echte-tijd Gegevens van de Klant  [!DNL Platform]  met de ervaring  [!DNL Platform]  zelfstudie van Edge
description: Leer hoe te om Adobe  [!DNL Analytics]  met Gegevens van de Klant in real time  [!DNL Platform]  te integreren gebruikend AEP Web SDK, AEP Mobiele SDK, of de Server API van de Edge Network.
solution: Real-Time Customer Data [!DNL Platform], [!DNL Analytics]
feature: Integrations
topic: Integrations
role: Developer
level: Experienced
index: true
hidefromtoc: true
kt: 13732
thumbnail: null
last-substantial-update: 2023-04-11T00:00:00Z
badgeIntegration: label="Integratie" type="positive"
exl-id: 07c2c329-0810-4f66-a91a-e315695f3fb4
source-git-commit: d35dc06c56c117cffe70542b6713f275877e4879
workflow-type: tm+mt
source-wordcount: '202'
ht-degree: 1%

---

# Adobe [!DNL Analytics] en realtime klantgegevens [!DNL Platform] integreren met de zelfstudie Experience [!DNL Platform] Edge

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
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/create-segments.html?lang=nl-NL" _target="_blank" rel="noopener noreferrer"> creeer segmenten in Ervaring [!DNL Platform].</a> Het systeem bepaalt automatisch of het segment wordt geëvalueerd als batch (gegevensconnector) of streaming (Edge-netwerk).</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/create-destinations-and-activate-data.html?lang=nl-NL" _target="_blank" rel="noopener noreferrer">Vorm bestemmingen voor het delen van profielattributen en publiekslidmaatschappen aan gewenste bestemmingen.</a></li>
</ol>

>[!NOTE]
>
>De standaardwerkstroomstappen voor de Adobe [!DNL Analytics] bronschakelaar leiden tot het schema en de dataset die worden gebruikt om de gegevens van [!DNL Analytics] &quot;as-is&quot; in te voeren. Daarom worden de eerste twee stappen behandeld door het systeem. Voor de toewijzingsworkflow moeten aangepaste kenmerken worden gemaakt. Volg daarom de stappen volledig.
