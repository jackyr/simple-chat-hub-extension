<p align="center">
  <img src="assets/logo.svg" width="72" height="72" alt="Logo de Simple Chat Hub">
</p>

# Simple Chat Hub

**Une question. Des réponses d’IA côte à côte.**

[Site web](https://chathub.aipilot.cc/?lang=fr) · [Commentaires](https://chathub.aipilot.cc/feedback?lang=fr) · [Historique des versions](CHANGELOG.md)

[English](README.md) · [简体中文](README_CN.md) · [繁體中文](README_TW.md) · [Español](README_ES.md) · [العربية](README_AR.md) · [Русский](README_RU.md) · **[Français](README_FR.md)** · [Deutsch](README_DE.md) · [Português (Portugal)](README_PT_PT.md) · [Português (Brasil)](README_PT_BR.md) · [日本語](README_JA.md) · [한국어](README_KO.md)

Simple Chat Hub réunit les sites de ChatGPT, Gemini, DeepSeek, Doubao, Kimi et d’autres plateformes d’IA côte à côte dans une fenêtre. Écrivez une fois dans le champ commun : chaque plateforme reçoit votre question et répond. Poursuivez ensuite avec celle que vous souhaitez explorer davantage.

Vous utilisez les sites des plateformes avec vos comptes déjà connectés. Aucune clé API ni inscription à Simple Chat Hub n’est nécessaire.

![Espace Simple Chat Hub avec ChatGPT, Gemini et DeepSeek répondant à une question en français](screenshots/workspace-writing-fr.png)

Interface réelle du produit

## Quelques façons de l’utiliser

- **Comprendre un concept.** Demandez la différence entre corrélation et causalité, comparez les exemples et les explications, puis poursuivez avec la plateforme la plus claire.
- **Analyser des documents.** Soumettez le même bilan hebdomadaire à plusieurs IA. Comparez les points clés et les questions à vérifier, puis revenez aux documents d’origine.
- **Résoudre un problème technique.** Demandez pourquoi une page envoie deux fois la même requête API. Comparez les pistes et approfondissez-en une.

## Fonctionnalités

- **Une question, des réponses côte à côte.** Envoyez la même question à toutes les plateformes de l’espace actuel depuis le champ commun. Joignez des fichiers en les sélectionnant, en les collant ou en les faisant glisser.
- **Des conversations indépendantes.** Chaque plateforme conserve son propre contexte. Posez une question de suivi dans son champ ou utilisez une seule plateforme.
- **Des espaces par tâche.** Enregistrez vos combinaisons pour apprendre, analyser ou développer. Choisissez noms et icônes, et changez d’espace au clavier. Placez plusieurs onglets dans une colonne, ajustez sa largeur et repliez la barre latérale.
- **Enregistrer et reprendre.** Sauvegardez les liens des conversations en cours et leur disposition, puis retrouvez-les en un clic.
- **Bibliothèque de prompts.** Enregistrez vos instructions fréquentes et insérez-les d’un clic ou au clavier. L’optimisation des prompts aide à clarifier vos idées.
- **Captures longues.** Enregistrez une conversation complète d’une plateforme en image, à une largeur adaptée à l’ordinateur ou au mobile.
- **Lancement externe.** Copiez un lien dans le menu de l’espace et configurez-le dans Alfred ou un autre lanceur. Ouvrez Hub avec une question à envoyer automatiquement ou à préremplir.
- **Autres détails.** Plus de 30 plateformes chinoises et internationales intégrées, ajout de sites personnalisés, raccourcis configurables, thèmes clair et sombre et 12 langues d’interface.

## Installation

**Application de bureau** · Windows / macOS / Linux

[Télécharger](https://chathub.aipilot.cc/?lang=fr#download) · [GitHub Releases](https://github.com/jackyr/simple-chat-hub-extension/releases)

Les programmes d’installation pour macOS et Windows ne sont actuellement pas signés avec un certificat de développeur, et la version macOS n’a pas été notarisée par Apple. Lors de la première installation ou ouverture, le système peut indiquer qu’il ne peut pas vérifier le développeur ou l’éditeur. Téléchargez les programmes d’installation depuis la page de téléchargement officielle ou la section GitHub Releases du projet. Sur macOS, ouvrez le fichier DMG et déplacez l’application dans Applications. Si la première ouverture est bloquée, assurez-vous que la source du téléchargement est fiable, puis ouvrez Réglages Système → Confidentialité et sécurité. Dans Sécurité, choisissez Ouvrir quand même, confirmez l’ouverture et authentifiez-vous si demandé.

Installez l’extension depuis la boutique officielle de votre navigateur :

- [Chrome Web Store](https://chromewebstore.google.com/detail/dpfkgaedamhcmkkgeiajeggihmfjhhlj)
- [Microsoft Edge Add-ons](https://microsoftedge.microsoft.com/addons/detail/simple-chat-hub/plaobjkecadfmaglmhdaolohmckjgnom)
- [Firefox Add-ons](https://addons.mozilla.org/firefox/addon/simple-chat-hub/)

Pour une installation hors ligne, téléchargez un paquet depuis la [liste des fichiers du dépôt](https://github.com/jackyr/simple-chat-hub-extension) : `.crx.zip` pour Chrome / Edge ou `.xpi.zip` pour Firefox. Décompressez l’archive avant l’installation. L’installation manuelle dépend des restrictions du navigateur et du système d’exploitation ; les boutiques officielles sont recommandées.

## Premiers pas

1. Installez l’extension et cliquez sur l’icône Simple Chat Hub dans la barre d’outils du navigateur.
2. Connectez-vous aux plateformes dans leurs colonnes. Si la connexion échoue dans une colonne, connectez-vous dans un nouvel onglet du navigateur, puis actualisez la colonne.
3. Choisissez votre combinaison de plateformes et enregistrez-la dans un espace.
4. Interrogez-les depuis le champ commun, lisez les réponses côte à côte et poursuivez où vous le souhaitez.

L’extension est gratuite. Chaque plateforme définit ses comptes, abonnements, quotas et exigences réseau. Le remplissage et l’envoi automatiques dépendent de la structure des sites. Après une modification, un envoi manuel peut être temporairement nécessaire ; nous maintenons la compatibilité par des mises à jour de configuration. L’envoi de pièces jointes dépend aussi de la plateforme. Certaines, comme Grok, ne fonctionnent pas normalement dans l’extension : utilisez l’application de bureau ou un nouvel onglet.

## Ouvrir Hub depuis Alfred ou un autre lanceur

1. Survolez l’espace souhaité dans la barre latérale et choisissez **Copier le lien de lancement** dans son menu.
2. Collez le lien dans l’action d’ouverture d’URL du lanceur. Il contient déjà l’adresse de Hub propre à votre installation et les plateformes sélectionnées.
3. Configurez le lanceur pour remplacer `{query}` par la question, encodée une seule fois pour une URL, et ouvrir un **nouvel onglet** dans le navigateur et le profil où l’extension est installée.
4. Le lien copié contient `send=1` pour envoyer la question lorsque les plateformes sont prêtes. Supprimez `send=1` pour remplir le champ partagé sans envoyer la question.

Utilisez votre propre lien copié : les adresses des extensions varient selon le navigateur, le profil et la méthode d’installation. Consultez la [FAQ du site web](https://chathub.aipilot.cc/?lang=fr#faq) pour en savoir plus.

## Plateformes

Les plateformes intégrées comprennent notamment ChatGPT, Gemini, Claude, DeepSeek, Copilot, Grok, Perplexity, Qwen, Kimi, Doubao, Yuanbao, Mistral, Meta et Z.ai. Vous pouvez aussi ajouter des sites personnalisés dans les paramètres.

## Données et confidentialité

Vos données personnelles, notamment vos espaces, votre bibliothèque de prompts et vos liens vers des conversations enregistrées, sont stockées localement. Les questions et pièces jointes sont envoyées aux plateformes d’IA que vous choisissez.

Nous utilisons Google Analytics pour recueillir anonymement des statistiques de base sur l’utilisation de l’interface (comme les clics sur les boutons et les raccourcis clavier) et les erreurs, afin d’améliorer le produit.

Lorsque vous optimisez un prompt, le texte saisi est envoyé aux serveurs de Simple Chat Hub pour traitement. Nous ne collectons ni ne conservons ce texte.

## Commentaires

Signalez un problème ou proposez une amélioration via la [page de commentaires](https://chathub.aipilot.cc/feedback?lang=fr) ou [GitHub Issues](https://github.com/jackyr/simple-chat-hub-extension/issues). Pour un rapport de bogue, indiquez la plateforme, le navigateur, la version de l’extension et les étapes permettant de reproduire le problème.

## Dons

Le développement et la maintenance demandent du travail. Si cette extension vous plaît ou vous est utile, offrez-moi un café !

| [Buy Me A Coffee](https://buymeacoffee.com/jackyrao)                                                                          | [PayPal](https://paypal.me/jackyrao)                                                                             | WeChat                                                  |
| ----------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------- |
| <a href="https://buymeacoffee.com/jackyrao" target="_blank"><img src="qrcodes/bmc.png" width="200" alt="Buy Me A Coffee"></a> | <a href="https://paypal.me/jackyrao" target="_blank"><img src="qrcodes/paypal.png" width="200" alt="PayPal"></a> | <img src="qrcodes/wechat.png" width="200" alt="WeChat"> |

## Donateurs

Merci aux personnes qui soutiennent le projet ! Votre soutien contribue à le faire vivre.

[Voir la liste des donateurs](DONORS.md)
