---
description: Verify wallet ownership by providing a signed message.
---

# /verifysignature

Verify that you own a wallet by submitting a signature, message, and public key. This is an alternative verification method for users who prefer not to connect their wallet through the website.

## Usage

`/verifysignature`

No options — a popup form will appear.

## How it works

1. Type `/verifysignature` and press Enter
2. A popup will appear with three fields:
   * **Signature** — the signed message
   * **Message** — the original message that was signed
   * **Public Key** — your wallet address
3. Fill in the fields and submit

<figure><img src="../.gitbook/assets/placeholder-cmd-verifysignature-popup.png" alt=""><figcaption><p>The verification signature popup</p></figcaption></figure>

If the signature is valid, you'll see a confirmation message.

<figure><img src="../.gitbook/assets/placeholder-cmd-verifysignature-success.png" alt=""><figcaption><p>Successful signature verification</p></figcaption></figure>
