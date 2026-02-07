---
description: Track profit and loss for your watched wallets over 7 and 30 days.
---

# PNL Tracking & Leaderboard

Solmate tracks the realized profit and loss (PNL) for all your tracked wallets, giving you insight into which wallets are performing best.

## Viewing Wallet PNL

When you look up a wallet with `/address`, the response includes the **7-day PNL** alongside the wallet balance and holdings.

<figure><img src="../.gitbook/assets/placeholder-pnl-address.png" alt=""><figcaption><p>Wallet info showing 7-day PNL</p></figcaption></figure>

## PNL Leaderboard

Compare the performance of all your tracked wallets with the leaderboard command.

1. Type `/tracker leaderboard`
2. Select the **type**: 7-day PNL or 30-day PNL
3. Select the **sort order**:
   * Highest % first
   * Lowest % first
   * Highest $ first
   * Lowest $ first
4. Press Enter

The leaderboard shows your top 10 tracked wallets ranked by performance.

<figure><img src="../.gitbook/assets/placeholder-pnl-leaderboard.png" alt=""><figcaption><p>PNL leaderboard showing top performing wallets</p></figcaption></figure>

## PNL Voice Counters

You can display a wallet's PNL as a live voice channel counter:

* **Wallet PNL (7 day)** — shows the 7-day PNL of a wallet
* **Wallet PNL (30 day)** — shows the 30-day PNL of a wallet

See [Server Stats](server-stats.md) for how to set up counters.
