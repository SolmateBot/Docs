---
description: >-
  With holder verification you can give your collection's holders roles, and
  connect their discord to their Solana wallet.
---

# Verification

Creating a panel

* type /verification create
*

    <figure><img src="../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>
* You can customize the message to your likings, this is optional.
* Click enter and your panel is created.
*

    <figure><img src="../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

![](<../.gitbook/assets/image (13) (1).png>)

* Your panel is created! you can add roles with /verification actions addcollection or /verification actions addtoken.

## Adding roles

You can add roles so users get a role when verifying a wallet (with a certain nft)

## Holder roles

You can add roles so a user will get a role if they own a nft from a certain collection.

We are supporting staked nfts and roles for traits, rarity and amount of nfts soon.

{% tabs %}
{% tab title="Tokens" %}


* start by typing /verification actions addtoken.
* Select a role to give.
* click the option "token"
* the amount field is optional, but is advised if you want to set a specific amount
* Enter the name of the token or contract address
*

    <figure><img src="../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>
* Click enter and the action is created.
{% endtab %}

{% tab title="NFT Collections" %}


* start by typing /verification actions addcollection.
* Select a role to give.
* click the option "collection"
* Enter the name of the collection or the collection's symbol

<figure><img src="../.gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**Collection Symbol:** You can see the symbol in the link on magic eden for example: [https://magiceden.io/marketplace/iconic\_ape\_club](https://magiceden.io/marketplace/iconic\_ape\_club). the symbol is "iconic\_ape_\__club"
{% endhint %}

* Click enter and the action is created.
{% endtab %}
{% endtabs %}

## Removing actions

You can remove reactions so users will no longer get a role when verifing a wallet.

* type /verifications actions remove
* select the role of the action you want to remove
* If the role is connected to a collection enter the collection name or symbol in the "collection" argument.
* Click enter

{% hint style="info" %}
**Hint:** You can see if a role is tied to a collection by running the command /verification actions list
{% endhint %}
