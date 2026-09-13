# Privacy Policy for Support Ticket Bot
**Last Updated:** September 13, 2026

## 1. Information We Collect
Our bot processes and stores minimal data strictly required to provide Support Ticket functionality within your Discord server:
* **User Identifiers:** Discord User IDs and Usernames (to identify ticket openers and log action history).
* **Server & Channel Data:** Server IDs, Channel IDs, and Category IDs (to save system configurations).
* **Ticket Communications:** Chat messages, timestamps, attached file URLs, and interaction metadata sent within active ticket channels (collected only for ticket transcripts).

## 2. How We Use Information
The collected data is used exclusively for:
* Managing permission overwrites to create and isolate ticket channels.
* Generating text-based conversation logs (Transcripts) sent to the server's designated logging channel when a ticket is closed.
* Ensuring administrative features and system settings function correctly.

## 3. Data Storage & Retention
* **In-Memory Storage:** Active settings (e.g., staff roles, logging channels, panel configurations) are stored in volatile application memory (Map objects).
* **Transcript Logs:** Chat history is processed upon closing a ticket and posted directly to your designated transcript channel in Discord. We do not host or store your chat logs on external server databases.
* **Deletion:** Closing a ticket permanently deletes the channel and its temporary data from the active session.

## 4. Data Sharing & Third Parties
We do not sell, trade, or share your data with third parties. All processing occurs through official Discord APIs and within your server environment.

## 5. User Rights
Users can request the deletion of their ticket history by contacting server administrators to remove transcript logs from the designated logging channel.

## 6. Contact Information
If you have any questions or requests regarding this Privacy Policy, please contact the bot developer directly via Discord:
* **Developer:** `@real_mr.arm`
