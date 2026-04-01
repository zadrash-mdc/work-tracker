# 🚀 GitHub Pages Setup Guide
## Ministerios Una Voz Profética — Work Tracker

These are all the files you need. Upload them to GitHub exactly as named.

---

## Files in this package

| File | Purpose |
|------|---------|
| `index.html` | The main app |
| `manifest.json` | Makes it installable as an app |
| `sw.js` | Offline support (service worker) |
| `icon-192.png` | App icon (home screen) |
| `icon-512.png` | App icon (splash screen) |

---

## Step-by-step: GitHub Pages

### 1. Create a GitHub account
Go to **github.com** → Sign up (free). Use any email.

### 2. Create a new repository
- Click the **+** button (top right) → **New repository**
- Repository name: `work-tracker` (or anything you like)
- Set to **Public**
- Check **"Add a README file"**
- Click **Create repository**

### 3. Upload all 5 files
- In your new repo, click **Add file** → **Upload files**
- Drag and drop ALL 5 files from this folder
- Scroll down → click **Commit changes**

### 4. Enable GitHub Pages
- Click **Settings** tab (in your repo)
- Left sidebar → **Pages**
- Under "Source" → select **Deploy from a branch**
- Branch: **main** / folder: **/ (root)**
- Click **Save**

### 5. Your live URL
After ~60 seconds your app is live at:
```
https://YOUR-USERNAME.github.io/work-tracker/
```
Replace YOUR-USERNAME with your GitHub username.

---

## 📱 Install on iPhone (after it's live)

1. Open the URL in **Safari**
2. Tap the **Share** button (box with arrow)
3. Tap **"Add to Home Screen"**
4. Tap **Add**

It will appear as an app icon with the ministry logo. Opens full-screen, no browser bar.

---

## 🔖 NFC Tag Setup (optional)

Program your NFC sticker to open:
```
https://YOUR-USERNAME.github.io/work-tracker/
```

In iPhone Shortcuts → Automations → NFC → Open URL → paste above.

---

## ⚠️ Important note on data

Your entries are saved in your **browser's local storage** on each device.
- Phone data stays on phone
- Computer data stays on computer

If you want data to sync across devices, the next upgrade is adding a free Supabase database — just ask and we can add that anytime.

