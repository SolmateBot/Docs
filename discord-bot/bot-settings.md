---
description: Customize Solmate's behavior in your server.
---

# Bot Settings

Solmate has several server-wide settings you can configure via Discord commands or the web dashboard.

## Bot Nickname (Price Ticker)

Make Solmate's Discord nickname display the live Solana price. The nickname updates automatically and shows the current price with a trend indicator.

**Format:** `$XX.XX ▲X.X%` or `$XX.XX ▼X.X%`

<figure><img src="../.gitbook/assets/placeholder-nickname-price.png" alt=""><figcaption><p>Bot nickname showing live SOL price</p></figcaption></figure>

{% hint style="info" %}
Solmate needs the **Change Nickname** permission for this to work.
{% endhint %}

## Ticker Roles

Ticker roles automatically change color based on whether the Solana price is going up or down over the last 24 hours:

* **ticker\_green** — assigned when price is up
* **ticker\_red** — assigned when price is down

These roles are created automatically. You can use them to make the bot's name appear green or red in the member list and chat.

{% hint style="info" %}
Solmate needs the **Manage Roles** permission, and the ticker roles must be **below** Solmate's role in the role hierarchy.
{% endhint %}

## Explorer Selection

Choose which blockchain explorer is used in links throughout Solmate's responses:

* **Solscan** (default)
* **Solana FM**
* **Solana Explorer**

## Token Viewer Selection

Choose which token viewer is linked in token-related notifications:

* **Axiom** (default)
* Birdeye, DexScreener, Photon, GMGN, and more

## Configuring Settings

Most settings can be managed from the web dashboard:

1. Go to [solmatebot.com/manage](https://solmatebot.com/manage)
2. Select your server
3. Click the **Settings** tab

<figure><img src="../.gitbook/assets/placeholder-settings-page.png" alt=""><figcaption><p>The Settings page on the dashboard</p></figcaption></figure>

See [Tracker Settings](../web-dashboard/tracker-settings.md) for detailed tracker-specific settings.
