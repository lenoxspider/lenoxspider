<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:4a1d96,100:9d4edd&height=200&section=header&text=1337&fontSize=72&fontColor=ffffff&fontAlignY=38&animation=fadeIn&desc=lenoxspider&descAlignY=60&descSize=18" width="100%" />

<a href="https://github.com/lenoxspider">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2600&pause=700&color=9D4EDD&center=true&vCenter=true&width=680&lines=systematic+trading+%26+market+automation;quantitative+research+that+fails+honestly;messaging+tooling+%26+AI+agents;low-level+C%2F%2B%2B+systems+work;build+it%2C+break+it%2C+ship+it" alt="typing" />
</a>

<br/>

<a href="https://t.me/lenoxspider"><img src="https://img.shields.io/badge/Telegram-@lenoxspider-9d4edd?style=for-the-badge&logo=telegram&logoColor=white&labelColor=0d1117"/></a>
<a href="https://instagram.com/unkiki_7"><img src="https://img.shields.io/badge/Instagram-unkiki__7-9d4edd?style=for-the-badge&logo=instagram&logoColor=white&labelColor=0d1117"/></a>
<a href="https://github.com/lenoxspider"><img src="https://img.shields.io/badge/GitHub-lenoxspider-9d4edd?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117"/></a>

</div>

---

## `$ whoami`

```yaml
handle:    lenoxspider
alias:     1337
focus:     systematic trading · quant research · backend & agent tooling
markets:   FX majors · XAUUSD/XAGUSD · BTC/ETH · indices · oil
stack:     Python · TypeScript · C · C++ · Java
status:    open to trading-bot collabs
contact:   t.me/lenoxspider
```

I build trading systems and the infrastructure around them. Most of my repos are either **backtest-driven strategy research** - with the honest verdict at the top of the README, including when it fails - or **automation**: WhatsApp agents, Discord bots, AI coding tools, full-stack backends. Plus low-level C/C++ work when I want to get closer to the metal.

---

## `$ stack`

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=python,ts,js,c,cpp,java,bash,sql&theme=dark" /><br/><br/>

**Backend & Web**

<img src="https://skillicons.dev/icons?i=nodejs,express,flask,django,spring,react,nextjs,tailwind&theme=dark" /><br/><br/>

**Data, Tools & Infra**

<img src="https://skillicons.dev/icons?i=linux,docker,git,github,redis,postgres,mysql,nginx,vscode&theme=dark" />

</div>

---

## `$ bots`

**Trading systems.** Every one ships with a leak-free backtest engine, out-of-sample validation, and a verdict at the top of the README - including the ones that lost.

| Bot | Market | Method | Status |
| --- | --- | --- | --- |
| [ai-trader](https://github.com/lenoxspider/ai-trader) | EURUSD · XAUUSD · GBPUSD · USDJPY | 14-agent LLM pipeline: news gate → macro dollar model → 4 SMC entry agents → risk manager → MT5 | live / MT5 |
| [trendhawk](https://github.com/lenoxspider/trendhawk) | metals · crypto · indices · oil (D1) | Donchian N-day breakout entries, N/2 channel trail, 2×ATR stop; 5-config ensemble | live - **swap-free accounts only**, swap costs kill it otherwise |
| [forex_research](https://github.com/lenoxspider/forex_research) | FX majors | `RANGE_TO_TREND_TFPB`: ADX regime-transition gate + H1 trend filter + 2R target, M15 exec | production-frozen spec, 27-point robustness, 10k-path Monte Carlo |
| [lynx_er](https://github.com/lenoxspider/lynx_er) | EURUSD (H1) | SMC mean reversion, trailing stop, FTMO rule set | validated - 55.8% WR, +51.5% over 9 months, 7.53% max DD |
| [lynx_limit_edition](https://github.com/lenoxspider/lynx_limit_edition) | EURUSD (H1) | same model, but **passive limit entries** 0.30×ATR into the stretch instead of market fills - earns the spread instead of paying it | research - beats market entry OOS, under deploy bar |
| [laroi](https://github.com/lenoxspider/laroi) | XAUUSD (M1, 2009-2023 · 5.17M bars) | intraday mean reversion gated by a single XGBoost probability filter, 21 features | validation +83.7%, Sharpe 3.04, 18/24 green months |
| [rex_er](https://github.com/lenoxspider/rex_er) | XAUUSD | dual-timeframe SMC + 4 XGBoost models (1H direction, 15M entry) | **research - not profitable.** Old headline numbers were a lookahead artifact; honest PF 0.98 |

---

## `$ tools`

**Automation, agents and infrastructure.**

| Project | What it does | Stack |
| --- | --- | --- |
| [whatsapp_messiah](https://github.com/lenoxspider/whatsapp_messiah) | Turns a personal WhatsApp account into a second brain + ghost-handler daemon: tool-calling agent over a local DB, hybrid FTS5 + vector search fused with Reciprocal Rank Fusion, Whisper voice-note transcription, deleted/View-Once media forensics, cadence-mimicking persona replies | TypeScript |
| [wa-assistant](https://github.com/lenoxspider/wa-assistant) | Agentic WhatsApp auto-reply: intent classification, ChromaDB long-term memory, task extraction, voice transcription, escalation protocol, real-time React dashboard | Baileys · BullMQ · Ollama |
| [automated_library](https://github.com/lenoxspider/automated_library) | SmartLib - full-stack library management: catalog, circulation, reservations, fines, acquisitions, inventory, audit logs | Next.js 16 · Express · Prisma · Redis · MinIO |
| [group_work](https://github.com/lenoxspider/group_work) | Discord bot killing free-riding in student teams: task ledger with interactive buttons, buddy verification, deadline T-minus alerts, contribution reports, spi economy, plugin architecture | Python · DDD · aiosqlite |
| [yoof1337](https://github.com/lenoxspider/yoof1337) | Terminal-first sandboxed autonomous coding agent for local models (llama.cpp) and OpenAI - streaming, syntax highlighting, on-demand tool loading, multi-agent orchestration, dual-pane TUI | TypeScript |
| [victory_stealer](https://github.com/lenoxspider/victory_stealer) | Modular C++ Windows credential/session collector: browsers, wallets, tokens, FTP/SSH/VPN, Wi-Fi, Windows Vault, clipboard; AES-encrypted local queue, Telegram/Discord exfil, Run-key + scheduled-task persistence | C++ · MinGW |
| [agent_test](https://github.com/lenoxspider/agent_test) | Flask todo REST API + small Python automation tools | Python · Flask |
| [java-exam-toolkit](https://github.com/lenoxspider/java-exam-toolkit) · [squarex-java](https://github.com/lenoxspider/squarex-java) · [fast-food-kiosk-java](https://github.com/lenoxspider/fast-food-kiosk-java) | Java coursework: grading matrices, weighted final scores, console apps | Java |
| [cpp-load-balancer](https://github.com/lenoxspider/cpp-load-balancer) · [cpp-atm-simulator](https://github.com/lenoxspider/cpp-atm-simulator) | C++ fundamentals built from scratch - a load balancer and a transaction simulator | C++ |
| [Student-Management-System](https://github.com/lenoxspider/Student-Management-System) · [Student-Data-Entry-System](https://github.com/lenoxspider/Student-Data-Entry-System) · [PhoneBook](https://github.com/lenoxspider/PhoneBook) · [password-generator](https://github.com/lenoxspider/password-generator) | earlier Python tools - CRUD apps, generators, small utilities | Python |

---

## `$ stats`

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=lenoxspider&show_icons=true&theme=radical&hide_border=true&include_all_commits=true&count_private=true&bg_color=0d1117&title_color=9d4edd&icon_color=9d4edd&text_color=c9d1d9" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=lenoxspider&layout=compact&theme=radical&hide_border=true&langs_count=8&bg_color=0d1117&title_color=9d4edd&text_color=c9d1d9" />

<br/><br/>

<img src="https://streak-stats.demolab.com?user=lenoxspider&theme=radical&hide_border=true&background=0d1117&ring=9d4edd&fire=9d4edd&currStreakLabel=9d4edd" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=lenoxspider&theme=react-dark&hide_border=true&bg_color=0d1117&color=9d4edd&line=9d4edd&point=ffffff&area=true" width="100%" />

</div>

---

## `$ principles`

1. **Model the costs before celebrating.** A strategy that only works before spread, commission and overnight swap does not work.
2. **One out-of-sample look.** Tune in-sample, test once, break results down by year.
3. **Publish the failures.** trendhawk's swap kill-shot, rex_er's lookahead audit, lynx_limit_edition's unfilled-order filter - the misses are the useful part.
4. **If it can't run unattended, it isn't finished.**

---

## `$ now`

- running [trendhawk](https://github.com/lenoxspider/trendhawk)'s live bot on a swap-free account, watching for the status notification that kills it
- expanding [ai-trader](https://github.com/lenoxspider/ai-trader)'s agent roster and risk gates
- taking [lynx_limit_edition](https://github.com/lenoxspider/lynx_limit_edition)'s passive-entry edge past the deploy bar
- always down to talk **trading bots**, quant research and automation collabs
- fastest way to reach me: [Telegram](https://t.me/lenoxspider)

<div align="center">

<img src="https://komarev.com/ghpvc/?username=lenoxspider&style=for-the-badge&color=9d4edd&label=PROFILE+VIEWS" />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:9d4edd,50:4a1d96,100:0d1117&height=120&section=footer" width="100%" />

</div>