---
description: How Solmate keeps you and your server safe and secure.
---

# Privacy and Safety

## Privacy

{% hint style="danger" %}
**Important:** Solmate will **never** ask for your wallet's private key, seed phrase, or passphrase. If anyone claims to be Solmate staff and asks for these, it is a scam. Contact our staff immediately in the support server.
{% endhint %}

### What data we store

We only store the data necessary for Solmate to function:

* Discord user ID and username (for linking your account)
* Wallet addresses you voluntarily connect (for verification and tracking)
* Server configuration settings (for bot features)

We do **not** collect or store:

* Private keys or seed phrases
* Transaction history beyond what's needed for active features
* Personal information beyond your Discord profile

### Data visibility

All data stored for a user is visible to the user themselves. For example, you can see all your connected wallets and notification settings on the [account page](https://solmatebot.com/account).

### Data deletion

If you remove your data (disconnect a wallet, delete a tracker, etc.), it is permanently deleted from our systems.

## Safety

### Bot access

Only the developer (@spruijt) has access to the bot's systems and infrastructure. No third parties have access.

### Database security

* The database is encrypted and only accessible by the bot service and the developer
* We only store what's needed for the bot to work
* Database backups are created regularly
* Deleted data is permanently removed

### Verification safety

* Wallet verification only requires a **signature** — no transaction or funds transfer
* The verification page is only hosted on `solmatebot.com` and `spruijtstudios.com`
* If you see any other domain, it is fake — do NOT connect your wallet

### Permissions

Solmate requests Discord permissions for specific features:

| Permission      | Used for                                          |
| --------------- | ------------------------------------------------- |
| Manage Roles    | Assigning holder roles and ticker roles           |
| Manage Channels | Creating and updating stat counter channels       |
| Send Messages   | Responding to commands and sending notifications  |
| Embed Links     | Displaying rich embed messages                    |
| Attach Files    | Sending export and snapshot files                 |

Not all permissions are required for the bot to function, but some features won't work without their respective permissions.
