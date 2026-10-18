# Privacy Policy for 9Arm Support Bot
**Last Updated:** October 18, 2026

This Privacy Policy explains what data 9Arm Support Bot ("the Bot", "we", "us") collects, why, where it is stored, and what choices you have. By adding the Bot to a Discord server or interacting with it, you agree to this policy.

## 1. Information We Collect
The Bot only processes the data needed to run the features that server administrators enable.

* **User Identifiers:** Discord User IDs and usernames/tags, used for ticket openers and closers, giveaway hosts, participants and winners, invite tracking, auto-role logs, verification sessions, and moderation logs.
* **Server Data:** Server (Guild) IDs, Channel IDs, Role IDs, Message IDs, and the settings administrators choose for each feature (for example AutoMod log channel, Auto-Role role, Starboard emoji and threshold, Sticky Message title/content/color, Verification panel text and image URL, Ticket panel settings).
* **Invite & Giveaway Data:** For invite-based giveaways and the invite leaderboard, the Bot stores who invited a member (inviter ID), the member's ID, when they joined, whether they have left, and any manual invite bonus assigned by administrators. Giveaway entries store participant and winner User IDs.
* **Message Content (processed):**
  * Messages are read in real time for AutoMod keyword filtering, Anti-Scam detection, Auto-Reaction triggers, Sticky Message re-posting, Starboard counting, and prefix commands.
  * The Bot does **not** keep a general archive of server messages. Message content is processed in memory and discarded, except where described in this section.
  * **Anti-Scam:** Image attachments in messages may be scanned with OCR to detect scam text. If a message is flagged, the Bot may copy the flagged message text and image(s) to the server's configured log channel as evidence for moderators, then delete the original and apply the configured action (kick, ban, or timeout).
  * **Starboard:** When a message reaches the configured threshold, its text, author name/avatar, and first image attachment are reposted to the Starboard channel. The Bot stores only the original and Starboard Message IDs.
* **Ticket Communications:** Messages, timestamps, author names and IDs, and attachment links inside a ticket channel, collected only to generate the transcript when the ticket is closed.
* **Verification (CAPTCHA):** A short-lived verification session (User ID, the generated code, number of attempts) is kept in the Bot's memory only until it expires or is completed. It is not saved to the database.
* **Direct Messages:** If you send a direct message to the Bot or interact with a DM-based feature, the Bot may receive and process that message to respond or relay it as that feature is designed.
* **Diagnostic Data:** When an error occurs, the Bot may send an error report (error message and limited request details such as IDs) to a private developer webhook for troubleshooting.

We do not intentionally collect email addresses, passwords, payment information, or other sensitive personal data. Please do not share such data in tickets or with the Bot.

## 2. How We Use Information
We use the collected data only to:
* Create and manage private ticket channels, and generate text transcripts sent to the server's designated transcript channel when a ticket is closed.
* Run AutoMod, Anti-Scam, Auto-Reactions, and send moderation/audit log alerts.
* Manage Sticky Messages, Starboard posts, Giveaways (including invite and role requirements), the invite leaderboard, Auto-Role assignment, and CAPTCHA verification.
* Display game statistics channels (public Roblox game and group information).
* Save feature settings so they keep working across restarts and updates.
* Monitor, debug, and secure the Bot.

We do not use your data for advertising, profiling, or training machine-learning models.

## 3. Data Storage & Retention
* **Database:** Feature settings, giveaway records, invite tracking records, invite bonuses, Starboard post references, and verification settings are stored in a MongoDB Atlas cloud database that only the Bot developer can access.
* **Local Files:** Some settings (for example ticket settings, Sticky Message configuration, AutoMod configuration, and game-stat settings) are stored in JSON files on the Bot's hosting server.
* **Ticket Transcripts:** Transcripts are posted to your server's transcript channel in Discord and are not otherwise kept by the Bot. Those copies are controlled by your server's administrators.
* **Retention:** Configuration data is kept until an administrator disables the related feature (for example turning off AutoMod or removing a Sticky Message) or asks us to delete it. Giveaway and invite records are kept for as long as needed to run giveaways and leaderboards. Removing the Bot from a server does not automatically erase its stored settings, so server owners who want everything removed should contact us (see Section 7).
* **Security:** Access to the database, hosting server, and admin dashboard is restricted to the developer and protected by credentials. No system is completely secure, and we cannot guarantee absolute security.

## 4. Data Sharing & Third Parties
We do not sell, rent, or trade your data. Data is shared only as needed to operate the Bot:
* **Discord:** All Bot activity runs through Discord's official API, and your use of Discord is governed by [Discord's Privacy Policy](https://discord.com/privacy).
* **MongoDB Atlas:** Our database provider, which stores the configuration and records described above.
* **Hosting Provider:** The platform that runs the Bot and its local files.
* **OCR.space:** When Anti-Scam image scanning is enabled, image links from messages may be sent to the OCR.space service to read text from the image. See [OCR.space's privacy policy](https://ocr.space/privacypolicy).
* **Roblox:** The game-stat feature requests public game and group information from Roblox. No Discord user data is sent.
* **Legal:** We may disclose information if required by law or to protect the rights and safety of users, servers, or the Bot.

## 5. Your Rights & Choices
* **Access / Deletion:** You may ask what data related to your Discord User ID the Bot stores (such as giveaway entries or invite records) and request that it be deleted.
* **Ticket Transcripts:** Transcripts sit in your server's channels, so ask that server's administrators to remove them.
* **Server Owners:** You may disable any feature at any time using the Bot's slash commands, or ask us to delete all data stored for your server.
* **Objection:** You can stop the Bot from processing your messages by leaving the server, or ask administrators to disable the relevant feature.

We will respond to verified requests within a reasonable time. Some records may be kept where needed for security, abuse prevention, or legal reasons.

## 6. Children's Privacy
The Bot is intended for users who meet Discord's minimum age requirement (13 or older, or higher where local law requires). We do not knowingly collect data from children below that age. If you believe we have, contact us and we will delete it.

## 7. Contact Information
For questions or requests about this Privacy Policy, contact the Bot developer on Discord:
* **Developer:** `@real_mr.arm`

## 8. Changes to This Policy
We may update this policy as the Bot's features change. The "Last Updated" date above shows the latest version. Continued use of the Bot after changes means you accept the updated policy.
