---
description: >-
  Counters are (voice) channels with stats like floor price in SOL and USD,
  solana price & change. SPL token price (from coingecko) and amount of NFTs
  listed below x SOL
---

# Counters (floor price & more)

## Creating counters

You can create a counter with the /counter add command.

* type /counter add
* select the type of counter you want

{% tabs %}
{% tab title="Floor Price (SOL and USD)" %}
You need the option "collection" for this type.

* add the collection name or symbol in the option "collection"
{% endtab %}

{% tab title="Solana Price (and change)" %}
b
{% endtab %}

{% tab title="SPL token Price" %}
c
{% endtab %}

{% tab title="Amount of NFTs below X SOL" %}

{% endtab %}
{% endtabs %}

**Optional:** Make the channel appear under a certain category with the "category" option.

* your channel will be made and be updates \~10 seconds, if this does not happen wait \~15minutes. If it does not update make sure you have the permissions set up correctly.

{% hint style="info" %}
**Hint:** You can change the channel type to a text channel.
{% endhint %}

You can add text in front of the data, for example the channel is called "◎8.79" You can change the name to "FP: ◎8.79" or "Floor: ◎8.79".

&#x20;"◎8.79 Floor" will be changed to "◎8.79". You can only add text before the ◎, $ or up & down arrows

## Delete a counter

You can delete a counter with /counter delete and click the corresponding type and click enter. Make sure to also delete the (voice) channel

## List counters

you can list counters with the /counter list command. The result will look similar to this:

![](<../.gitbook/assets/image (11).png>)
