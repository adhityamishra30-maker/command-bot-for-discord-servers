# Custom Discord Management Bot

A customizable Discord bot built with **discord.js** for handling everyday server administration. It manages channels, members, and core moderation tasks — and can be branded with your server's name or owner's name to give your community a more professional, native feel.

## Features

- 📁 **Channel Management** — create, delete, and organize channels
- 👥 **Member Management** — manage roles, permissions, and member actions
- 🛡️ **Basic Moderation** — handle essential server moderation tasks
- 🎨 **Custom Branding** — rename the bot to match your server or owner's name for a professional, native look

## Requirements

- [Node.js](https://nodejs.org/) v18 or higher
- A [Discord Developer Application](https://discord.com/developers/applications) with a bot token
- npm (comes with Node.js)

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure environment variables**

   Create a `.env` file in the root directory:
   ```env
   DISCORD_TOKEN=your-bot-token-here
   CLIENT_ID=your-client-id-here
   GUILD_ID=your-server-id-here
   ```

4. **Run the bot**
   ```bash
   node index.js
   ```

## Usage

Once the bot is online and invited to your server, you can use commands such as:

| Command | Description |
|---|---|
| `/create-channel` | Creates a new channel |
| `/manage-member` | Manage a member's roles/permissions |
| `/moderate` | Perform basic moderation actions |

> Update this table with your bot's actual command names as they're finalized.

## Custom Branding

To rename the bot to match your server or owner's name:
1. Go to the [Discord Developer Portal](https://discord.com/developers/applications)
2. Select your bot application
3. Update the **Name** and **Icon** under the "General Information" tab

This gives the bot a native, professional appearance tailored to your community.

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to open a pull request or issue.

## License

This project is licensed under the [MIT License](LICENSE).
