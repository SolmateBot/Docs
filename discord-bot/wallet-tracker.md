---
description: Track Solana wallets in real-time and get notifications for every transaction.
---

# Wallet Tracker

The wallet tracker is Solmate's most powerful feature. Track any Solana wallet and get instant Discord notifications for swaps, transfers, token creation, burns, limit orders, and more.

<figure><img src="../.gitbook/assets/placeholder-tracker-notification.png" alt=""><figcaption><p>A swap notification from the wallet tracker</p></figcaption></figure>

## Adding a Tracker

### Via Discord

1. Type `/tracker add` in any channel
2. Enter the **wallet address** (or a `.sol` domain)
3. Select the **channel** where notifications should be sent
4. Optionally add a **nametag** (a friendly name for the wallet)
5. Optionally add **labels** (comma-separated tags to organize wallets)
6. Press Enter

<figure><img src="../.gitbook/assets/placeholder-tracker-add-command.png" alt=""><figcaption><p>Adding a wallet tracker with /tracker add</p></figcaption></figure>

### Via Web Dashboard

You can also add trackers from the dashboard — including bulk adding multiple wallets at once. See [Managing Trackers](../web-dashboard/managing-trackers.md).

{% hint style="info" %}
**Activation time:** New trackers may take up to 10 minutes to start receiving transactions.
{% endhint %}

## What Gets Tracked

Each notification includes details about the transaction, along with quick-action buttons to view it on explorers and trading tools.

| Transaction Type     | Description                                      |
| -------------------- | ------------------------------------------------ |
| **Swaps**            | Token buys and sells (Jupiter, Raydium, etc.)    |
| **Transfers**        | SOL and token transfers between wallets          |
| **Token Creation**   | When the wallet creates a new token              |
| **Burns**            | When tokens are burned                           |
| **Limit Orders**     | Creation, execution, and cancellation             |
| **Fee Claims**       | Pump.fun fee claims                              |

<figure><img src="../.gitbook/assets/placeholder-tracker-swap.png" alt=""><figcaption><p>Swap notification with token details and action buttons</p></figcaption></figure>

## Managing Trackers

### List all trackers

* **Discord:** `/tracker list` — shows all tracked wallets with pagination
* **Dashboard:** Go to [solmatebot.com/manage](https://solmatebot.com/manage) > select your server > **Trackers** tab

<figure><img src="../.gitbook/assets/placeholder-tracker-list.png" alt=""><figcaption><p>Tracker list on the web dashboard</p></figcaption></figure>

### Pause & Resume

You can temporarily pause trackers without deleting them:

* **Discord:** `/tracker pause` and `/tracker resume` — pause/resume all or a specific tracker by index
* **Dashboard:** Use the pause/resume buttons next to each tracker, or select multiple and use bulk actions

### Remove a tracker

* **Discord:** `/tracker remove` and enter the wallet address
* **Dashboard:** Click the delete button next to the tracker, or select multiple and bulk delete

## Minimum Transaction Value

Filter out spam and dust transactions by setting a minimum USD value. Only transactions above this amount will trigger notifications.

Set this on the dashboard under **Settings** > **Wallet Tracker Settings** > **Minimum USD Value**.

<figure><img src="../.gitbook/assets/placeholder-tracker-min-value.png" alt=""><figcaption><p>Setting a minimum transaction value</p></figcaption></figure>

## Notification Buttons

Each tracker notification includes quick-action buttons. You can customize which buttons appear and their order on the dashboard under **Settings** > **Button Configuration**.

Available buttons include links to:

* **Explorers:** Solscan, Solana.fm, Solana Explorer
* **Trading bots:** Trojan, Bonkbot, BananaGun, BullX, and more
* **Token viewers:** Birdeye, DexScreener, Photon, GMGN, Axiom
* **Utilities:** RugCheck, PumpFun, Jupiter

<figure><img src="../.gitbook/assets/placeholder-tracker-buttons.png" alt=""><figcaption><p>Customizable notification buttons</p></figcaption></figure>

## Display Options

On the dashboard under **Settings**, you can toggle:

* **Show contract address** — display the token's contract in notifications
* **Show transaction summary** — include a summary line
* **Anonymize addresses** — hide full addresses in notifications
* **Show market cap** — display token market cap
* **Show memo field** — show transaction memos

## Tracker Limits

| Plan      | Wallet Trackers |
| --------- | --------------- |
| Free      | 5               |
| Plus      | 50              |
| Pro       | 150             |
| Community | 300             |

{% hint style="info" %}
Need more? Check out [Premium Plans](../getting-started/premium-plans.md) or request a custom plan.
{% endhint %}
