---
description: Convert between tokens and currencies.
---

# /calculate

Calculate the value of one token in another token or USD.

## Usage

`/calculate <value> <from> <to>`

| Option  | Required | Description                                            |
| ------- | :------: | ------------------------------------------------------ |
| `value` |    x     | The amount to convert                                  |
| `from`  |    x     | Source currency (token name, address, or "USD")        |
| `to`    |    x     | Target currency (token name, address, or "USD")        |

## Example

`/calculate 100 SOL USD` — converts 100 SOL to its USD value

<figure><img src="../.gitbook/assets/placeholder-cmd-calculate.png" alt=""><figcaption><p>/calculate command converting between tokens</p></figcaption></figure>

The response includes a "Buy on Jup.ag" button for quick access to swap on Jupiter.
