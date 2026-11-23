<h3 align="center">Frankfurtlin</h3>

<p align="center">
  I build tools for <b>DeepSeek Harness</b> — plugins, an Android client, and the glue that lets a
  self-hosted agent actually reach the phone in my hand.
</p>

---

Most of my work lives in one place: **DSH**, a self-hosted agent harness I run on my own server.
The pieces below turn it from a web page into something that can touch the rest of my devices.

**DSH Pocket** — an Android client for DSH. Native Flutter UI over an SSH tunnel to your own host,
plus a phone bridge so the agent can read the screen, tap, type and move files on the device.
[`dsh-pocket`](https://github.com/frankfurtlin/dsh-pocket)

**Plugins** — small, single-purpose extensions that run inside the harness:

- [`dsh-pet`](https://github.com/frankfurtlin/dsh-pet) — a capybara that lives in the corner and reacts to session state
- [`dsh-webpilot`](https://github.com/frankfurtlin/dsh-webpilot) — a real browser inside the host, driven by the agent
- [`dsh-kb`](https://github.com/frankfurtlin/dsh-kb) — a knowledge base with hybrid search and an LLM-written wiki
- [`dsh-wallstreet`](https://github.com/frankfurtlin/dsh-wallstreet) — market panel: indices, breadth, turnover
- [`dsh-creative-studio`](https://github.com/frankfurtlin/dsh-creative-studio) — writing, design and logo workbenches in one panel
- [`dsh-tavern`](https://github.com/frankfurtlin/dsh-tavern) — character-card writing and roleplay
- [`dsh-ziwei`](https://github.com/frankfurtlin/dsh-ziwei) — 紫微斗数 charting
- [`dsh-game`](https://github.com/frankfurtlin/dsh-game) — poker and mahjong
- [`dsh-bartending`](https://github.com/frankfurtlin/dsh-bartending) — cocktail recipes
- [`dsh-skin`](https://github.com/frankfurtlin/dsh-skin) — theme tokens and a few visual primitives

**Elsewhere** — a Minecraft Fabric mod
([`mixinenhance`](https://github.com/frankfurtlin/mixinenhance)), older web and Java projects from
school, mostly archived.

---

<sub>Everything here assumes you run your own server. No accounts, no telemetry.</sub>
