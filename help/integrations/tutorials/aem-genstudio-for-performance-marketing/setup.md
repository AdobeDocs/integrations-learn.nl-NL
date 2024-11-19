---
title: Adobe GenStudio instellen met AEM Assets en GenStudio for Performance Marketing
description: Leer hoe u de integratie tussen AEM Assets en GenStudio for Performance Marketing instelt.
solution: Experience Manager, GenStudio for Performance Marketing
version: Cloud Service
feature-set: Experience Manager Assets, GenStudio for Performance Marketing
topic: Content Supply Chain
role: User
level: Intermediate
doc-type: Feature Video
duration: 416
last-substantial-update: 2024-11-19T00:00:00Z
jira: KT-16484
source-git-commit: ec0ac56e16a76ad5b7b92c87866464fa21459ce2
workflow-type: tm+mt
source-wordcount: '244'
ht-degree: 6%

---


# Instellen

[Overzicht van teruggaan naar integratie](./overview.md)

Om met Adobe GenStudio te beginnen gebruikend AEM Assets as a Cloud Service en GenStudio for Performance Marketing, moeten beide toepassingen behoorlijk worden gevormd. Het installatieproces omvat verschillende stappen die moeten worden uitgevoerd voordat u Adobe GenStudio volledig kunt integreren met AEM Assets en GenStudio for Performance Marketing.

Deze taken vereisen samenwerking met beheerders die over de juiste machtigingen beschikken om beide systemen te beheren.

<!-- CARDS 

* https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/video-playlists/assets-view
   {title=Set up AEM Assets with Assets view}
* https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/content-hub/set-up
   {title=Enable AEM Assets Content Hub}
* https://experienceleague.adobe.com/en/docs/genstudio-for-performance-marketing/user-guide/get-started
   {title=Set up GenStudio for Performance Marketing}
   {image=https://experienceleague.adobe.com/en/docs/genstudio-for-performance-marketing/user-guide/media_1dd8829962c9e37e1251f3d2d92f5d72c8a58cdaf.png?width=2000&format=webply&optimize=medium}

-->
<!-- START CARDS HTML - DO NOT MODIFY BY HAND -->
<div class="columns">
    <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="Set up AEM Assets with Assets view">
        <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
            <div class="card-image">
                <figure class="image x-is-16by9">
                    <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/video-playlists/assets-view" title="AEM Assets instellen met de Assets-weergave" target="_blank" rel="referrer">
                        <img class="is-bordered-r-small" src="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/video-playlists/assets-view./media_1e4b209baa6169af9b0aefff8a2f1f39816aa6b42.png?width=400&format=png&optimize=medium" alt="AEM Assets instellen met de Assets-weergave"
                             style="width: 100%; aspect-ratio: 16 / 9; object-fit: cover; overflow: hidden; display: block; margin: auto;">
                    </a>
                </figure>
            </div>
            <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
                <div class="top-card-content">
                    <p class="headline is-size-6 has-text-weight-bold">
                        <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/video-playlists/assets-view" target="_blank" rel="referrer" title="AEM Assets instellen met de Assets-weergave"> Opstelling AEM Assets met de mening van Assets </a>
                    </p>
                    <p class="is-size-6">Leer hoe u AEM Assets as a Cloud Service in Assets-weergave kunt gebruiken met deze verzameling videoafspeellijsten die zijn ontworpen om uw productexpertise te vergroten.</p>
                </div>
                <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/video-playlists/assets-view" target="_blank" rel="referrer" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
                    <span class="spectrum-Button-label has-no-wrap has-text-weight-bold"> Leer meer </span>
                </a>
            </div>
        </div>
    </div>
    <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="Enable AEM Assets Content Hub">
        <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
            <div class="card-image">
                <figure class="image x-is-16by9">
                    <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/content-hub/set-up" title="AEM Assets Content Hub inschakelen" target="_blank" rel="referrer">
                        <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/3433513/?format=jpeg&nocache=1732038662663" alt="AEM Assets Content Hub inschakelen"
                             style="width: 100%; aspect-ratio: 16 / 9; object-fit: cover; overflow: hidden; display: block; margin: auto;">
                    </a>
                </figure>
            </div>
            <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
                <div class="top-card-content">
                    <p class="headline is-size-6 has-text-weight-bold">
                        <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/content-hub/set-up" target="_blank" rel="referrer" title="AEM Assets Content Hub inschakelen"> laat AEM Assets Content Hub </a> toe
                    </p>
                    <p class="is-size-6">Leer hoe u de Adobe Experience Manager Assets Content Hub op AEM as a Cloud Service instelt.</p>
                </div>
                <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/content-hub/set-up" target="_blank" rel="referrer" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
                    <span class="spectrum-Button-label has-no-wrap has-text-weight-bold"> Controle </span>
                </a>
            </div>
        </div>
    </div>
    <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="Set up GenStudio for Performance Marketing">
        <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
            <div class="card-image">
                <figure class="image x-is-16by9">
                    <a href="https://experienceleague.adobe.com/en/docs/genstudio-for-performance-marketing/user-guide/get-started" title="GenStudio for Performance Marketing instellen" target="_blank" rel="referrer">
                        <img class="is-bordered-r-small" src="https://experienceleague.adobe.com/en/docs/genstudio-for-performance-marketing/user-guide/media_1dd8829962c9e37e1251f3d2d92f5d72c8a58cdaf.png?width=400&format=webply&optimize=medium" alt="GenStudio for Performance Marketing instellen"
                             style="width: 100%; aspect-ratio: 16 / 9; object-fit: cover; overflow: hidden; display: block; margin: auto;">
                    </a>
                </figure>
            </div>
            <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
                <div class="top-card-content">
                    <p class="headline is-size-6 has-text-weight-bold">
                        <a href="https://experienceleague.adobe.com/en/docs/genstudio-for-performance-marketing/user-guide/get-started" target="_blank" rel="referrer" title="GenStudio for Performance Marketing instellen"> Opstelling GenStudio for Performance Marketing </a>
                    </p>
                    <p class="is-size-6">Meer informatie over hoe u met GenStudio voor prestatiemarketing aan de slag gaat om nieuwe marketingcontent te genereren die aansluit bij uw merk.</p>
                </div>
                <a href="https://experienceleague.adobe.com/en/docs/genstudio-for-performance-marketing/user-guide/get-started" target="_blank" rel="referrer" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
                    <span class="spectrum-Button-label has-no-wrap has-text-weight-bold"> Leer meer </span>
                </a>
            </div>
        </div>
    </div>
</div>
<!-- END CARDS HTML - DO NOT MODIFY BY HAND -->
