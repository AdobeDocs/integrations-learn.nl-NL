---
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '373'
ht-degree: 0%

---


# [!DNL Analytics] en integratie van Audience Managers

{{analytics-description}}

{{audience-manager-description}}

Toelatend deze integratie, door Adobe door:sturen [!DNL Analytics] gegevensserver-kant aan Audience Manager, geeft Audience Manager één van zijn belangrijkste gegevensbronnen, namelijk online klantengedragsgegevens. Deze gegevens kunnen dan met andere gegevens, zoals de gegevens van eerste-partijCRM of derdenpartner worden gecombineerd, om rijke klantensegmenten tot stand te brengen. Bovendien worden de segmenten van de Audience Manager vervolgens teruggestuurd naar de webpagina in het antwoord voor verdere analyse door de bezoeker. Beide gevallen van waardevol gebruik worden hieronder beschreven.

De belangrijkste voordelen van de integratie van Adobe [!DNL Analytics] en Audience Manager zijn:

+ **Verbeterde segmentatie**: Adobe combineren [!DNL Analytics] &amp; Audience Manager gegevens voor nauwkeurige, gepersonaliseerde publiekssegmenten in marketing campagnes.
+ **Verenigde klantenprofielen**: Integreer gegevensbronnen om interacties en gedrag te begrijpen en uitgebreide klantprofielen te maken.
+ **Verbeterde en effectievere**: Advertenties optimaliseren met gegevensgestuurde activering vanuit Adobe [!DNL Analytics] en Audience Manager.
+ **Gegevensgestuurde beslissingen**: Maak keuzes via gedetailleerde inzichten, voeg Adobe samen [!DNL Analytics] en Audience Managers.
+ **Persoonlijke ervaringen**: Maak kennis met uw inhoud en aanbiedingen en verrijk de interactie van klanten met beide platforms.

Over het algemeen brengt deze integratie waardevolle gegevens en inzicht in het publiek samen. Hierdoor kunnen bedrijven doelgerichtere en relevante marketingcampagnes opzetten en tegelijkertijd een beter inzicht krijgen in de voorkeuren en het gedrag van hun klanten.

## Gemeenschappelijke integratie

<table>
    <thead>
        <tr>
            <th>Experience Cloud-toepassingen</th>
            <th>Integreert met</th>
            <th>Wanneer gebruiken</th>
            <th>Vaak voorkomende gebruiksscenario's</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <a href="/docs/analytics-learn/tutorials/integrations/audience-manager/enable-server-side-forwarding-in-adobe-launch.html" target="_blank" rel="noreferrer">[!DNL Analytics] gegevens verzenden naar Audience Manager</a>
            </td>
            <td>Adobe [!DNL Analytics] tags extension of AppMeasurement.js met server-side door:sturen ingeschakeld</td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Wanneer u Adobe wilt verzenden [!DNL Analytics] gegevens aan Audience Manager om segmenten tot stand te brengen die met andere bestemmingen van Adobe Experience Cloud, op mensen-gebaseerde bestemmingen, of andere op apparaat-gebaseerde en douanebestemmingen kunnen worden gedeeld die door Audience Manager worden gesteund.</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Segmenten delen naar advertentieplatforms die gedragskenmerken bevatten die zijn verzameld in [!DNL Analytics].</li>
                    <li>Segmenten vergroten met [!DNL Analytics] gegevens om hoogwaardig, dwars-kanaalsegmenten tot stand te brengen om in het richten op locatie te gebruiken.</li>
                    <li>Laag in [!DNL Analytics] gegevens naar segmenten die zijn uitgeschakeld op hashed-id's, zoals e-mail, voor gebruik in sociale-mediaplatforms.</li>
                </ul>
            </td>
        </tr>        
        <tr>
            <td>
                <a href="https://experienceleague.adobe.com/docs/analytics/integration/audience-analytics/mc-audiences-aam.html" target="_blank" rel="noreferrer">Audience Manager die gegevens terugsturen naar [!DNL Analytics]</a>
            </td>
            <td>Adobe [!DNL Analytics] tags extension of AppMeasurement.js met server-side door:sturen ingeschakeld</td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Wanneer u segmenten van Audience Manager aan wilt delen [!DNL Analytics] om publieksontdekking, segmentatie, en optimalisering te informeren.</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>De segmenten van de Audience Manager van het gebruik die demografische gegevens van derdeleveranciers in omvatten [!DNL Analytics] rapporten.</li>
                    <li>De segmenten van de Audience Manager van het gebruik die campagnegegevens van en servers in omvatten [!DNL Analytics] rapporten.</li>
                    <li>De segmenten van de Audience Manager van het gebruik die onboard CRM gegevens in omvatten [!DNL Analytics] rapporten.</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>
