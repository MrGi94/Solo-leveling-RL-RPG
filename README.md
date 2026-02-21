# Quest Log v5 ⚔️

## Deploy from your Phone (5 minutes)

### Step 1: GitHub Account
- Open **github.com** in Chrome
- Sign up or log in

### Step 2: Create Repository
- Tap **+** (top right) → **New repository**
- Name: `quest-log`
- Set to **Public**
- Tap **Create repository**

### Step 3: Upload Files
- On the repo page, tap **"uploading an existing file"** link
- Tap **"choose your files"**
- Select ALL files from this zip:
  - `index.html`
  - `manifest.json`
  - `sw.js`
  - `icon-192.png`
  - `icon-512.png`
- Tap **Commit changes**

### Step 4: Enable GitHub Pages
- Tap **Settings** (gear icon)
- Scroll to **Pages** in the left menu
- Under "Source" select **Deploy from a branch**
- Branch: **main** / **/ (root)**
- Tap **Save**
- Wait 1-2 minutes

### Step 5: Open Your App
- Your URL: `https://YOUR-USERNAME.github.io/quest-log/`
- Open in Chrome on Android

### Step 6: Install as App
- In Chrome, tap **⋮** menu → **Install app**
- Done! It's on your home screen now

## Features in v5

- **Phase/Gate System** — Steps grouped in phases, next phase unlocks when current is complete
- **Deadlines** — Set per quest and for the epic quest, with countdown warnings
- **Milestone Celebrations** — Special overlay at 25%, 50%, 75%, 100% epic progress
- **System Voice** — Claude as the omniscient System narrator
- **Quest Modification** — AI-powered quest changes
- **Adaptive Tracking** — Completion timestamps on every step

## API Key Setup
1. Go to [console.anthropic.com](https://console.anthropic.com)
2. Create an API key
3. In the app → System tab → paste key
4. Paste your Doktorat project context

## Data Backup
- System tab → **Export** saves a JSON file
- **Import** restores from JSON
- Do this regularly — localStorage is device-bound!
