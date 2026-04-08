# Livechat Overlay pour Discord

Livechat Overlay est un outil léger et transparent destiné aux streamers et aux joueurs. Il permet d'afficher en temps réel les messages d'un salon Discord en superposition sur n'importe quel jeu ou application, sans interférer avec la souris grâce à son mode "clic-au-travers" (click-through).

---

## Installation

1. Accédez à la section **[Releases](../../releases/latest)** située sur la droite.
2. Téléchargez l'exécutable de la dernière version (`Livechat-Overlay-Setup-X.X.X.exe`).
3. Lancez le fichier téléchargé pour procéder à l'installation.
4. Démarrez l'application depuis le raccourci créé sur votre bureau.

> **Note :** L'application intègre un système de mise à jour automatique. Les nouvelles versions seront téléchargées et installées silencieusement lors du lancement.

---

## Configuration du Bot Discord (Prérequis)

Pour que l'overlay puisse accéder aux messages de votre serveur, la création d'un Bot Discord personnel est nécessaire.

### Étape 1 : Créer l'application
1. Connectez-vous au **[Discord Developer Portal](https://discord.com/developers/applications)**.
2. Cliquez sur **New Application** en haut à droite, nommez votre application (ex: *Livechat*) et validez.
3. Dans le menu latéral gauche, accédez à la section **Bot**.

### Étape 2 : Activer les Intents
1. Sur la page **Bot**, descendez jusqu'à la section **Privileged Gateway Intents**.
2. Activez l'option **Message Content Intent**.
3. Sauvegardez via le bouton **Save Changes** en bas de page.

### Étape 3 : Récupérer le Token
1. Sur la même page, remontez à la section **Token**.
2. Cliquez sur **Reset Token** (puis confirmez).
3. Copiez le code généré. Ce Token sera à insérer dans les Réglages Avancés de l'application Livechat.

> **Attention :** Ne partagez jamais votre Token. Il permet à quiconque de contrôler votre bot.

### Étape 4 : Inviter le Bot sur le serveur
1. Cliquez sur **OAuth2** puis **URL Generator** dans le menu de gauche.
2. Dans la section *Scopes*, cochez **bot**.
3. Dans la section *Bot Permissions*, cochez **Read Messages/View Channels**.
4. Copiez l'URL générée en bas de page, ouvrez-la dans un nouvel onglet, sélectionnez votre serveur et autorisez le bot.

### Étape 5 : Récupérer l'ID du salon
L'application doit cibler un salon spécifique pour récupérer les messages.
1. Ouvrez Discord.
2. Rendez-vous dans les Paramètres (roue crantée) > **Avancé** et activez le **Mode Développeur**.
3. Faites un clic droit sur le salon ciblé et sélectionnez **Copier l'identifiant du salon**.
4. Collez cet ID dans les Réglages Avancés de l'application.

Une fois le Token et l'ID du salon renseignés dans l'application, vous pouvez configurer votre profil et lancer l'overlay.

---

## Support

Projet développé par **3liotlsj**.

Pour toute question, suggestion ou demande d'assistance technique concernant la configuration, vous pouvez me contacter sur Discord :

**[Discuter avec @3liotlsj](https://discordapp.com/users/TON_ID_DISCORD_ICI)**

*(Utilisez l'application Discord de préférence pour que le lien s'ouvre correctement sur le profil).*