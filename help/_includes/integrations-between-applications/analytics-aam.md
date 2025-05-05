---
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '367'
ht-degree: 0%

---


# [!DNL Analytics] en integratie met Audience Managers

{{analytics-description}}

{{audience-manager-description}}

Als u deze integratie inschakelt door Adobe [!DNL Analytics] aan de serverzijde door te sturen naar de Audience Manager, krijgt Audience Manager een van de belangrijkste gegevensbronnen, namelijk gedragsgegevens van de online klant. Deze gegevens kunnen dan met andere gegevens, zoals de gegevens van eerste-partijCRM of derdenpartner worden gecombineerd, om rijke klantensegmenten tot stand te brengen. Bovendien worden de segmenten van de Audience Manager vervolgens teruggestuurd naar de webpagina in het antwoord voor verdere analyse door de bezoeker. Beide gevallen van waardevol gebruik worden hieronder beschreven.

De belangrijkste voordelen van de integratie van Adobe [!DNL Analytics] en Audience Manager zijn:

+ **Verbeterde segmentatie**: Combineer Adobe [!DNL Analytics] &amp; Audience Manager gegevens voor nauwkeurige, gepersonaliseerde publiekssegmenten in marketing campagnes.
+ **Verenigde klantenprofielen**: Integreer gegevensbronnen om interactie en gedrag te begrijpen, creërend uitvoerige klantenprofielen.
+ **Verbeterde en doeltreffendheid**: Optimaliseer reclame met gegeven-gedreven het richten van Adobe [!DNL Analytics] &amp; de integratie van de Audience Manager.
+ **gegevens-gedreven besluiten**: Maak keuzen door gedetailleerde inzichten, het samenvoegen van Adobe [!DNL Analytics] &amp; de gegevens van de Audience Manager.
+ **Gepersonaliseerde ervaringen**: Tailor uw inhoud &amp; aanbiedingen, die klanteninteractie over aanraking-punten verrijken gebruikend beide platforms.

Over het algemeen brengt deze integratie waardevolle gegevens en inzicht in het publiek samen. Hierdoor kunnen bedrijven doelgerichtere en relevante marketingcampagnes opzetten en tegelijkertijd een beter inzicht krijgen in de voorkeuren en het gedrag van hun klanten.

## Gemeenschappelijke integratie

<table>
    <thead>
        <tr>
            <th>Experiencen Cloud</th>
            <th>Integreert met</th>
            <th>Wanneer gebruiken</th>
            <th>Vaak voorkomende gebruiksscenario's</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <a href="/docs/analytics-learn/tutorials/integrations/audience-manager/enable-server-side-forwarding-in-adobe-launch.html" target="_blank" rel="noreferrer">[!DNL Analytics] gegevens verzenden naar Audience Manager </a>
            </td>
            <td>Adobe [!DNL Analytics] tags extension of AppMeasurement.js met server-side forward enabled</td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Wanneer u Adobe [!DNL Analytics] gegevens naar Audience Manager wilt verzenden om segmenten tot stand te brengen die met andere bestemmingen van Adobe Experience Cloud, op mensen-gebaseerde bestemmingen, of andere op apparaat-gebaseerde en douanebestemmingen kunnen worden gedeeld die door Audience Manager worden gesteund.</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Segmenten delen op advertentieplatforms die gedragskenmerken bevatten die zijn verzameld in [!DNL Analytics] .</li>
                    <li>Verrijk segmenten met [!DNL Analytics] gegevens om hoogwaardig, dwars-kanaalsegmenten tot stand te brengen om in plaats te gebruiken die richten.</li>
                    <li>Laag in [!DNL Analytics] -gegevens naar segmenten die zijn uitgeschakeld op hashed-id's, zoals e-mail, voor gebruik in sociale-mediaplatforms.</li>
                </ul>
            </td>
        </tr>        
        <tr>
            <td>
                <a href="https://experienceleague.adobe.com/docs/analytics/integration/audience-analytics/mc-audiences-aam.html?lang=nl-NL" target="_blank" rel="noreferrer"> Audience Manager die gegevens terug naar [!DNL Analytics]</a> verzendt
            </td>
            <td>Adobe [!DNL Analytics] tags extension of AppMeasurement.js met server-side forward enabled</td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Wanneer u segmenten van Audience Manager tot [!DNL Analytics] wilt delen om publieksdetectie, segmentatie en optimalisatie te informeren.</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Gebruik Audience Manager-segmenten die demografische gegevens van externe providers in [!DNL Analytics] -rapporten bevatten.</li>
                    <li>Gebruik Audience Manager-segmenten die campagnegegevens van advertentieservers in [!DNL Analytics] -rapporten bevatten.</li>
                    <li>Gebruik Audience Manager-segmenten die niet-gecodeerde CRM-gegevens in [!DNL Analytics] -rapporten bevatten.</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>
