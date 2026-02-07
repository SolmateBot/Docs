---
description: Look up any SPL token to see its price, supply, market cap, and security info.
---

# /token

Get detailed information about an SPL token, including a security analysis.

## Usage

`/token <token>`

| Option  | Required | Description                              |
| ------- | :------: | ---------------------------------------- |
| `token` |    x     | Token name or contract address           |

## What it shows

* Token name and contract address
* Current price (USD)
* Decimals and total supply
* Market cap
* **Security analysis:**
  * Top 10 holder concentration (warns if >30%)
  * Liquidity status and USD value
  * Mint authority status (renounced or not)
  * Freeze authority status (renounced or not)

<figure><img src="../.gitbook/assets/placeholder-cmd-token.png" alt=""><figcaption><p>/token command showing token info with security details</p></figcaption></figure>

The response includes a button to view the token on your configured token viewer (Axiom by default).
