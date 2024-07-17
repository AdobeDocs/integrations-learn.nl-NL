---
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '305'
ht-degree: 0%

---


# Adobe [!DNL Analytics] integreren met realtime klantgegevens [!DNL Platform]

{{analytics-description}}

{{real-time-cdp-description}}

Het integreren van Adobe [!DNL Analytics] met Adobe Real-Time Customer Data [!DNL Platform] (Real-Time CDP) kan verschillende voordelen bieden voor bedrijven die hun klantervaringen en marketinginspanningen willen verbeteren. Hier volgen enkele belangrijke voordelen:

+ **Verbeterde publiek richtend &amp; verpersoonlijking**: Precieze marketing op apparaten &amp; kanalen, op maat gemaakte berichten voor geoptimaliseerde overeenkomst.
+ **Verbeterde het landen paginamoptimalisering**: Getelegrafeerde ervaringen die op apparaat en gedrag worden gebaseerd, die gebruikerstevredenheid &amp; omzetting verbeteren.
+ **Naadloze publieksactivering**: Gebruik klantenprofielen voor effectief het richten door aangewezen kanalen, leverend relevante berichten.

Door Adobe [!DNL Analytics] en Real-Time CDP te combineren, kunnen bedrijven hun marketinginspanningen op een hoger niveau brengen, persoonlijke ervaringen bieden, de betrokkenheid van klanten verhogen en conversies optimaliseren voor verschillende digitale aanraakpunten.

<table>
    <thead>
        <tr>
            <th>Experiencen Cloud</th>
            <th>Integreert met</th>
            <th>Wanneer gebruiken</th>
            <th>Vaak voorkomende gebruiksscenario's</th>
        </tr>
    </thead>
    <tr>
        <td rowspan="2">[!DNL Analytics] met Real-Time CDP</td>
        <td><a href="../../integrations/tutorials/analytics-rtcdp/experience-platform-source-connector.md" target="_blank" rel="noreferrer">Experience [!DNL Platform] bronaansluiting</a></td>
        <td>
            <ul style="margin-top: 0;">
                <li>Aanbevolen aanpak voor klanten die al Adobe [!DNL Analytics] hebben geïmplementeerd en de snelste manier willen om deze gegevens in te voeren in de Experience [!DNL Platform] voor gebruik in het Real-Time Klantprofiel.</li>
                <li>Wanneer de gegevensbeschikbaarheid aan het Real-Time Profiel van de Klant tussen 2-30 minuten van de tijd van gegevensinzameling kan zijn, en beschikbaarheid aan het meer van Gegevens is tot 90 minuten.</li>
            </ul>
        </td>
        <td>
            <ul style="margin-top: 0;">
                <li>Eenvoudig, door de gebruikersinterface geïnitieerde workflow.</li>
                <li>Wijs de gebruikersinterface toe om [!DNL Analytics] eigenschappen en eVars naar nieuwe XDM-velden te kopiëren.</li>
                <li>Snelste manier om waarde te krijgen van het Real-Time Klantprofiel en de Reis van de Klant [!DNL Analytics].</li>
            </ul>
        </td>
    </tr>
    <tr>
       <td><a href="../../integrations/tutorials/analytics-rtcdp/experience-platform-edge.md" target="_blank" rel="noreferrer">Experience [!DNL Platform] Edge</a></td>
        <td>
            <ul style="margin-top: 0;">
                <li>Aanbevolen aanpak voor nieuwe [!DNL Analytics] -implementaties of wanneer u een langetermijnstrategie wilt implementeren.</li>
                <li>Verstuurt gegevens rechtstreeks van een apparaat naar de Experience [!DNL Platform] met behulp van de AEP Web SDK, AEP Mobile SDK of de Edge Network Server API.</li>
                <li>Nieuwe of bestaande klanten die [!DNL Analytics] gegevensbeschikbaarheid aan het Real-Time Profiel van de Klant nodig hebben om dezelfde en volgende pagina te steunen verpersoonlijkingsgebruiksgevallen.</li>
            </ul>
        </td>
        <td>
            <ul style="margin-top: 0;">
                <li>Verstrekt het grootste niveau van controle voor gegevens die voor het steunen van uw gebruiksgevallen worden verzameld.</li>
                <li>Clientgegevens worden eenvoudig toegewezen aan XDM-velden.</li>
                <li>De snelste gegevensbeschikbaarheid aan het Profiel van de Klant in real time.</li>
            </ul>
        </td>
    </tr>            
</table>
