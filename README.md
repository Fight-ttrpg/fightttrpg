# 🥊 Fight TTRPG — Dice & Combat Helper

[![Live Demo](https://img.shields.io/badge/demo-online-brightgreen)](https://fightrpg.github.io/fightttrpg/)

Fight TTRPG is a tabletop boxing RPG with fast-paced dice combat, stamina management, and anime-inspired drama.  
This repo contains the **browser-playable helper tool** + the official **rulesets (v4 + v4.1 patch)**.

---

## 🎮 Play Online
👉 Open the live demo: **[fightrpg.github.io/fightttrpg](https://fightrpg.github.io/fightttrpg/)**  
No install required — runs in your browser.

---

## ⚡ Features
- Import **character sheets** (HP, Stamina, Power, Speed, Defense, IQ, Personality).
- Roll **Tempo** (initiative).
- Execute **Actions**: Attack combos, Taunt, IQ Study, Move, Recover.
- Automatic **Reactions**: Defense rolls, Counters, Edge usage.
- Track **Stamina costs, HP damage, penalties**.
- Handle **Corner Phase** recovery and coach buffs.
- Built-in **Combat Log** for transparency.

---

## 📖 Rules Reference

This helper enforces the **v4.1 Patch** rules:

- **Tempo**: both roll 2d6 + Speed; tie = both lose 1 Stamina, reroll.
- **0 Stamina**: fighter suffers −2 to all rolls until stamina is recovered.
- **Defense**: successful block restores +1 Stamina.
- **Counters**: trigger on +3 margin; Perfect Counter on +5 (+1 dmg).
- **Criticals**:
  - PvP contested = margin +5
  - Solo rolls = Nat 12 (crit) / Nat 2 (crit fail)
- **Move + Attack** allowed in the same Tempo (pay stamina for both).
- **Attack Actions** consume the **full minute**.  
- **Non-Attack Actions** (Taunt, Move, IQ, Recover) consume **one Tempo**, not the full minute.

📂 Rulebooks included in `/rules/`:
- [Boxing_RPG_Playbook_v4_CLEAN.md](rules/Boxing_RPG_Playbook_v4_CLEAN.md) — v4 rules  
- [boxing_rpg_v_41_patch.txt](rules/boxing_rpg_v_41_patch.txt) — v4.1 patch notes  
- [Boxing_RPG_Playbook_UPDATED.md](rules/Boxing_RPG_Playbook_UPDATED.md) — early v1.0 concept

---

## 🛠 Development

### Local
- Clone repo → open `index.html` in your browser. Works offline.

### GitHub Pages
- Repo auto-deploys on push via GitHub Actions.
- Live at: [fightrpg.github.io/fightttrpg](https://fightrpg.github.io/fightttrpg/)

### Repo Structure
