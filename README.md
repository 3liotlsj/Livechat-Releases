# Livechat Overlay for Discord

Livechat Overlay is a lightweight and transparent tool designed for streamers and gamers. It allows you to display messages from a Discord channel in real-time, overlaid on any game or application, without interfering with your mouse thanks to its "click-through" mode.

---

## Installation

1. Go to the **[Releases](../../releases/latest)** section on the right side of this page.
2. Download the executable for the latest version (`Livechat-Overlay-Setup-X.X.X.exe`).
3. Run the downloaded file to proceed with the installation.
4. Launch the application from the shortcut created on your desktop.

> **Note:** The application features an automatic update system. New versions will be downloaded and installed silently upon launch.

---

## Discord Bot Configuration (Prerequisites)

For the overlay to access messages from your server, creating a personal Discord Bot is required.

### Step 1: Create the Application
1. Log in to the **[Discord Developer Portal](https://discord.com/developers/applications)**.
2. Click on **New Application** in the top right corner, name your application (e.g., *Livechat*), and confirm.
3. In the left sidebar menu, go to the **Bot** section.

### Step 2: Enable Intents
1. On the **Bot** page, scroll down to the **Privileged Gateway Intents** section.
2. Enable the **Message Content Intent** option.
3. Save by clicking the **Save Changes** button at the bottom of the page.

### Step 3: Retrieve the Token
1. On the same page, scroll back up to the **Token** section.
2. Click on **Reset Token** (and then confirm).
3. Copy the generated code. This Token must be entered in the Advanced Settings of the Livechat application.

> **Warning:** Never share your Token. It allows anyone to control your bot.

### Step 4: Invite the Bot to Your Server
1. Click on **OAuth2** and then **URL Generator** in the left menu.
2. In the *Scopes* section, check the **bot** box.
3. In the *Bot Permissions* section, check **Read Messages/View Channels**.
4. Copy the URL generated at the bottom of the page, open it in a new tab, select your server, and authorize the bot.

### Step 5: Retrieve the Channel ID
The application must target a specific channel to fetch messages.
1. Open Discord.
2. Go to User Settings (gear icon) > **Advanced** and enable **Developer Mode**.
3. Right-click on the targeted channel and select **Copy Channel ID** (or just "Copy ID").
4. Paste this ID into the Advanced Settings of the application.

Once the Token and Channel ID are entered in the application, you can set up your profile and launch the overlay.

---

## Support

Project developed by **3liotlsj**.

For any questions, suggestions, or requests for technical assistance regarding the configuration, you can contact me on **[Discord](https://discordapp.com/users/1014275331676446781)**:



*(Preferably use the Discord application so the link correctly opens the profile).*