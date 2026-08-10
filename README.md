# Life HQ — Desktop

Your five pixel characters (Anar + the four agents) stroll along the bottom of your screen, speech bubbles show what each is up to, and a small ticker cycles the latest HQ events. Anar wears the plumbob.

## Put it on your desktop (pick one)

**A. Live wallpaper — recommended (Plash, free)**
1. Install **Plash** from the Mac App Store (by Sindre Sorhus, free & open source).
2. Click the Plash icon in the menu bar → **Add Website…**
3. Enable **Local Website**, choose this `LifeHQ-Desktop` folder (it uses `index.html`).
4. Done — the scene becomes your animated wallpaper, behind all your windows and icons.
   Tip: in Plash settings set **Reload every 15 minutes** so status refreshes.

**B. Quick look (no install)**
Double-click `index.html` — it opens in your browser with the full night-sky backdrop. Press ⌘⇧F for fullscreen and it's a screensaver.

**C. Overlay tools (advanced)**
Open `index.html#transparent` — background becomes fully transparent, for tools like Übersicht that float widgets over your existing wallpaper.

## How it updates

- The page carries a built-in snapshot of every agent's status.
- If a `status.json` file sits next to `index.html` (one is included), the page re-reads it every 60 seconds — edit that file and the bubbles/ticker change live.
- Want the agents to update it automatically after each run? Keep this folder somewhere Claude can reach (e.g. connect it in a Cowork session) and tell Claude "wire the desktop status file" — future runs will drop a fresh `status.json` whenever your desktop app is open.

## The cast

ANAR (blue hoodie, plumbob) · SCOUT the Job Scout (hat) · ODKO the Chief of Staff (tie) · INK the Application Writer (glasses) · TUYA the YPG Producer (red).

Everything runs locally — no network, no accounts, just pixels.
