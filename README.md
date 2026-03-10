# DISORDER
### *A Civilizational Decision Game*

> *"When order fails, what remains?"*

---

**DISORDER** is a browser-based, text-driven decision game set in the year **2061**. You are **ARBITER** — an AI advisory system reactivated inside the hollowed shell of the United Nations — and the fate of a fractured world runs through your outputs.

Three civilizational blocs hold the world in uneasy tension. A single nation, Kestanu, has been rejected from regional membership for the 23rd time. You have six hours before the session begins. Every choice you make will tip the scales — and there is no correct answer. Only consequences.

---

## 🌐 Play

Open `index.html` in any modern browser. No installation, no dependencies, no server required.

```
git clone https://github.com/Terrarioz/disorder.git
cd disorder
open index.html
```

Or simply download the file and open it directly.

---

## 🗺️ The World of 2061

The post-multilateral order is held together by three competing blocs:

| Faction | Color | Description |
|---|---|---|
| **Great East Asia Pact** | 🟡 Gold | China, Japan, Korea + 11 Southeast Asian states. The most successful integration experiment since the EU — and the most defensive of its architecture. |
| **Pan-Southern Alliance** | 🟢 Green | A coalition of nations that have met every standard, watched every bar move, and are running out of patience. |
| **Atlantic System** | 🔵 Blue | The custodians of a fading era's legal imagination — still setting standards, still writing the frameworks others must live within. |
| **United Nations** | 🟣 Purple | An institution everyone attends and no one believes in. Secretary-General Amara Diallo needs ARBITER operational. Now. |

Each bloc has a **trust score** (0–100) that shifts with every directive you issue. Your final trust distribution shapes the world you leave behind.

---

## 📖 Structure

The game unfolds across **five acts** with branching paths through **16 unique scenes** and **4 distinct endings**:

| Ending | Title | Description |
|---|---|---|
| I | **The Uneasy Architecture** | The truth named. A date agreed. The world shifted, slightly. |
| II | **Many Centers, No Periphery** | Fragmentation — but also, unexpectedly, something the South built themselves. |
| III | **The Pact Endures** | Order preserved. The moral argument conceded. The ones it didn't work for kept their own records. |
| IV | **The Last Session** | The UN ran out of things to decide. The building became a heritage site. |

**No ending is a win condition.** Each is an honest account of where the choices led.

---

## 🎮 Gameplay

- **Read** the scene narrative and intelligence briefings
- **Choose** a directive from the available options — each tagged by faction alignment or risk level
- **Watch** the trust bars shift in real time
- **Carry** the consequences of each decision into the next scene

Choices are tagged:

- `UN PROTOCOL` — procedural, balanced, often frustrating
- `EAST / SOUTH / ATLANTIC FAVOR` — faction-aligned, with trade-offs
- `RISK` — unilateral, disruptive, sometimes the most honest option

Every choice previews its immediate consequence. What it doesn't preview is the accumulation.

---

## ✍️ Themes

DISORDER is about:

- **The gap between procedural legitimacy and moral legitimacy** — when the rules are technically correct and still wrong
- **AI as an advisory system** — the question of whether a system trained on human data can ever be neutral
- **The weight of information** — what you do with a truth no one asked you to find
- **Institutional collapse** — not as explosion, but as accumulation

It does not take sides. It takes consequences seriously.

---

## 🛠️ Technical

| Detail | Value |
|---|---|
| Format | Single-file HTML (no build step) |
| Dependencies | Google Fonts (Playfair Display, IBM Plex Mono, EB Garamond) |
| State | In-memory JavaScript object — resets on page reload |
| Browser support | All modern browsers |
| Lines of code | ~585 |

The entire game — logic, narrative, styling — lives in one `index.html` file.

---

## 📜 License

This project is open source. Do what you will with it. Credit appreciated, not required.

---

*ARBITER — Installed 2047. Reactivated under emergency protocols.*
*There is no correct answer. Only consequences.*
