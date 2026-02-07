---
description: Create auto-updating embed messages with custom data.
---

# Static Messages

Static messages are custom embed messages posted by Solmate that can display dynamic data like wallet balances, token prices, and more. They stay pinned in a channel and update automatically.

<figure><img src="../.gitbook/assets/placeholder-static-example.png" alt=""><figcaption><p>A static message displaying wallet information</p></figcaption></figure>

## Adding a Static Message

1. Type `/static add`
2. Select the **channel** where the message should be posted
3. Customize the embed fields:
   * Title, description, color
   * Image, thumbnail
   * Footer text
4. Use **variables** in your text to display dynamic data
5. Press Enter

<figure><img src="../.gitbook/assets/placeholder-static-add.png" alt=""><figcaption><p>Creating a static message with /static add</p></figcaption></figure>

## Viewing Static Messages

`/static list` — shows all configured static messages with their index numbers

<figure><img src="../.gitbook/assets/placeholder-static-list.png" alt=""><figcaption><p>List of static messages</p></figcaption></figure>

## Removing a Static Message

1. Type `/static remove`
2. Select the index of the message to remove (check `/static list` for the index)
3. Press Enter

## Static Variable Limits

| Plan      | Static Variables |
| --------- | ---------------- |
| Free      | 1                |
| Plus      | 10               |
| Pro       | 10               |
| Community | 10               |
