# Steam Cart Parser

A simple tool that converts your Steam shopping cart into a clean, easy to read list. No installation required — just open the link below and paste your cart text.

---

## Links

| Version | Link |
|---|---|
| Basic (no API needed) | https://thewowcollector.github.io/steam-cart-parser/SteamCartParser.html |
| ITAD Version (with best prices) | https://thewowcollector.github.io/steam-cart-parser/SteamCartParserOnlineITAD.html |

Basic has a **Download Local Version** button in the top right corner if you prefer to run it offline.

---

## How to use

### Step 1 — Copy your Steam cart text

1. Open your Steam shopping cart in your browser or from the desktop app
2. Select all the text on the page (Ctrl + A) or simply click and drag
3. Copy it (Ctrl + C)

### Step 2 — Paste and parse

1. Open `SteamCartParser.html` by double-clicking it
2. Click inside the text box and paste (Ctrl + V)
3. Click **Parse Cart**

Your cart will appear as a clean numbered list showing each game, its discount, original price, and sale price — with a total at the bottom.

---

## Copying your list

### Copy as Text
Copies the list in a tab-separated format that pastes cleanly into Excel or Google Sheets.

### Copy for Discord
Copies the list formatted as a monospace code block for Discord. If your cart is too long for one message, it will automatically split into multiple parts — each with its own copy button so you can paste them one at a time.

---

## ITAD Version (Best Prices)

The ITAD version fetches the best current and best ever prices for each game across all stores using the [IsThereAnyDeal](https://isthereanydeal.com) database.

To use it you need a free API key:
1. Create a free account at **isthereanydeal.com**
2. Go to **Settings → API** to get your key
3. Paste it into the API key field at the top of the page — it saves automatically

### What the columns mean
- **Best Current** — the lowest price available right now across all stores
- **Best Ever** — the lowest price the game has ever been anywhere

If Best Ever is much lower than the current sale price, it may be worth waiting for a better deal.

---

## Notes

- Works in any modern browser (Chrome, Firefox, Edge)
- Your cart text is never sent anywhere — everything runs locally in your browser
- The local version requires no internet connection or API key
