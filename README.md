# Kyle's Emergency Dashboard

A single-page emergency toolkit for RSD spirals, decision paralysis, self-criticism, task initiation misfires, and overwhelm. Forced 60-second breathing entry → 5 mode selectors → structured walkthroughs → local save + Notion copy-export.

Built around frameworks you already use: TIPP, STAR, rapid evidence challenge, self-compassion break, ignition misfire, brain dump → pick one.

## How to deploy (GitHub Pages)

1. Create a new GitHub repo (e.g. `emergency-dashboard`). Make it private if you want — GitHub Pages works on private repos with Pro.
2. Upload `index.html` to the repo (drag-and-drop on github.com works).
3. Go to **Settings → Pages → Source: Deploy from a branch → main → /(root) → Save**.
4. In 1–2 minutes, your URL is live at `https://<your-username>.github.io/emergency-dashboard/`.
5. On your iPhone: open that URL in Safari → tap **Share → Add to Home Screen**. It'll install like a native app (full-screen, custom icon, offline-capable after first load).

## How it works

- **Opens in breathing mode** — you cannot skip the first 15 seconds. This is intentional. You can't think clearly when flooded; the body goes first.
- **After 15s** a "skip to tools" button appears for when you're regulated enough to move on. After 60s it auto-advances.
- **5 modes** — pick the closest match to what's happening. You can switch anytime.
- **Local save** — stored in your browser's localStorage on that device only. Nobody else sees it. Not synced.
- **Copy for Notion** — formats the entry as a Markdown-ready block you can paste into your Memory Library as an ADHD entry.
- **Panic button (bottom-right)** — sends you back to breathing from anywhere in the app.

## Data & privacy

- 100% client-side. No server, no analytics, no tracking.
- localStorage entries live on your phone. Clearing Safari data wipes them.
- Max 50 entries stored (oldest auto-deleted).
- Copy-to-clipboard → you choose what to paste into Notion.

## Tweaks you might want later

- Adjust the 60s breathing length (edit `breathSeconds = 60` in the script)
- Add a "Keith" mode with its own voice (needs your definition of how Keith talks to you)
- Sync entries to a Notion API endpoint automatically (requires a Notion integration token)
- Add Vyvanse / Americano tracking if you want to correlate what's helping

Built for Kyle, April 2026.
