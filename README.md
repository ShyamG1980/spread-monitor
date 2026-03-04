# Spread Monitor PWA

A personal trade spread tracking app. Monitors client spreads across uploads and flags any trade where the spread is lower than the previous trade on a newer date.

## How to deploy (free, 5 minutes)

1. Go to [github.com](https://github.com) and sign in (or create a free account)
2. Click **+** → **New repository**
3. Name it `spread-monitor`, set to **Public**, click **Create repository**
4. Upload all files in this folder (index.html, manifest.json, sw.js, and the icons/ folder)
5. Go to **Settings** → **Pages** → Source: **Deploy from a branch** → Branch: **main** → **Save**
6. After ~60 seconds your app is live at: `https://YOUR-USERNAME.github.io/spread-monitor`

## Install on iPhone
1. Open the URL above in **Safari**
2. Tap the **Share** button (box with arrow)
3. Tap **Add to Home Screen**
4. Tap **Add** — done!

## Install on Android
1. Open the URL in **Chrome**
2. Tap the **three dots** menu
3. Tap **Add to Home screen**
4. Tap **Add** — done!

## Features
- Upload CSV or Excel trade files daily
- Automatically flags trades where spread is lower than the last known spread for that client + currency pair, on a newer trade date
- Remembers all history across sessions (browser localStorage)
- Works offline after first load
- Export flagged trades to Excel
