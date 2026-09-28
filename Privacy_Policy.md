# Privacy Policy for 9Arm Support Bot
**Last Updated:** September 28, 2026

## 1. Information We Collect
Our bot processes and stores minimal data strictly required to provide server automation, moderation, and interaction features within your Discord server:
* **User Identifiers:** Discord User IDs and Usernames (to track ticket openers, giveaway participants, message actions, auto-role assignees, and logging history).
* **Server & Channel Data:** Server IDs, Channel IDs, Role IDs, and Category IDs (to save feature configurations across systems).
* **Message Content & Metadata:** 
  * Processed temporarily for AutoMod keyword filtering, Anti-Scam verification, and Auto-Reaction detection.
  * Stored temporarily (Message IDs and Channel IDs) to facilitate auto-updating Sticky Messages, Starboard tracking, and deleting expired messages.
* **Ticket Communications:** Chat messages, timestamps, attached file URLs, and interaction metadata sent within active ticket channels (collected only for generating ticket transcripts).

## 2. How We Use Information
The collected data is used exclusively for:
* Managing permission overwrites to create and isolate ticket channels, and generating text transcripts sent to designated logging channels upon ticket closure.
* Executing automated moderation (AutoMod), auto-reactions, anti-scam checks, and sending audit log alerts.
* Managing Sticky Messages, Starboard post tracking, Giveaway entries, and Auto-Role assignments.
* Ensuring system configurations function correctly across restarting or updating sessions.

## 3. Data Storage & Retention
* **Local Configuration Files:** Active feature settings (e.g., AutoMod rules, Sticky Message content, Auto-Role rules, Starboard channels) are saved securely in JSON configuration files (`.json`) on the hosting server.
* **Transcript Logs:** Chat history within tickets is processed upon closing a ticket and posted directly to your server's designated transcript channel in Discord.
* **Data Deletion:** When a feature is disabled via slash commands (e.g., disabling AutoMod or Sticky Messages) or when the bot is removed from a server, associated configuration data is deleted from our database files.

## 4. Data Sharing & Third Parties
We do not sell, trade, or share your data with any third parties. All processing occurs strictly through official Discord APIs and within your server environment.

## 5. User Rights
Users can request the deletion of their personal configuration data or ticket history by contacting server administrators to remove transcript logs, or by reaching out directly to the bot developer.

## 6. Contact Information
If you have any questions or requests regarding this Privacy Policy, please contact the bot developer directly via Discord:
* **Developer:** `@real_mr.arm`
