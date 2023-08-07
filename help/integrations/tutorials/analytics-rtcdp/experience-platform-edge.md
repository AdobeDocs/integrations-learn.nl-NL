---
title: Integreren [!DNL Analytics] en realtime klantgegevens [!DNL Platform] met de ervaring [!DNL Platform] Edge-zelfstudie
description: Leer hoe u Adobe kunt integreren [!DNL Analytics] met realtime klantgegevens [!DNL Platform] met de AEP Web SDK, AEP Mobile SDK of de Edge Network Server-API.
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
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '270'
ht-degree: 2%

---


# Adobe integreren [!DNL Analytics] en realtime klantgegevens [!DNL Platform] met ervaring [!DNL Platform] Edge-zelfstudie

<ol>
    <li><a href="https://experienceleague.adobe.com/?lang=en#dashboard/learning" _target="_blank" rel="noopener noreferrer">Schema's maken</a> voor gegevens die moeten worden ingevoerd.</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/create-datasets-and-ingest-data.html" _target="_blank" rel="noopener noreferrer">Gegevenssets maken</a> voor gegevens die moeten worden ingevoerd.</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/identities/label-ingest-and-verify-identity-data.html?lang=en" _target="_blank" rel="noopener noreferrer">Vorm de correcte identiteiten en identiteitsnamespaces op het schema</a> om er zeker van te zijn dat de opgenomen gegevens kunnen worden gekoppeld aan een eenvormig profiel.</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/bring-data-into-the-real-time-customer-profile.html" _target="_blank" rel="noopener noreferrer">De schema's en datasets voor profiel inschakelen</a>.</li>
    <li>Gegevens presenteren in Experience [!DNL Platform] op een van de volgende manieren:</li>
        <ul>
           <li>Ervaring [!DNL Platform] Web SDK:</li>
                <ul>
                    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/implement-web-sdk/overview.html" _target="_blank" rel="noopener noreferrer">Tutorial</a></li>
                    <li><a href="https://experienceleague.adobe.com/docs/analytics/implementation/aep-edge/web-sdk/overview.html" _target="_blank" rel="noopener noreferrer">Checklist</a></li>
                </ul>
            <li>Ervaring [!DNL Platform] Mobile SDK:</li>
                <ul>
                    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/data-collection/mobile-sdk/create-mobile-properties.html" _target="_blank" rel="noopener noreferrer">Tutorial</a></li>
                    <li><a href="https://experienceleague.adobe.com/docs/analytics/implementation/aep-edge/mobile-sdk/overview.html" _target="_blank" rel="noopener noreferrer">Checklist</a></li>
                </ul></li>
            <li>Edge Network Server API:</li>
                <ul>
                    <li><a href="https://experienceleague.adobe.com/docs/experience-platform/edge-network-server-api/interacting-other-adobe-solutions/interacting-adobe-analytics.html" _target="_blank" rel="noopener noreferrer">Tutorial</a></li>
                </ul>
       </ul>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/create-segments.html" _target="_blank" rel="noopener noreferrer">Segmenten maken in de ervaring [!DNL Platform].</a> Het systeem bepaalt automatisch of het segment als partij (gegevensschakelaar) of het stromen (het netwerk van de Rand) wordt geëvalueerd.</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/create-destinations-and-activate-data.html" _target="_blank" rel="noopener noreferrer">Vorm bestemmingen voor het delen van profielattributen en publiekslidmaatschappen aan gewenste bestemmingen.</a></li>
</ol>

>[!NOTE]
>
>De standaardworkflowstappen voor de Adobe [!DNL Analytics] bronschakelaar creeert het schema en de dataset wordt gebruikt om de gegevens van in te voeren [!DNL Analytics] &quot;as-is&quot;. Daarom worden de eerste twee stappen behandeld door het systeem. Voor de toewijzingsworkflow moeten aangepaste kenmerken worden gemaakt. Volg daarom de stappen volledig.
