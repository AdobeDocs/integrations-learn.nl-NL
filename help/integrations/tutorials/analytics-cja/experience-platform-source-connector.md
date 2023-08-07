---
title: Integreren [!DNL Analytics] en Klantenreis [!DNL Analytics] met ervaring [!DNL Platform] zelfstudie bronaansluiting
description: Leer hoe u Adobe kunt integreren [!DNL Analytics] met Klantreis [!DNL Analytics] gebruiken van de Ervaring [!DNL Platform] bronaansluiting.
solution: Customer Journey [!DNL Analytics], [!DNL Target]
feature: Integrations
topic: Integrations
role: Leader, Architect, Admin, Developer
level: Beginner
index: true
hidefromtoc: true
kt: 13727
thumbnail: null
last-substantial-update: 2023-04-11T00:00:00Z
badgeIntegration: label="Integratie" type="positive"
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '274'
ht-degree: 0%

---


# Adobe integreren [!DNL Analytics] en Klantenreis [!DNL Analytics] met ervaring [!DNL Platform] bronaansluiting

<ol>
    <li><a href="https://experienceleague.adobe.com/?lang=en#dashboard/learning" _target="_blank" rel="noopener noreferrer">Schema's maken</a> voor gegevens die moeten worden ingevoerd.</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/create-datasets-and-ingest-data.html" _target="_blank" rel="noopener noreferrer">Gegevenssets maken</a> voor gegevens die moeten worden ingevoerd.</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/identities/label-ingest-and-verify-identity-data.html?lang=en" _target="_blank" rel="noopener noreferrer">Vorm de correcte identiteiten en identiteitsnamespaces op het schema</a> om er zeker van te zijn dat de opgenomen gegevens kunnen worden gekoppeld aan een eenvormig profiel.</li> 
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/bring-data-into-the-real-time-customer-profile.html" _target="_blank" rel="noopener noreferrer">De schema's en datasets voor profiel inschakelen</a>.</li>
    <li>Gegevens presenteren in Experience [!DNL Platform] met de <a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/ingest-data-from-adobe-analytics.html" _target="_blank" rel="noopener noreferrer">Adobe [!DNL Analytics] bronaansluiting</a></li>
    <li><i>(Optioneel)</i>. Als u meerdere gegevenssets gebruikt, koppelt u de id van de persoon aan <a href="https://experienceleague.adobe.com/docs/analytics-platform/using/cja-connections/combined-dataset.html" _target="_blank" rel="noopener noreferrer">een gecombineerde gegevensset genereren</a>. Als u één [!DNL Analytics] dataset, of als een gemeenschappelijke herkenningsteken over alle datasets bestaat u van plan bent in de Reis van de Klant te gebruiken [!DNL Analytics]Deze stap overslaan.</li>
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/connections/connecting-customer-journey-analytics-to-data-sources-in-platform.html" _target="_blank" rel="noopener noreferrer">Verbinding maken</a> op reis van klant [!DNL Analytics].</li>
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/basic-configuration-for-data-views.html" _target="_blank" rel="noopener noreferrer">Een gegevensweergave maken</a>, <a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/configuring-component-settings-in-data-views.html" _target="_blank" rel="noopener noreferrer">configureren, componentinstellingen</a>, en <a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/formatting-metrics-in-data-views.html" _target="_blank" rel="noopener noreferrer">indelingswaarden</a> op reis van klant [!DNL Analytics].
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/analysis-workspace/workspace-projects/build-a-new-project.html" _target="_blank" rel="noopener noreferrer">Een project maken op reis van klant [!DNL Analytics].</a></li>
</ol>

>[!NOTE]
>
>De standaardworkflowstappen voor de Adobe [!DNL Analytics] bronschakelaar creeert het schema en de dataset wordt gebruikt om de gegevens van in te voeren [!DNL Analytics] &quot;as-is&quot;. Daarom worden de eerste twee stappen behandeld door het systeem. Voor de toewijzingsworkflow moeten aangepaste kenmerken worden gemaakt. Volg daarom de stappen volledig.
