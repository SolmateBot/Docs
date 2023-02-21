---
description: How to verify your wallet with Solmate?
---

# How to verify your wallet

Solmate offers holder roles and wallet verification, you can see how to set it up here:

{% content-ref url="../commands/panel.md" %}
[panel.md](../commands/panel.md)
{% endcontent-ref %}

## Add a wallet to your profile

You can add a wallet to your profile with /profile addwallet.

* type /profile addwallet
* add the wallet public key in the "wallet" option. The following will pop up:

![](<../.gitbook/assets/image (14) (1).png>)

* Click the button in the message, you'll be brought to this site:
*

    <figure><img src="../.gitbook/assets/image (36).png" alt=""><figcaption></figcaption></figure>

If the domain does not include spruijtstudios.com or solmatebot.com it's fake and you should immediately contact Solmate staff.

{% hint style="info" %}
**Supported Wallets:** We support verification with the following wallets: Phantom, Solflare and Slope, contact Solmate staff to verify if you don't have one of these.
{% endhint %}

* Click the "Verify" button on the site, you'll be prompted to log in with your wallet and sign a message. This message will NOT TRIGGER any blockchain transaction or cost a fee.

<figure><img src="../.gitbook/assets/image (13) (2).png" alt=""><figcaption></figcaption></figure>

* approve the message and you're verified, make sure the button on the site says verified.

you can check if you are verified with /profile view

![](<../.gitbook/assets/image (6) (1).png>)

if the emoji in front of your wallet is green you're verified, if red it's unverified.

## Verify added wallet

You can verify wallets you have added before but are not verified yet.

* type /profile verifywallet and enter your wallets public key in the "wallet" option
* click enter
* follow the same steps as verification above

## Remove and view wallets

You can remove and view wallets with /profile removewallet and /profile view
