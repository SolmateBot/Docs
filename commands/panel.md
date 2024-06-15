---
description: >-
  With holder verification you can give your collection's holders roles, and
  connect their discord to their Solana wallet.
---

# Panel

Creating a panel

* type /panel create

![](<../.gitbook/assets/image (10) (1) (1).png>)

* You can customize the message to your likings, this is optional.
* Click enter and your panel is created.

![](<../.gitbook/assets/image (7) (1) (1).png>)

![](<../.gitbook/assets/image (13) (1).png>)

* Your panel is created! you can add roles with /panel actions addac.

## Adding roles

You can add roles so users get a role when verifying a wallet (with a certain nft)

### Holder roles

You can add roles so a user will get a role if they own a nft from a certain collection.

We are supporting staked nfts and roles for traits, rarity and amount of nfts soon.

* start by typing /panel actions add.
* Select a role to give.
* click the option "collection"
* Enter the name of the collection or the collection's symbol

<figure><img src="../.gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**Collection Symbol:** You can see the symbol in the link on magic eden for example: [https://magiceden.io/marketplace/iconic\_ape\_club](https://magiceden.io/marketplace/iconic\_ape\_club). the symbol is "iconic\_ape_\__club"
{% endhint %}

* Click enter and the action is created.

### Verification roles

You can add a role users will get when they verify their wallet. If they have a verified wallet they will automatically be given the role.

* start by typing /panel actions add
* select a role to give

{% hint style="info" %}
**Hint:** You can also add roles for users without a Solana wallet, make the option "walletrequired" false
{% endhint %}

![](<../.gitbook/assets/image (1) (1) (1) (1) (1).png>)

* Click enter and you're done.

All users with a verified wallet will get this role.



## Removing actions

You can remove reactions so users will no longer get a role when verifing a wallet.

* type /panel actions remove
* select the role of the action you want to remove
* If the role is connected to a collection enter the collection name or symbol in the "collection" argument.
* Click enter

{% hint style="info" %}
**Hint:** You can see if a role is tied to a collection by running the command /panel actions list
{% endhint %}
