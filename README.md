# Wealth Builder — Phone App

A personal finance tracker that works as a real phone app.
Track paycheques, expenses, investments, and savings goals.

---

## 📱 How to Install on Your Phone

### Option A — GitHub Pages (Recommended, Free, Works on iPhone + Android)

1. Go to https://github.com and create a free account if you don't have one
2. Click **New repository** → name it `wealthbuilder` → set to **Public** → click Create
3. Click **uploading an existing file** and upload ALL 4 files:
   - `WealthBuilderApp.html`
   - `manifest.json`  
   - `sw.js`
   - `icon-192.svg`
4. Click **Commit changes**
5. Go to **Settings** → **Pages** → under Source select **main branch** → click Save
6. Wait ~60 seconds, then your app is live at:
   `https://YOUR-USERNAME.github.io/wealthbuilder/WealthBuilderApp.html`

### Install on iPhone (Safari)
1. Open the link above in Safari
2. Tap the **Share** button (box with arrow pointing up)
3. Scroll down and tap **Add to Home Screen**
4. Tap **Add** — done! It's now on your home screen like a real app

### Install on Android (Chrome)
1. Open the link in Chrome
2. Tap the **3-dot menu** (top right)
3. Tap **Add to Home screen** or **Install app**
4. Tap **Add** — done!

---

## 🗂 Files Explained

| File | What it does |
|------|-------------|
| `WealthBuilderApp.html` | The entire app — all tabs, logic, and UI |
| `manifest.json` | Tells the phone it's an installable app (name, icon, colours) |
| `sw.js` | Service worker — makes the app work offline |
| `icon-192.svg` | App icon shown on your home screen |

---

## 💾 Your Data

All data saves locally in your browser's storage on your phone.
It does NOT go to any server. Only you can see it.

---

## 🔄 Updating the App

To update: just re-upload `WealthBuilderApp.html` to GitHub with the new version.
Your data is stored separately so it won't be lost.
