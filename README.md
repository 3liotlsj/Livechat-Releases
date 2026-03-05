# 💬 Livechat Overlay pour Discord

Bienvenue sur le dépôt officiel de **Livechat Overlay**, un outil léger et transparent conçu spécialement pour les streamers et les joueurs. 

Il permet d'afficher en temps réel les messages d'un salon Discord par-dessus n'importe quel jeu ou application, sans jamais gêner votre souris grâce à son mode "clic-au-travers".

---

## 📥 Comment télécharger et installer l'application

1. Allez dans la section **[Releases](../../releases/latest)** sur le côté droit de cette page.
2. Téléchargez le fichier **`Livechat-Overlay-Setup-X.X.X.exe`** de la dernière version.
3. Double-cliquez sur le fichier téléchargé pour l'installer.
4. **C'est prêt !** Lancez l'application depuis le raccourci créé sur votre bureau.

> **💡 Note :** Vous n'avez besoin de faire l'installation manuelle qu'une seule fois ! L'application dispose d'un système de **mise à jour automatique**. Elle téléchargera et installera les nouvelles versions toute seule à chaque lancement.

---

## 🤖 Tutoriel : Créer et configurer le Bot Discord (Prérequis)

Pour que l'overlay puisse lire les messages de votre serveur, vous devez créer un "Bot" personnel. Ne vous inquiétez pas, cela prend 2 minutes et c'est totalement gratuit !

### Étape 1 : Créer le Bot
1. Rendez-vous sur le **[Discord Developer Portal](https://discord.com/developers/applications)** et connectez-vous avec votre compte Discord.
2. Cliquez sur le bouton bleu **"New Application"** en haut à droite. Donnez-lui un nom (ex: *Mon Livechat*) et acceptez les conditions.
3. Dans le menu de gauche, cliquez sur l'onglet **"Bot"**.

### Étape 2 : Activer les permissions de lecture (Intents)
*C'est l'étape la plus importante pour que le bot puisse lire vos messages !*
1. Restez sur la page **"Bot"** et descendez jusqu'à la section **Privileged Gateway Intents**.
2. Cochez/Activez la case **Message Content Intent**.
3. Cliquez sur le bouton vert **"Save Changes"** en bas de l'écran.

### Étape 3 : Récupérer le "Token" (Mot de passe du bot)
1. Toujours sur la page **"Bot"**, remontez vers le haut jusqu'à la section **Token**.
2. Cliquez sur **"Reset Token"** (puis sur "Yes, do it!").
3. Un long code secret apparaît : **Copiez-le**. 
> ⚠️ *Ne partagez **JAMAIS** ce code à personne. C'est ce Token que vous devrez coller dans les Réglages Avancés de l'application Livechat.*

### Étape 4 : Inviter le Bot sur votre serveur
1. Dans le menu de gauche, cliquez sur **"OAuth2"** puis sur **"URL Generator"**.
2. Dans la section *Scopes*, cochez uniquement la case **`bot`**.
3. Dans la section *Bot Permissions* qui vient d'apparaître en dessous, cochez : **`Read Messages/View Channels`**.
4. Descendez tout en bas de la page, copiez l'URL générée et collez-la dans un nouvel onglet de votre navigateur internet.
5. Choisissez votre serveur Discord dans la liste et autorisez le bot à le rejoindre !

### Étape 5 : Récupérer l'ID de votre salon vocal/texte
L'application aura besoin de savoir quel salon spécifique elle doit écouter.
1. Ouvrez votre application Discord normale.
2. Allez dans vos Paramètres (Roue crantée) > **Avancé** > Cochez **Mode Développeur**.
3. Faites un **clic droit** sur le salon que vous souhaitez afficher en live, et cliquez sur **"Copier l'identifiant du salon"**.
4. Collez cet ID dans les Réglages Avancés de l'application Livechat.

🎉 **Félicitations ! Vous avez le Token de votre Bot et l'ID de votre salon. Entrez-les dans l'application, créez votre profil, et démarrez l'overlay !**


## 📞 Contact & Support

Ce projet est développé par **3liotlsj**. 

Un bug rencontré ? Une suggestion d'amélioration ? Ou simplement besoin d'aide pour configurer l'overlay ? 
N'hésitez pas à me contacter directement sur Discord !

👉 **[Discuter avec @3liotlsj sur Discord](https://discordapp.com/users/TON_ID_DISCORD_ICI)**

*(N'oubliez pas d'utiliser l'application Discord pour que le lien s'ouvre correctement sur mon profil).*