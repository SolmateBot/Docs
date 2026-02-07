---
description: Get the current price of Solana or any SPL token.
---

# /price

Get live price information for Solana or a specific SPL token.

## Usage

`/price [spltoken]`

| Option     | Required | Description                                        |
| ---------- | :------: | -------------------------------------------------- |
| `spltoken` |          | Token name or address. Leave blank for SOL price.  |

## What it shows

* Current price (USD)
* 24-hour price change (%)
* All-time high (ATH)
* Trading volume
* Price changes over 7d, 14d, 30d, 60d, 200d, and 1 year

<figure><img src="../.gitbook/assets/placeholder-cmd-price.png" alt=""><figcaption><p>/price command showing SOL price data</p></figcaption></figure>

{% hint style="info" %}
If no token is specified, the command returns the current Solana (SOL) price.
{% endhint %}

The response includes a "Buy on Jup.ag" button to quickly swap to the token on Jupiter.
