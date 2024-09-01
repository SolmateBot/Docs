---
description: Counters are (voice) channels with stats like floor price in SOL.
---

# Stats

## Creating counters

You can create a counter with the /counter add command.

* type /counter add
* select the type of counter you want

{% hint style="info" %}
**Optional:** Make the channel appear under a certain category with the "category" option.
{% endhint %}

#### Counter type and their required options

<table><thead><tr><th width="233">Counter type</th><th width="112" data-type="checkbox">collection</th><th width="75" data-type="checkbox">price</th><th width="77" data-type="checkbox">token</th><th width="84" data-type="checkbox">token2</th><th data-type="checkbox">wallet</th><th></th></tr></thead><tbody><tr><td>Solana price to USD</td><td>false</td><td>false</td><td>false</td><td>false</td><td>false</td><td></td></tr><tr><td>Solana price change in %</td><td>false</td><td>false</td><td>false</td><td>false</td><td>false</td><td></td></tr><tr><td>Collection floor price in Solana</td><td>true</td><td>false</td><td>false</td><td>false</td><td>false</td><td></td></tr><tr><td>Collection floor price in USD</td><td>true</td><td>false</td><td>false</td><td>false</td><td>false</td><td></td></tr><tr><td>Amount of NFTs below price x</td><td>true</td><td>true</td><td>false</td><td>false</td><td>false</td><td></td></tr><tr><td>SPL token price in USD</td><td>false</td><td>false</td><td>true</td><td>false</td><td>false</td><td></td></tr><tr><td>SPL token price in another Token</td><td>false</td><td>false</td><td>true</td><td>true</td><td>false</td><td></td></tr><tr><td>Total collection volume in Solana</td><td>true</td><td>false</td><td>false</td><td>false</td><td>false</td><td></td></tr><tr><td>Total collection volume 24h in Solana</td><td>true</td><td>false</td><td>false</td><td>false</td><td>false</td><td></td></tr><tr><td>Average Price 24h</td><td>true</td><td>false</td><td>false</td><td>false</td><td>false</td><td></td></tr><tr><td>Amount listed</td><td>true</td><td>false</td><td>false</td><td>false</td><td>false</td><td></td></tr><tr><td>Listed total value in Solana</td><td>true</td><td>false</td><td>false</td><td>false</td><td>false</td><td></td></tr><tr><td>Solana TPS</td><td>false</td><td>false</td><td>false</td><td>false</td><td>false</td><td></td></tr><tr><td>Wallet balance in SOL</td><td>false</td><td>false</td><td>false</td><td>false</td><td>true</td><td></td></tr><tr><td>Wallet balance in SPL</td><td>false</td><td>false</td><td>true</td><td>false</td><td>true</td><td></td></tr><tr><td>Total wallet networth</td><td>false</td><td>false</td><td>false</td><td>false</td><td>true</td><td></td></tr></tbody></table>

{% hint style="info" %}
For the collection field: You can enter the collection link to Magic Eden, the collection's name or the symbol.
{% endhint %}

* your channel will be made and be updates \~10 seconds, if this does not happen wait \~15minutes. If it does not update make sure you have the permissions set up correctly.

{% hint style="info" %}
**Hint:** You can change the channel type to a text channel.
{% endhint %}

{% hint style="info" %}
You can add text in front of the data, for example the channel is called "◎8.79" You can change the name to "FP: ◎8.79" or "Floor: ◎8.79".

&#x20;"◎8.79 Floor" will be changed to "◎8.79". You can only add text before the ◎, $ or up & down arrows
{% endhint %}

## Delete a counter

You can delete a counter with /counter delete and click the corresponding index (see /counter list) and click enter. Make sure to also delete the (voice) channel (This should be done automatically)

## List counters

you can list counters with the /counter list command. The result will look similar to this:

<figure><img src="../.gitbook/assets/image (18) (1).png" alt=""><figcaption></figcaption></figure>
