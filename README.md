# memecoin-desk-live

Public PAPER book snapshots for the Memecoin Desk PWA.

- Source of truth is rebuilt on the bot side, then pushed here as JSON feeds.
- PWA polls the raw URLs every ~45s (Vercel Hobby free — no redeploy needed).
- PAPER only. No keys, no live trading.

## Dual-Lane Feeds

**Alpha Lane** (main desk):  
https://raw.githubusercontent.com/Ludovic-M-DAN/memecoin-desk-live/main/desk-state.json

**Beta Lane** (experimental):  
https://raw.githubusercontent.com/Ludovic-M-DAN/memecoin-desk-live/main/desk-state-beta.json
