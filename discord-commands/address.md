---
description: Look up any Solana wallet to see its balance, holdings, and PNL.
---

# /address

Get detailed information about a Solana wallet address.

## Usage

`/address <address>`

| Option    | Required | Description                          |
| --------- | :------: | ------------------------------------ |
| `address` |    x     | The Solana wallet address or .sol domain |

## What it shows

* SOL balance
* Total wallet value (USD)
* 7-day PNL (profit and loss)
* Top 10 token holdings with values
* .sol domains owned by the wallet
* Nametag (if one is set for this server)

<figure><img src="../.gitbook/assets/placeholder-cmd-address.png" alt=""><figcaption><p>/address command result</p></figcaption></figure>

{% hint style="info" %}
You can give wallets a custom name using nametags. This will display the name instead of the address. Learn more in [Nametags & Labels](../discord-bot/nametags-and-labels.md).
{% endhint %}

The response also includes a link to manage trackers for this wallet on the dashboard.
