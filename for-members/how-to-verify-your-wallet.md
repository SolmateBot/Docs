---
description: Step-by-step guide for community members to verify their wallet and get holder roles.
---

# How to Verify Your Wallet

If a Discord server uses Solmate for holder verification, you'll need to connect and verify your wallet to receive roles based on your NFT or token holdings.

## Step 1: Click the Verify button

Find the verification panel in the Discord server (usually in a dedicated channel) and click the **Verify** button.

<figure><img src="../.gitbook/assets/placeholder-member-verify-panel.png" alt=""><figcaption><p>Click the Verify button on the panel</p></figcaption></figure>

You'll be redirected to the Solmate website to complete verification.

## Step 2: Add your wallet

If this is your first time, you'll be on the wallet verification page. You have two ways to verify:

{% tabs %}
{% tab title="Option 1: Sign a Message (Recommended)" %}

1. Click **Connect Wallet**
2. Select your wallet provider (Phantom, Solflare, MetaMask, Trust Wallet, Coinbase Wallet, and 300+ more)
3. Approve the connection in your wallet
4. Click **Verify** — you'll be asked to sign a message
5. Approve the signature in your wallet

<figure><img src="../.gitbook/assets/placeholder-member-sign-message.png" alt=""><figcaption><p>Signing a verification message — this costs nothing</p></figcaption></figure>

{% hint style="info" %}
**This is free and safe.** Signing a message does NOT trigger a blockchain transaction, does NOT cost any gas, and does NOT give anyone access to your funds.
{% endhint %}

{% endtab %}

{% tab title="Option 2: Send a Transaction" %}

If you can't connect your wallet directly (e.g., you're using a hardware wallet):

1. Send a small amount of SOL (or BNB) to the address shown on the verification page
2. Copy the transaction ID/signature
3. Paste it into the input field
4. Click **Submit**

Your wallet is verified once the transaction is confirmed.

{% endtab %}
{% endtabs %}

## Step 3: Get your roles

Once verified, the bot will automatically check your holdings and assign the appropriate roles. This happens within a few seconds.

If the server has roles for:

* **NFT Collections** — you get the role if you hold an NFT from that collection
* **Tokens** — you get the role if you hold the required amount of a token
* **Traits** — you get the role if you hold an NFT with a specific trait (e.g., "Background: Gold")

## Managing Your Wallets

You can manage all your connected wallets at [solmatebot.com/account](https://solmatebot.com/account):

* View all connected wallets
* Verify wallets you haven't verified yet
* Remove wallets you no longer want connected
* Add additional wallets (both Solana and EVM)

<figure><img src="../.gitbook/assets/placeholder-member-account-page.png" alt=""><figcaption><p>Your account page with connected wallets</p></figcaption></figure>

## Supported Wallets

Solmate supports 300+ wallets through WalletConnect, including:

* **Phantom**
* **Solflare**
* **MetaMask** (for BNB/EVM)
* **Trust Wallet**
* **Coinbase Wallet**
* And many more

## Chain Support

Depending on the server's configuration, you may be able to verify with:

* **Solana** wallets (SOL, SPL tokens, NFTs)
* **BNB/EVM** wallets (BNB, ERC-20, BEP-20 tokens)

{% hint style="danger" %}
**Stay safe:** The verification page will only be on `solmatebot.com` or `spruijtstudios.com`. If you're redirected to any other domain, it's a scam. Do NOT connect your wallet and contact Solmate staff immediately.
{% endhint %}

## Re-verification

Solmate periodically re-checks your holdings. If you sell your NFTs or tokens, the associated roles may be removed automatically. If you acquire new holdings, verify again or wait for the next automatic check.

## FAQ

**Q: Will verifying cost me anything?**\
A: No. Signing a message is completely free and doesn't interact with the blockchain.

**Q: Can the bot access my funds?**\
A: No. The verification only proves you own the wallet. Solmate never has access to your private keys or funds.

**Q: I verified but didn't get my role?**\
A: Make sure you hold the required NFT/token in the wallet you verified. If the issue persists, contact the server's admins or Solmate support.

**Q: Can I verify multiple wallets?**\
A: Yes. Add and verify multiple wallets at [solmatebot.com/account](https://solmatebot.com/account). Holdings across all verified wallets are combined.
