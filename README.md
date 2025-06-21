# steam-followed-games-enhancer
Tampermonkey script for Steam Followed Games: Price, Discount, History &amp; Sorting.

# Steam Followed Games Enhancer

Enhance your Steam Followed Games page with real-time pricing info, discount insights, and historical lows from Steam. This script adds powerful overlays and tools to your Steam experience for game tracking and decision-making.

## 🔧 Features
- 🏷️ Displays Steam current price, discount %, and final price
- 🕰️ Shows Steam's all-time historical low (via isthereanydeal.com)
- 📊 Sort your followed games by price, discount %, and release date
- 📉 Calculates total discounted value of all games on sale
- ✅ Runs directly in your browser using Tampermonkey

## 🚀 Installation

1. Install the [Tampermonkey extension](https://tampermonkey.net/)
2. [Click here to install the userscript](<RAW_SCRIPT_URL>) *(replace with raw GitHub script link)*
3. Visit your Steam followed games page: `https://steamcommunity.com/id/YOUR_ID/followedgames/`
4. Click the **📊 Load Game Info** button at the top left
5. Watch your games get enhanced with info

## 📂 How It Works

- Uses Steam's public API to fetch pricing
- Pulls historical low prices via isthereanydeal.com game history
- Automatically highlights discounted games with colored borders:
  - 🟧 Orange if discounted
  - 🟩 Green if not discounted

## 🛠️ Developer Notes

- Uses a 10-game batch system with a delay to avoid rate-limiting
- Fully client-side and lightweight
- Can be extended to show GG.deals, SteamDB tags, etc.

## 📜 License

MIT — free to use, modify, or distribute.

---
