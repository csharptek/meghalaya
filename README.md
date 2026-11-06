# Meghalaya & Kamakhya Expedition Map (Dec 2026)

A sleek, mobile-optimized interactive itinerary and GPS tour map for 15 travelers covering Guwahati, Sumer/Umsning, Laitlum, Krang Shuri, Shnongpdeng, Sohra (Wei Sawdong, Arwah, Nohkalikai, Mawsmai), Mawphanlur, Umiam Lake, and Kamakhya Temple.

## How to Deploy on Railway.com via GitHub

### Option 1: GitHub Repo (Recommended)
1. Unzip `meghalaya-tour-railway.zip`.
2. Push all extracted files (`index.html`, `package.json`, `README.md`) to a new repository on your GitHub account.
3. Open [Railway.app](https://railway.app) and click **"New Project"**.
4. Select **"Deploy from GitHub repo"** and choose your repository.
5. Railway will automatically detect `package.json`, run `npx serve`, and generate a public live URL.

### Option 2: Railway CLI (Direct from terminal)
```bash
npm install -g @railway/cli
railway login
railway init
railway up
```

## Features
- **Day-by-Day Filters**: Switch between Day 1 through Day 6 or view the full circuit.
- **Trek Difficulty Indicators**: Clear color-coded badges (Zero Trek, Easy, Moderate, Steep).
- **Google Maps & Photos Integration**: Click any stop to inspect live photos and coordinates.
- **Mobile Responsive Drawer**: Works smoothly on iPhones, Android devices, tablets, and desktop.
