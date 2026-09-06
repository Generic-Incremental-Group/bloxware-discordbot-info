# Bloxware: Roblox Microgames Discord bot
Discord Bot for the Roblox Discord server related to Bloxware: Roblox Microgames. Provides utility functions.

---

## Privacy Policy

_Last updated: September 6th, 2026_

### Foreword
All mentions of "bot owner" directly refer to the Roblox group "Generic Incremental Group". For any data inquiries or requests,
contact the bot developer directly via Discord at hattapper.

All mentions of "bot" and "application" refer to the Discord Application under the handle `Bloxware Bot#1610`

### What data we collect

When you use the `/verify` command, we store:
- Your **Discord user ID**
- Your **Roblox user ID**
- Your **total donations** in Robux purchased through the donation board present in the Bloxware: Roblox Microgames game

When server administrators configure the bot, we store, per server:
- **Guild (server) IDs** and associated **channel IDs** for bug reports, system messages, donation announcements, and general announcements
- **Role IDs** for the verified role, the self-service notification roles, and the developer role used to gate administrative commands
- **Donation thresholds** and the **role IDs** awarded at each threshold
- A boolean flag per guild for the startup greeting setting

This configuration describes the server, not its members. No per-member role data is stored by the bot.

During the `/verify` verification process, the bot utilizes the Roblox OAuth 2.0 flow to link your profiles.

When using `/playerinfo`, the bot temporarily accesses the requested player's datastore data within the Bloxware: Roblox Microgames game in order to display it.
This data is fetched in real time and is never stored by the bot.

When you purchase a donation developer product, a real time message is sent to the bot containing the Roblox account ID along with the amount donated.
If you have a registered account with the bot, the bot will add the donated amount to your total stored donation amount.

When you join a server that uses this application, we use the member join event exposed by Discord to send members an onboarding welcome message.
None of the data associated with this event is stored directly.

The bot maintains server-side logs for diagnostic purposes. Logs are rotated weekly and older logs are deleted automatically.

### Role management

The bot reads which roles you currently hold in order to determine which of its own managed roles you should have. It will add or remove:

- The **verified role**, based on whether you currently have a linked Roblox account
- **Donor roles**, based on your stored donation total. These are exclusive, so you hold at most one at a time and reaching a higher threshold replaces the previous one
- **Notification roles**, based only on your own choices made via `/roles` or an opt-in panel

The bot only ever adds or removes roles that a server administrator has explicitly configured for these purposes. It will never modify any other role you hold. Your role membership is stored by Discord, not by the bot.

### Why we collect it

Your Discord and Roblox user IDs are collected solely to link your accounts for the bot's features (e.g. `/playerinfo`). Guild settings are collected to allow server administrators to configure the bot's behavior in their server. It is also necessary for the bot to determine the Discord account of the player that purchased a donation.

Your total donations are collected to send a message in the communications Discord server which contains the amount donated and your total donations.
It also is used to provide exclusive member roles for certain donation thresholds.

### How long data is retained

Account links (Discord ID ↔ Roblox ID) and donation totals are stored indefinitely until you request deletion via `/unregister` or contact the bot owner. Guild settings are retained as long as the bot is in the server.

### Who has access

Stored data is only accessible to the bot and its owner/developers. We do not sell, share, or transmit your data to any third party.

Logs are only accessible to the bot and its owner/developers. We do not sell, share, or transmit logs to any third party.

If you would like to know exactly what data we have stored about you, you may request it by contacting the bot owner via Discord. Any such information will only be shared directly with the requesting user and with no one else.

### Third-party services

The bot communicates with:
- **Roblox APIs** (`OAuth 2.0`, `apis.roblox.com`) to fetch profile and datastore data. Requests are subject to [Roblox's Privacy Policy](https://en.help.roblox.com/hc/en-us/articles/115004630823).
- **Discord's API**, subject to [Discord's Privacy Policy](https://discord.com/privacy).

### Your rights

You can view everything we have stored about you at any time using the `/profile` command, which is only ever visible to you.

You can request deletion of your stored data at any time by using the `/unregister` command, which will permanently remove your Discord and Roblox ID link from our database along with any additional metadata (e.g. donation totals). Any roles the bot granted you on the basis of that data are removed at the same time.

### Contact

If you have questions or want to manually request data deletion, contact the bot owner via Discord.

---

## Terms of Service

_Last updated: September 6th, 2026_

### Foreword
All mentions of "bot owner" refer to the Roblox group "Generic Incremental Group". For any inquiries, contact the bot developer directly via Discord at hattapper.

All mentions of "bot" and "application" refer to the Discord Application under the handle `Bloxware Bot#1610`

### 1. Acceptance
By using the Bloxware Discord Bot, you agree to these Terms of Service. If you do not agree, do not use the bot.

### 2. Eligibility
Use of the bot is restricted to members of the Bloxware: Roblox Microgames Discord server. The bot is not a public service and may not be added to other servers.

### 3. Acceptable Use
You agree not to:
- Abuse or spam bot commands
- Attempt to exploit, manipulate, or break the bot's functionality
- Submit false or misleading bug reports
- Register a Roblox account that is not your own
- Attempt to obtain any role the bot manages by means other than the bot's own commands
- Use the bot in any way that violates Discord's Terms of Service or Roblox's Terms of Use

### 4. Account Linking
By using `/verify`, you confirm that the Roblox account you are linking belongs to you. Linking an account that is not yours is a violation of these terms and may result in removal from the service.

### 5. Donations
Donation data processed by the bot reflects purchases made through the in-game donation board in Bloxware: Roblox Microgames. All purchases are final and subject to Roblox's own payment and refund policies. The bot owner is not responsible for failed or missing donation records caused by issues outside the bot's control.

Roles awarded for reaching a donation threshold are a courtesy and not a purchased good. The bot owner reserves the right to change or remove donation thresholds and their associated roles at any time.

### 6. Termination
The bot owner reserves the right to restrict or revoke any user's access to the bot at any time, for any reason, without prior notice.

### 7. Availability
The bot is provided as-is with no guarantee of uptime or continued availability. The service may be modified, suspended, or discontinued at any time.

### 8. Limitation of Liability
The bot owner is not liable for any loss or damage arising from your use of the bot, including but not limited to data loss, missed donations, or service interruptions.

### 9. Changes to These Terms
These terms may be updated at any time. Continued use of the bot after changes are posted constitutes acceptance of the revised terms.

### Contact
For questions regarding these terms, contact the bot developer via Discord at hattapper.
