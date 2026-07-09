# Bloxware: Roblox Microgames Discord bot
Discord Bot for the Roblox Discord server related to Bloxware: Roblox Microgames. Provides utility functions.

---

## Privacy Policy

_Last updated: July 9, 2026_

### Foreword
All mentions of "bot owner" directly refer to the Roblox group "Generic Incremental Group". For any data inquiries or requests,
contact the bot developer directly via Discord at hattapper.

### What data we collect

When you use the `/register_id` command, we store:
- Your **Discord user ID**
- Your **Roblox user ID**
- Your **total donations** in Robux purchased through the donation board present in the Bloxware: Roblox Microgames game

When server administrators configure the bot, we store:
- **Guild (server) IDs** and associated **channel IDs** for bug reports and system messages
- A boolean flag per guild for the startup greeting setting

During the `/register_id` verification process, the bot temporarily reads your Roblox profile description to check for a verification code. This description is **not stored**.

When using `/get_player_information`, the bot temporarily accesses your datastore data within the Bloxware: Roblox Microgames game in order to display it.
This data is fetched in real time and is never stored by the bot.

When you purchase a donation developer product, a real time message is sent to the bot containing the Roblox account ID along with the amount donated.
If you have a registered account with the bot, the bot will add the donated amount to your total stored donation amount.

### Why we collect it

Your Discord and Roblox user IDs are collected solely to link your accounts for the bot's features (e.g. `/get_player_information`). Guild settings are collected to allow server administrators to configure the bot's behavior in their server. It is also necessary for the bot to determine the Discord account of the player that purchased a donation.

Your total donations are collected to send a message in the communications Discord server which contains the amount donated and your total donations. 
It also is used to provide exclusive member roles for certain donation thresholds.

### How long data is retained

Account links (Discord ID ↔ Roblox ID) and donation totals are stored indefinitely until you request deletion via `/unregister` or contact the bot owner. Guild settings are retained as long as the bot is in the server.

### Who has access

Stored data is only accessible to the bot and its owner/developers. We do not sell, share, or transmit your data to any third party.

If you would like to know exactly what data we have stored about you, you may request it by contacting the bot owner via Discord. Any such information will only be shared directly with the requesting user and with no one else.

### Third-party services

The bot communicates with:
- **Roblox APIs** (`users.roblox.com`, `apis.roblox.com`) to fetch profile and datastore data. Requests are subject to [Roblox's Privacy Policy](https://en.help.roblox.com/hc/en-us/articles/115004630823).
- **Discord's API**, subject to [Discord's Privacy Policy](https://discord.com/privacy).

### Your rights

You can request deletion of your stored data at any time by using the `/unregister` command, which will permanently remove your Discord and Roblox ID link from our database along with any additional metadata (e.g. donation totals).

### Contact

If you have questions or want to manually request data deletion, contact the bot owner via Discord.
