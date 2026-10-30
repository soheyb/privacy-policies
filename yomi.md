# YOMI — Privacy Policy

**Last updated:** 30 October 2026  
App: YOMI · Package: `com.soheyb.yomi`

> **YOMI has no accounts, no advertising and no gameplay analytics.** Your progress is stored on your device, and we have no server. Information can leave your device in two ways only: a report sent to Unity Technologies when you **buy** the paid content, and, if Android's backup is switched on, a copy of your save made by Android in your Google account. Both are explained below.

## What the app stores on your device

YOMI keeps one save file (`profile.json`, with a backup copy) in the app's private storage on your device. It contains your learning progress and settings:

- which kana you have learned and when they are next due for review;
- your runs, score, best depth, coins, relics, Ascension records and creature compendium;
- your preferences: language, music, sound effects, Japanese voice, screen effects;
- whether you have purchased the paid content.

This file is never sent to us. We have no server. Uninstalling YOMI deletes it from your device.

The game engine (Unity) may also keep small technical preferences in the app's private storage. 

## Android backup

YOMI allows Android's standard backup. Depending on your Android settings, Android's backup service, run by Google, may keep a copy of the app's save file and preferences in your Google account, and restore it if you reinstall YOMI or set up a new phone. This is done by Android and Google, not by YOMI: we never receive that copy, and it is covered by the [Google Privacy Policy](https://policies.google.com/privacy). You can switch the backup off in your Android settings, and delete existing backups from your Google account. 

## Purchases

YOMI is free, and offers a single optional one-time purchase that unlocks the katakana content, and what is added to it later. Payment is handled entirely by **Google Play**. We never see, receive or store your payment details. Google's handling of the transaction is covered by the [Google Privacy Policy](https://policies.google.com/privacy).

### What the purchase library sends to Unity

The app talks to Google Play through **Unity In-App Purchasing** (version 5.4.4), a library made by Unity Technologies. Each time a purchase goes through one of the following steps, this library sends a report over an encrypted connection (HTTPS) to Unity's servers (`prd.insights.analytics.unity3d.com`):

- when you tap the button to buy;
- when Google Play reports the payment;
- when the purchase fails or is cancelled;
- when the purchase is confirmed.

Finding, at start-up, a purchase you already own and that is already confirmed does not send this report. A purchase that still needs confirming (for example a payment that completed while the app was closed) sends the confirmation report when the app confirms it. 

Each report can contain:

- **about the purchase**: the product (its identifier, name, description, type), its displayed price, price and currency, the transaction identifier and, once the purchase is confirmed, the purchase record issued by Google Play (order number, purchase token, purchase time, purchase state) and its signature. If the purchase fails, it also contains the failure reason;
- **about the device and the app**: device model, Android version, system language and language list, total storage space, the time the device was last started, the app's package name and version, the engine version, the time the app was installed and how it was installed;
- **identifiers**: a random identifier generated for each report, a timestamp, and an installation identifier created by Unity's services for this installation of the app. 

The report does **not** contain your name, your email address, your Google account or your payment card. It does not contain your advertising ID: Unity's library only reads it after advertising consent, and YOMI never asks for it.

Unity receives these reports under Unity's Developer Data framework and its own [Privacy Policy](https://unity.com/legal/privacy-policy). We have no access to them: the app is not linked to any Unity dashboard, and we receive no copy. 

## The game engine

YOMI is built with the Unity engine. In this project, Unity's analytics, crash reporting, performance reporting and advertising services are switched off, and the project is not linked to Unity's cloud services. 

## Japanese pronunciation

The game can read kana aloud using the **text-to-speech engine of your own device**. YOMI sends the character to be spoken to that system engine and nothing else. Depending on your device settings, that engine may be provided by Google or another vendor and may process text on their systems. This is governed by your device's speech settings, not by YOMI. You can turn the voice off at any time in the game settings.

## Children

YOMI is not directed at children under 13 and does not knowingly collect any information from them. The purchase reports described above are the same for every user; they do not identify a person, and we do not hold them.

## Permissions

The app requests no permission for camera, microphone, contacts, location or storage beyond its own files. It uses:

- **network access**: for Google Play billing and for the purchase reports described above;
- **network status**: to check whether a connection is available before contacting Google Play;
- **vibration**: for short haptic feedback in the game;
- the **Google Play billing** permission, required to sell the paid content.

## Your choices and deletion

- You can play the whole free part without buying anything. If you never buy, no purchase report is sent.
- Uninstalling YOMI deletes everything stored on your device. A copy kept by Android backup in your Google account is managed in your Android and Google settings.
- We do not hold any data about you, so there is nothing we can delete on our side. For the purchase reports held by Unity, you can contact Unity through its [privacy page](https://unity.com/legal/privacy-policy), or write to us and we will help you.

## Changes

If this policy changes, the new version will be published on this page with a new date above. Any change that affects what the app collects will be announced in the app's release notes. This version replaces the policy of 26 August 2026: the change of game engine introduced the purchase reports described above, and the save may now be copied by Android's backup.

## Contact

Questions about this policy: [soheyb.alouach@gmail.com](mailto:soheyb.alouach@gmail.com)

---

# YOMI — Politique de confidentialité

**Dernière mise à jour :** 30 octobre 2026  
Application : YOMI · Package : `com.soheyb.yomi`

> **YOMI n'a ni compte, ni publicité, ni mesure d'audience du jeu.** Votre progression est enregistrée sur votre appareil, et nous n'avons aucun serveur. Des informations ne peuvent en sortir que de deux façons : un rapport envoyé à Unity Technologies quand vous **achetez** le contenu payant, et, si la sauvegarde d'Android est activée, une copie de votre sauvegarde faite par Android dans votre compte Google. Les détails sont ci-dessous.

## Ce que l'application enregistre sur votre appareil

YOMI conserve un seul fichier de sauvegarde (`profile.json`, avec une copie de secours) dans l'espace privé de l'application, sur votre appareil. Il contient votre progression et vos réglages :

- les kana que vous avez appris et la date de leur prochaine révision ;
- vos parties, votre score, votre profondeur record, vos pièces, vos reliques, vos records d'Ascension et votre bestiaire ;
- vos préférences : langue, musique, bruitages, voix japonaise, effets d'écran ;
- le fait que vous ayez acheté ou non le contenu payant.

Ce fichier ne nous est jamais transmis : nous n'avons aucun serveur. Désinstaller YOMI le supprime de votre appareil.

Le moteur du jeu (Unity) peut aussi garder quelques préférences techniques dans l'espace privé de l'application. 

## Sauvegarde Android

YOMI autorise la sauvegarde standard d'Android. Selon vos réglages Android, le service de sauvegarde d'Android, géré par Google, peut conserver dans votre compte Google une copie du fichier de sauvegarde et des préférences de l'application, et la restaurer si vous réinstallez YOMI ou configurez un nouveau téléphone. C'est Android et Google qui s'en chargent, pas YOMI : nous ne recevons jamais cette copie, et elle relève de la [politique de confidentialité de Google](https://policies.google.com/privacy). Vous pouvez désactiver la sauvegarde dans les réglages d'Android, et supprimer les sauvegardes existantes depuis votre compte Google. 

## Achats

YOMI est gratuit et propose un unique achat facultatif, qui débloque le contenu katakana et ce qui s'y ajoutera ensuite. Le paiement est intégralement traité par **Google Play**. Nous ne voyons, ne recevons et ne stockons aucune donnée de paiement. Le traitement par Google relève de la [politique de confidentialité de Google](https://policies.google.com/privacy).

### Ce que la bibliothèque d'achat transmet à Unity

L'application dialogue avec Google Play par **Unity In-App Purchasing** (version 5.4.4), une bibliothèque d'Unity Technologies. À chacune des étapes suivantes d'un achat, cette bibliothèque envoie un rapport, par une connexion chiffrée (HTTPS), aux serveurs d'Unity (`prd.insights.analytics.unity3d.com`) :

- quand vous touchez le bouton d'achat ;
- quand Google Play signale le paiement ;
- quand l'achat échoue ou est annulé ;
- quand l'achat est confirmé.

Retrouver au démarrage un achat que vous possédez déjà, et déjà confirmé, n'envoie pas ce rapport. Un achat qui reste à confirmer (par exemple un paiement abouti pendant que l'application était fermée) envoie le rapport de confirmation quand l'application le confirme. 

Chaque rapport peut contenir :

- **sur l'achat** : le produit (identifiant, nom, description, type), son prix affiché, son montant et sa monnaie, l'identifiant de la transaction et, une fois l'achat confirmé, le justificatif d'achat émis par Google Play (numéro de commande, jeton d'achat, date d'achat, état de l'achat) avec sa signature ; en cas d'échec, la raison de l'échec ;
- **sur l'appareil et l'application** : le modèle de l'appareil, la version d'Android, la langue du système et la liste des langues, l'espace de stockage total, l'heure du dernier démarrage de l'appareil, le nom de paquet et la version de l'application, la version du moteur, la date d'installation de l'application et son mode d'installation ;
- **des identifiants** : un identifiant aléatoire propre à chaque rapport, un horodatage, et un identifiant d'installation créé par les services d'Unity pour cette installation de l'application. 

Le rapport ne contient **pas** votre nom, votre adresse e-mail, votre compte Google ni votre carte de paiement. Il ne contient pas votre identifiant publicitaire : la bibliothèque d'Unity ne le lit qu'après un consentement publicitaire, que YOMI ne demande jamais.

Unity reçoit ces rapports dans le cadre de son « Developer Data framework » et de sa propre [politique de confidentialité](https://unity.com/legal/privacy-policy). Nous n'y avons pas accès : l'application n'est reliée à aucun tableau de bord Unity, et nous n'en recevons aucune copie. 

## Le moteur du jeu

YOMI est construit avec le moteur Unity. Dans ce projet, les services de mesure d'audience, de rapports de plantage, de rapports de performance et de publicité d'Unity sont désactivés, et le projet n'est relié à aucun service en ligne d'Unity. 

## Prononciation japonaise

Le jeu peut lire les kana à voix haute via le **moteur de synthèse vocale de votre appareil**. YOMI lui transmet le caractère à prononcer, et rien d'autre. Selon les réglages de votre appareil, ce moteur peut être fourni par Google ou un autre éditeur et traiter le texte sur ses propres systèmes : cela dépend des réglages vocaux de votre téléphone, pas de YOMI. La voix peut être désactivée à tout moment dans les réglages du jeu.

## Enfants

YOMI ne s'adresse pas aux enfants de moins de 13 ans et ne collecte sciemment aucune information les concernant. Les rapports d'achat décrits plus haut sont les mêmes pour tous les utilisateurs : ils n'identifient pas une personne, et nous ne les détenons pas.

## Autorisations

L'application ne demande ni caméra, ni micro, ni contacts, ni localisation, ni accès au stockage au-delà de ses propres fichiers. Elle utilise :

- **l'accès réseau** : pour la facturation Google Play et pour les rapports d'achat décrits plus haut ;
- **l'état du réseau** : pour savoir si une connexion est disponible avant de contacter Google Play ;
- **le vibreur** : pour de courts retours tactiles en jeu ;
- l'autorisation de **facturation Google Play**, nécessaire à la vente du contenu payant.

## Vos choix et la suppression

- Toute la partie gratuite se joue sans rien acheter. Sans achat, aucun rapport d'achat n'est envoyé.
- Désinstaller YOMI supprime tout ce qui est enregistré sur votre appareil. Une copie conservée par la sauvegarde Android dans votre compte Google se gère dans vos réglages Android et Google.
- Nous ne détenons aucune donnée vous concernant : il n'y a rien à supprimer de notre côté. Pour les rapports d'achat détenus par Unity, vous pouvez contacter Unity depuis sa [page de confidentialité](https://unity.com/legal/privacy-policy), ou nous écrire : nous vous aiderons.

## Modifications

Toute nouvelle version de cette politique sera publiée sur cette page avec une nouvelle date. Tout changement affectant ce que l'application collecte sera annoncé dans les notes de version. Cette version remplace la politique du 26 août 2026 : le changement de moteur du jeu a introduit les rapports d'achat décrits plus haut, et la sauvegarde peut désormais être copiée par la sauvegarde d'Android.

## Contact

Questions : [soheyb.alouach.dev@gmail.com](mailto:soheyb.alouach.dev@gmail.com)
