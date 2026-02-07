---
description: Show off a random NFT from your wallet.
---

# /flex

Randomly display an NFT from your verified wallet for a collection that has holder verification set up in the server.

## Usage

`/flex`

No options required.

## How it works

1. Your wallet must be verified in the server (see [How to Verify Your Wallet](../for-members/how-to-verify-your-wallet.md))
2. The server must have at least one collection-based verification role set up
3. The bot picks a random NFT you own from one of those collections
4. It displays the NFT image with a link to view it on Magic Eden

<figure><img src="../.gitbook/assets/placeholder-cmd-flex.png" alt=""><figcaption><p>/flex showing a random NFT from your collection</p></figcaption></figure>

{% hint style="info" %}
This command only works for collections that have verification roles configured in the current server.
{% endhint %}
