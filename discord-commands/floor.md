---
description: Get the floor price of an NFT collection with a visual preview.
---

# /floor

Get the current floor price of an NFT collection, with an image preview of the cheapest listed NFTs.

## Usage

`/floor <collection> [data] [size]`

| Option       | Required | Description                                        |
| ------------ | :------: | -------------------------------------------------- |
| `collection` |    x     | Collection name, symbol, or Magic Eden link        |
| `data`       |          | `normal` or `all` — how much data to show          |
| `size`       |          | `small` or `big` — size of the NFT preview image   |

## What it shows

* Floor price in SOL
* Number of listed NFTs
* Preview image of the floor NFT
* NFT details: price, ID, owner, mint address
* Interactive left/right buttons to browse floor listings

<figure><img src="../.gitbook/assets/placeholder-cmd-floor.png" alt=""><figcaption><p>/floor command with NFT preview and browse buttons</p></figcaption></figure>

{% hint style="info" %}
Use the arrow buttons to scroll through floor listings and see the next cheapest NFTs.
{% endhint %}
