<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=24&pause=1200&color=9CA3AF&center=true&vCenter=true&width=900&lines=Frankfurtlin;Tools+for+DeepSeek+Harness;Self-hosted%2C+no+telemetry" alt="typing"/>

<p>
  <img src="https://img.shields.io/badge/DSH-DeepSeek%20Harness-6e7681?style=flat-square&labelColor=161b22" alt="DSH"/>
  <img src="https://img.shields.io/badge/Android-Flutter-6e7681?style=flat-square&labelColor=161b22" alt="Flutter"/>
  <img src="https://img.shields.io/badge/self--hosted-no%20telemetry-6e7681?style=flat-square&labelColor=161b22" alt="self-hosted"/>
</p>

</div>

---

### What I'm building

Most of my work is one thing: **DSH** (DeepSeek Harness), a self-hosted agent harness I run on my
own server. The projects below turn it from a web page into something that can reach the devices in
my room — a phone, a real browser, a pet on the desktop — and turn the server into the machine I
actually live on.

| | Project | What it is |
|---|---|---|
| 📱 | **[dsh-pocket](https://github.com/frankfurtlin/dsh-pocket)** | Android client for DSH: native Flutter UI over an SSH tunnel, plus a phone bridge that lets the agent read the screen, tap, type and move files on a real device. |
| 🖥️ | **[AgentHub](https://github.com/frankfurtlin/AgentHub)** | A floating ball for people who run four AI coding tools at once. It shows which window is waiting for a click, and jumps you there. Windows, MIT. |
| ⛏️ | **[mixinenhance](https://github.com/frankfurtlin/mixinenhance)** | A vanilla-friendly Minecraft 26.3 / Fabric mod: vein mining, fast leaf decay, auto-sorting containers. The one project here that is played rather than run. |

### Ten plugins inside the harness

| Plugin | What it does |
|---|---|
| [dsh-kb](https://github.com/frankfurtlin/dsh-kb) | Knowledge base: hybrid search, a co-occurrence graph, and a wiki the model writes itself. |
| [dsh-webpilot](https://github.com/frankfurtlin/dsh-webpilot) | A real Chrome inside the host, driven by the agent; a login wall is handed to the human and picked up afterwards. |
| [dsh-pet](https://github.com/frankfurtlin/dsh-pet) | A capybara on the desktop that reacts to session state — approvals first, thinking second. |
| [dsh-creative-studio](https://github.com/frankfurtlin/dsh-creative-studio) | Writing, design and logo benches in a single panel. |
| [dsh-wallstreet](https://github.com/frankfurtlin/dsh-wallstreet) | A-share market panel: indices, breadth, turnover, valuation. |
| [dsh-tavern](https://github.com/frankfurtlin/dsh-tavern) | Character-card writing and roleplay. |
| [dsh-ziwei](https://github.com/frankfurtlin/dsh-ziwei) | Zi Wei Dou Shu charting, read by the agent. |
| [dsh-game](https://github.com/frankfurtlin/dsh-game) | Poker and mahjong with live win-rate and shanten maths. |
| [dsh-bartending](https://github.com/frankfurtlin/dsh-bartending) | Classic cocktail recipes and ratios. |
| [dsh-skin](https://github.com/frankfurtlin/dsh-skin) | Theme tokens and visual primitives for the rest of the set. |

### How I build

- **Plain files first.** Every artifact stays readable without the program that produced it; indexes,
  vectors and graphs are rebuildable side products, never the only copy.
- **Self-hosted, no telemetry.** No accounts, no analytics, no cloud dependency — the only server is
  the one in my room. The same rule applies to this page: no counters, no stats cards.
- **The deployment ships with the code.** systemd units, e2e scripts and verification reports live in
  the repositories, not in a private wiki or on a machine only I can reach.

---

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/frankfurtlin/frankfurtlin/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/frankfurtlin/frankfurtlin/output/github-contribution-grid-snake.svg">
  <img alt="contribution snake" src="https://raw.githubusercontent.com/frankfurtlin/frankfurtlin/output/github-contribution-grid-snake.svg">
</picture>

</div>

---

<div align="center">
  <sub>Everything here assumes you run your own server. No accounts, no telemetry.
  · <a href="https://frankfurtlin.top">frankfurtlin.top</a></sub>
</div>
