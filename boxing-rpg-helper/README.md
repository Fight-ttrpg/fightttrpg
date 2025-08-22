# Boxing RPG — Dice & Combat Helper

A single-file HTML app to run GM-less bouts for the **Boxing RPG**. Paste two character sheets, roll **Tempo**, execute **Actions**, resolve **Reactions**, and handle **Corner** phases. Tracks HP, Stamina, Edge, counters-per-minute, zones, and temporary modifiers.

## Quick Start
1. Open `index.html` in your browser.
2. Paste each fighter’s character sheet (left panel) and click **Import**.
3. Click **Roll Tempo**. Tempo winner chooses an **Action**; the other side **reacts**.
4. Use **Attack Combo** (costs the **full minute**) or **Taunt / Move / IQ / Recover** (costs **one Tempo**).
5. See the **Combat Log** for a transparent breakdown of rolls and effects.

## Rules Version
This helper uses the **v4.1 patch** defaults (Aug 22, 2025). See `/rules/`.

## Deploy on GitHub Pages
- Create a repo and push these files.
- In GitHub → **Settings → Pages**: choose **GitHub Actions** and commit the workflow below.
- Your site will publish at `https://<user>.github.io/<repo>/`.

## Local Dev with Codespaces
- Open the repo and click **Code → Create codespace**.
- The devcontainer installs Live Server; run `live-server --port=5500` and preview.

## Notes
- Tempo ties: **both lose 1 Stamina** and reroll.
- Counter on defense margin **+3**, Perfect Counter on **+5** (+1 dmg).
- Defender gains **+1 Stamina** on each successful block/evade.
- 0 Stamina imposes **−2 to all rolls** until recovered.
