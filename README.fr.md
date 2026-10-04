# OpenSide

**Un assistant IA gratuit pour Windows : écrivez ce dont vous avez besoin dans un chat, et l'IA s'en charge dans le Chrome ou l'Edge que vous utilisez déjà, de la recherche aux clics et à la saisie.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md) · Français

> Ce document est une traduction. En cas de différence, la [version coréenne](README.ko.md) fait foi.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20(64--bit)-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/openside?lang=fr)

![Écran d'OpenSide](images/openside-en.png)

## Présentation

Beaucoup de tâches sur le web demandent de nombreux clics mais peu de réflexion : rassembler dans un tableau les prix de plusieurs boutiques, remplir le même formulaire encore et encore, publier sur un blog, retrouver le bon e-mail dans sa boîte de réception.

OpenSide vous permet de confier ce travail en une ligne de chat. Écrivez la tâche dans la case « Que puis-je faire pour vous ? » : l'IA ouvre les sites dans votre navigateur, lit les pages, clique sur les boutons et saisit le texte jusqu'au bout, puis vous donne le résultat en quelques phrases. Les données collectées peuvent vous parvenir sous forme de fichier Excel.

Il n'utilise pas de navigateur à part : il travaille **dans le Chrome ou l'Edge que vous utilisez déjà**. Les sites où vous êtes connecté ne demandent pas de nouvelle connexion, et comme l'IA travaille dans son propre onglet, vous pouvez continuer à utiliser vos autres onglets pendant ce temps. Associez Telegram et vous pourrez confier des tâches et recevoir les résultats depuis votre téléphone quand vous êtes dehors.

Pour l'IA elle-même, connectez-vous avec un compte ChatGPT que vous possédez déjà, ou saisissez une clé API Claude, OpenAI ou Gemini.

## Fonctionnalités

- **Tâches web par chat** — décrivez la tâche ; l'IA cherche, clique, saisit et passe d'une page à l'autre pour vous, puis vous rend compte.
- **Votre navigateur, vos connexions** — il se connecte au Chrome ou à l'Edge que vous utilisez, donc les sites où vous êtes connecté fonctionnent tout de suite.
- **Travail répétitif** — confiez d'un coup les tâches qui se répètent, comme remplir des formulaires ou collecter des données sur de nombreuses pages.
- **Enregistrer dans Excel** — les données collectées arrivent en fichier Excel (.xlsx), ou en CSV si vous le demandez.
- **Contrôle à distance par Telegram** — envoyez des tâches depuis Telegram sur votre téléphone et recevez réponses et fichiers. Inutile de créer un bot vous-même.
- **Joindre des fichiers** — joignez des images, du texte ou des CSV pour que l'IA les lise, ou pour qu'elle les envoie sur un site.
- **Se souvient de ce que vous avez vu** — une fois activé, il enregistre les pages que vous lisez et les applis que vous utilisez, et s'en sert pour des questions comme « l'article que j'ai lu hier ».
- **À l'aise sur les sites courants** — la publication sur Naver Blog, Tistory et Blogger, Gmail, Google Docs et Sheets, Notion, Slack, YouTube, Naver Real Estate et d'autres sont traités avec des méthodes propres à chaque site, plus rapides et plus précises.
- **Plusieurs comptes IA** — enregistrez une connexion ChatGPT (Codex) et des clés API Claude, OpenAI et Gemini, et passez de l'un à l'autre directement dans le chat.
- **Mode sombre · 9 langues** — coréen, anglais, japonais, chinois, russe, italien, français, espagnol et arabe.

## Téléchargement / Installation

| Édition | Lien |
|---|---|
| Installateur | [Télécharger](https://down.kilho.net/openside?lang=fr) |
| Portable (ZIP) | [Télécharger](https://down.kilho.net/openside?lang=fr&nosetup) |

L'installateur lance OpenSide dès la fin de l'installation. Pour l'édition portable, décompressez le ZIP et lancez `OpenSide.exe`. Les deux éditions ont les mêmes fonctions ; seule la valeur initiale de **Lancer à l'ouverture de session** diffère — activée pour l'installateur, désactivée pour l'édition portable.

## Utilisation

### Premiers pas

1. Lancez OpenSide. Au premier lancement, la page de réglage de la connexion s'ouvre d'elle-même dans votre navigateur (Chrome ou Edge).
2. Sur cette page, cochez la case **Remote debugging**. Si la page ne s'est pas ouverte, tapez `chrome://inspect/#remote-debugging` (pour Edge, `edge://inspect/#remote-debugging`) dans la barre d'adresse du navigateur.
3. Quand le navigateur affiche une demande de connexion, cliquez sur **Autoriser**. Ce réglage ne se fait qu'une fois.
4. **Préférences** s'ouvre ensuite sur **Compte**. Cliquez sur **Ajouter**, choisissez l'IA à utiliser (par exemple **Se connecter à Codex**) et connectez-vous sur la page qui s'ouvre dans le navigateur. Quand « Connexion réussie » s'affiche, fermez cette fenêtre et revenez à OpenSide.
5. Écrivez une tâche dans la case de chat (« Que puis-je faire pour vous ? ») et appuyez sur **Entrée**. Par exemple : « Donne-moi les titres des 5 dernières annonces de kilho.net ».
6. Pendant que l'IA travaille, sa progression s'affiche ligne par ligne. À la fin, le résultat apparaît comme réponse et la progression se replie en une seule ligne « N s de travail », sur laquelle vous pouvez cliquer pour la déplier.

### Organisation de l'écran

| Élément | Rôle |
|---|---|
| Titre du chat | Le titre de la discussion en cours. Il est tiré de votre premier message ; cliquez dessus pour le modifier (**Entrée** enregistre · **Échap** annule) |
| **Sessions récentes** | Vos discussions passées (les 15 plus récentes). Choisissez-en une pour la poursuivre |
| **Nouvelle discussion** | Commence une nouvelle discussion |
| **Paramètres** | Ouvre la fenêtre **Préférences** |
| Trombone (**Joindre des fichiers**) | Joint des fichiers au message. Ils apparaissent sous la case de saisie ; retirez-en un avec × |
| Case de saisie · **Envoyer** | Écrivez la tâche et envoyez-la. Pendant que l'IA travaille, **Envoyer** devient **Arrêter** |
| Icône **Contrôle à distance** | Active et désactive le contrôle par Telegram. Verte quand il est actif |
| Icône de l'œil (**Historique**) | Visible seulement quand l'enregistrement des pages est actif. Cliquez pour mettre en pause ou reprendre l'enregistrement |
| Anneau d'utilisation | Utilisation d'un compte **Se connecter à Codex**. Survolez-le pour voir ce qu'il reste |
| Compte · modèle · niveau de raisonnement | Choisissez le compte IA, le modèle et la profondeur de réflexion pour cette discussion |

### Que faire quand…

**Rassembler dans un tableau les informations de plusieurs sites**
Dites quoi collecter et sous quelle forme, par exemple « Trouve le prix de l'ordinateur portable modèle A dans trois boutiques et mets-le dans Excel ». À la fin, une carte **⬇ Télécharger** apparaît dans le chat. Cliquez dessus pour choisir où enregistrer (le dossier Téléchargements au départ) ; ensuite, **Ouvrir le fichier** et **Ouvrir le dossier** l'ouvrent aussitôt. Le fichier Excel conserve intactes les valeurs qui commencent par zéro, comme `007` ou les numéros de téléphone. S'il vous faut un fichier pour un autre programme, dites « en CSV » : il est écrit pour que les caractères non latins s'affichent correctement.

**Remplir le même formulaire plusieurs fois**
Dites par exemple « Envoie une demande pour chaque personne de cette liste ». L'IA remplit d'un coup les champs, cases à cocher et listes déroulantes, et vérifie que le résultat apparaît avant de passer au suivant ; elle n'appuie donc jamais deux fois sur un bouton d'envoi. Si la liste est dans un fichier, joignez-le.

**Quand vous voulez seulement qu'elle regarde, et quand vous voulez que ce soit fait**
Si vous dites « compare » ou « écris juste un brouillon », l'IA ne fait rien d'irréversible, comme envoyer, payer, supprimer ou publier. Si vous dites « envoie-le » ou « commande-le », elle mène la tâche jusqu'au dernier bouton sans redemander. Mieux vaut indiquer clairement dans votre message jusqu'où aller.

**Publier sur un blog**
Dites par exemple « Rédige ceci en article Naver Blog et publie-le ». Sur Naver Blog, Tistory et Blogger, le titre, le corps, les intertitres, les images et les tags sont saisis avec des méthodes adaptées à chaque site. Joignez les images à inclure.

**Travailler avec la messagerie, les documents et les outils de travail**
Dites par exemple « Trouve dans Gmail l'e-mail de devis de la semaine dernière et résume-le », « Lis les valeurs de la colonne B de ma feuille Google », « Ajoute les notes du jour à la page de compte rendu dans Notion » ou « Donne-moi les derniers messages du canal Slack #annonces ». Il travaille avec les comptes déjà connectés dans votre navigateur. Si plusieurs comptes Google sont connectés, précisez lequel et il travaillera dans celui-là.

**Faire des recherches sur YouTube, X et LinkedIn**
Dites par exemple « Résume la transcription de cette vidéo YouTube », « Résume les réactions dans les commentaires de cette vidéo », « Rassemble les publications récentes sur ce sujet sur X » ou « Trouve les offres d'emploi de cette entreprise sur LinkedIn ».

**Rassembler des annonces immobilières**
Dites par exemple « Mets dans Excel les annonces en jeonse de la résidence ○○ sur Naver Real Estate », et il transforme les annonces en tableau.

**Trouver des images**
Dites par exemple « Trouve 10 photos de ○○ et rassemble leurs adresses », et il collecte les URL des images dans les résultats de recherche.

**Utiliser d'autres onglets pendant qu'elle travaille**
L'IA ne bouge que dans l'onglet où elle travaille ; vous pouvez donc continuer votre travail dans les autres onglets du même navigateur. Son onglet continue de fonctionner même en arrière-plan, comme s'il était au premier plan. Si vous confiez la tâche suivante dans la même discussion, elle continue dans l'onglet où elle travaillait, même si vous regardez un autre onglet. Une nouvelle discussion commence dans l'onglet que vous regardez.

**Les onglets qu'elle ouvre et les vôtres**
L'IA n'ouvre un nouvel onglet que lorsqu'elle a besoin de deux pages à la fois, et ferme les onglets qu'elle a ouverts avant de répondre. Elle ne ferme pas les onglets que vous avez ouverts. Si vous voulez faire le tri dans vos onglets, demandez-le directement, par exemple « Ferme tous les onglets kilho.net ».

**Quand un code de vérification ou une validation dans l'appli bancaire est nécessaire**
Quand une étape demande une personne — un code envoyé sur votre téléphone, une validation dans l'appli de la banque, un CAPTCHA textuel —, l'IA met cet onglet au premier plan et vous dit en une ligne quoi faire. Faites-le dans le navigateur, ou tapez le code dans la case de chat, et l'IA reprend. L'IA coche elle-même les cases « Je ne suis pas un robot » et ne vous passe la main que lorsqu'un défi de sélection d'images apparaît. Si une inscription demande un lien ou un code envoyé par e-mail et que Gmail est connecté dans le navigateur, l'IA ouvre la boîte de réception et le trouve.

**Ajouter quelque chose pendant qu'elle travaille**
Vous pouvez écrire dans la case de chat même pendant que l'IA travaille. Votre message va directement à la tâche en cours. Servez-vous-en pour changer de direction (« écris les prix en wons ») ou pour répondre à une question qu'elle a posée. Pour l'arrêter, cliquez sur **Arrêter**.

**Lui faire lire des fichiers de votre PC, ou les envoyer sur un site**
Joignez des fichiers avec le trombone et envoyez-les : l'IA les lit. Elle regarde le contenu des images (png, jpg, gif, webp) et lit et utilise les fichiers texte et CSV. Vous pouvez en joindre plusieurs à la fois, et les fichiers d'origine ne sont jamais modifiés. Dites par exemple « Joins la photo que j'ai envoyée à un message sur ce forum », et l'IA s'occupe aussi de la fenêtre d'envoi de fichiers du site.

**Lui faire toujours lire un dossier précis**
Si joindre à chaque fois est fastidieux, ajoutez le dossier dans **Préférences** → **Fichiers** → **Dossier lisible par l'IA** (**Ajouter un dossier...**). Vous pouvez alors dire par exemple « Avec la liste de clients de mon dossier de données, … ». L'IA ne fait que lire ce dossier et n'y écrit jamais. N'ajoutez que les dossiers nécessaires.

**Retrouver une page vue auparavant**
Activez **Enregistrer les pages lues et les applis utilisées** dans **Préférences** → **Historique**, et OpenSide enregistre le texte des pages que vous lisez et les fenêtres des applis que vous utilisez. Vous pouvez alors dire par exemple « Résume à nouveau l'article sur l'investissement que j'ai lu hier » ou « Compare les avantages et inconvénients des hôtels que j'ai regardés tout à l'heure ». Les enregistrements sont conservés 30 jours, et les pages comportant un champ de mot de passe ne sont pas enregistrées. Indiquez les sites et applis à ne pas enregistrer, séparés par des virgules (p. ex. `bank.com, kakaotalk.exe`). Pour mettre l'enregistrement en pause, cliquez sur l'icône de l'œil dans l'écran du chat ; pour tout effacer, cliquez sur **Tout supprimer**. Cette fonction est désactivée au départ.

**Retrouver un site visité auparavant**
Dites par exemple « Ouvre le site de ce fleuriste que j'ai visité la dernière fois », et il le retrouve dans l'historique du navigateur et l'ouvre.

**Confier des tâches depuis votre téléphone (Telegram)**
1. Dans **Préférences** → **À distance**, cliquez sur **Associer**. Un QR code et un code d'association apparaissent, valables 10 minutes.
2. Scannez le QR code avec l'appareil photo du téléphone. Quand Telegram s'ouvre, touchez **Démarrer**. Si Telegram est installé sur votre PC, vous pouvez aussi cliquer sur **Ouvrir sur ce PC**.
3. Quand Telegram affiche un message indiquant que la connexion est établie, c'est terminé. Envoyez maintenant une tâche par message texte dans Telegram, et OpenSide sur votre PC l'exécute et vous renvoie la réponse.

Les fichiers créés et les demandes comme « veuillez saisir le code de vérification » arrivent aussi sur votre téléphone. Répondez avec le code dans Telegram et il est transmis à la tâche en cours. Si une réponse est longue, le début arrive en message et le texte complet en fichier. Telegram n'accepte que du texte : envoyez des mots plutôt que des photos. OpenSide doit être lancé sur votre PC pour travailler ; activer **Lancer à l'ouverture de session** est donc pratique quand vous utilisez le contrôle à distance. Pour le désactiver un moment, cliquez sur l'icône **Contrôle à distance** dans l'écran du chat ; pour le déconnecter complètement, cliquez sur **Dissocier**.

**Utiliser plusieurs comptes IA**
Dans **Préférences** → **Compte**, cliquez sur **Ajouter** pour voir les types disponibles.

| Type | Fonctionnement |
|---|---|
| **Se connecter à Codex** | Connexion avec un compte ChatGPT |
| **Clé API Claude...** · **Clé API Gemini...** | Saisissez une clé API |
| **Clé API OpenAI...** | Saisissez une clé API et une **URL de base (.../v1)**. En changeant l'adresse, vous pouvez utiliser d'autres services qui fonctionnent comme OpenAI |

À l'enregistrement d'un compte à clé API, la liste des modèles est récupérée aussitôt pour le vérifier. Choisissez le compte des nouvelles discussions avec **Définir par défaut**, et double-cliquez sur un compte pour le renommer. Pendant une discussion, vous pouvez changer de compte, de modèle et de niveau de raisonnement directement en bas de l'écran du chat. Un niveau de raisonnement plus élevé réfléchit davantage ; un niveau plus bas répond plus vite.

**Voir combien d'utilisation il reste**
Avec un compte **Se connecter à Codex**, un anneau d'utilisation apparaît en bas de l'écran du chat. Il se remplit à mesure que vous l'utilisez ; survolez-le pour voir ce qu'il reste pour chaque période. Quand il est presque épuisé, passez à un autre compte.

**Reprendre une discussion passée**
Cliquez sur **Sessions récentes** pour voir vos 15 dernières discussions avec la date de leur dernière utilisation. Choisissez-en une et continuez. Pour lui donner un titre plus clair, cliquez sur le titre en haut.

**Ce qu'elle retient d'elle-même**
Chaque fois qu'elle termine une tâche, l'IA garde ce qui est confirmé — comment utiliser un site, des faits que vous lui avez donnés — et s'en sert dans les discussions suivantes. Plus vous lui confiez de tâches sur un même site, moins elle tâtonne.

**La garder lancée après avoir fermé la fenêtre**
Cliquer sur la × de la fenêtre ne quitte pas l'application : OpenSide passe dans la zone de notification (barre d'état système). Cliquez sur son icône pour rappeler la fenêtre. Pour quitter complètement, faites un clic droit sur l'icône et choisissez **Quitter**. **Lancer au démarrage** dans ce même menu est le même réglage que **Lancer à l'ouverture de session** dans **Préférences** ; s'il est activé, OpenSide démarre discrètement dans la zone de notification au démarrage de Windows. Une seule copie d'OpenSide tourne à la fois ; la relancer ramène au premier plan la fenêtre déjà ouverte.

**Garder la fenêtre d'OpenSide au premier plan**
Pour garder OpenSide à côté de votre navigateur pendant que vous suivez, réglez **Toujours au premier plan** sur **Activé** dans **Préférences** → **Général**. La position et la taille de la fenêtre sont mémorisées ; elle s'ouvre au même endroit la fois suivante.

**Chrome ou Edge : dans lequel elle travaille**
OpenSide travaille dans le navigateur où **Remote debugging** est activé. Si les deux l'ont activé, il utilise d'abord le navigateur par défaut de Windows. Pour qu'il travaille dans l'autre, activez-le seulement dans ce navigateur.

**Après avoir redémarré le navigateur**
Si une connexion est nécessaire, OpenSide affiche la fenêtre **Une connexion au navigateur est nécessaire** avec les étapes dans l'ordre. Suivez-les et cliquez sur **Connecter**. Cliquer sur l'adresse dans cette fenêtre la copie ; il suffit de la coller dans la barre d'adresse.

## Configuration

Cliquez sur **Paramètres** pour ouvrir la fenêtre **Préférences**. Les changements s'appliquent immédiatement.

| Onglet | Options |
|---|---|
| **Général** | **Toujours au premier plan** · **Thème** (Auto · Clair · Sombre) · **Langue** (Auto ou l'une des 9 langues) · **Lancer à l'ouverture de session** |
| **Compte** | Ajouter, supprimer et connecter des comptes IA · choisir le compte par défaut |
| **À distance** | Associer ou dissocier Telegram |
| **Historique** | Activer l'enregistrement des pages et applis · pause · sites et applis à ne pas enregistrer · tout supprimer |
| **Fichiers** | Dossiers lisibles par l'IA |

Avec **Langue** sur **Auto**, OpenSide suit la langue d'affichage de Windows. Si vous choisissez l'arabe, l'écran passe en lecture de droite à gauche. Les lignes de progression et les réponses de l'IA suivent la langue de votre message. Avec **Thème** sur **Auto**, il suit le mode d'application de Windows (clair ou sombre).

## Configuration requise

- Windows 10 · Windows 11 (64 bits)
- Google Chrome ou Microsoft Edge
- Un compte ChatGPT, ou une clé API Claude, OpenAI ou Gemini
- Une connexion internet

## Mises à jour

Pour la sécurité et pour éviter les fausses alertes des antivirus, OpenSide **ne** se met **pas** à jour tout seul. Au démarrage, il vérifie s'il existe une nouvelle version et vous prévient ; si vous choisissez de la récupérer, il ouvre la page de téléchargement et ferme le programme. Les nouvelles versions sont publiées manuellement après vérification interne et annoncées sur la [page d'OpenSide](https://kilho.net/openside). Consultez l'[avis sur la politique de mise à jour](https://en.kilho.net/archives/notice/2940).

## Licence

OpenSide est un **graticiel** (freeware). Utilisez-le partout — au bureau, à la maison, dans les administrations ou à l'école — gratuitement et sans restriction, et redistribuez-le librement. Le coût d'utilisation de l'IA dépend de l'offre de votre propre compte IA ou clé API.

## Liens

- Site web : <https://kilho.net/openside>
- Forum : <https://kilho.top/forum/qna>
- X (Twitter) : <https://www.twitter.com/kilhonet>

© KILHO.NET
