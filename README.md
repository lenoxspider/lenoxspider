<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:4a1d96,100:9d4edd&height=200&section=header&text=1337&fontSize=72&fontColor=ffffff&fontAlignY=38&animation=fadeIn&desc=lenoxspider&descAlignY=60&descSize=18" width="100%" />

<a href="https://github.com/lenoxspider">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2600&pause=700&color=9D4EDD&center=true&vCenter=true&width=700&lines=i+build+things+that+run+unattended;automation+%26+AI+agents;full-stack+backends+%26+tooling;trading+%26+quant+research;low-level+C+%2F+C%2B%2B+%26+Java" alt="typing" />
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
builds:    automation · AI agents · backends · trading systems · low-level C/C++
stack:     Python · TypeScript · C · C++ · Java
contact:   t.me/lenoxspider
```

I build software across the stack. Autonomous agents and WhatsApp tooling, full-stack backends, terminal dev tools, systematic trading research, and low-level C/C++ when I want to get closer to the metal. Self-taught, 30 public repos and counting.

---

## `$ stack`

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=python,ts,js,c,cpp,java,bash,powershell&theme=dark" /><br/><br/>

**Backend & Web**

<img src="https://skillicons.dev/icons?i=nodejs,express,flask,django,spring,react,nextjs,tailwind&theme=dark" /><br/><br/>

**Data, Tools & Infra**

<img src="https://skillicons.dev/icons?i=postgres,mysql,sqlite,redis,prisma,docker,linux,git,github,nginx,vscode&theme=dark" />

</div>

---

# `$ work`

## automation & ai agents

| Project | What it does | Stack |
| --- | --- | --- |
| [whatsapp_messiah](https://github.com/lenoxspider/whatsapp_messiah) | Turns a personal WhatsApp account into a second brain + ghost-handler daemon: tool-calling agent over a local DB, hybrid FTS5 + vector search fused with Reciprocal Rank Fusion, Whisper voice-note transcription, deleted/View-Once media forensics, cadence-mimicking persona replies | TypeScript |
| [wa-assistant](https://github.com/lenoxspider/wa-assistant) | Agentic WhatsApp auto-reply: intent classification, ChromaDB long-term memory, task extraction from natural conversation, voice transcription, escalation protocol, real-time React dashboard | Baileys · BullMQ · Ollama |
| [yoof1337](https://github.com/lenoxspider/yoof1337) | Terminal-first sandboxed autonomous coding agent for local models (llama.cpp) and OpenAI - mixed tool streaming, 256-color syntax highlighting, on-demand tool loading, multi-agent orchestration, dual-pane TUI | TypeScript |
| [group_work](https://github.com/lenoxspider/group_work) | Discord bot for student team accountability: task ledger with interactive buttons, buddy verification, deadline T-minus alerts, contribution reporting, spi economy, plugin architecture | Python · DDD · aiosqlite |

## full-stack & backends

| Project | What it does | Stack |
| --- | --- | --- |
| [automated_library](https://github.com/lenoxspider/automated_library) | SmartLib - library management platform: catalog, circulation, reservations, fines, acquisitions, inventory, member services, reporting, audit logs, compliance, system health | Next.js 16 · Express 5 · Prisma · PostgreSQL · Redis · BullMQ · MinIO |
| [agent_test](https://github.com/lenoxspider/agent_test) | Flask todo REST API + assorted Python automation tools | Python · Flask · SQLite |

## trading & quant research

Every one ships with a leak-free backtest engine, out-of-sample validation, and the verdict at the top of the README - including the ones that lost.

| Bot | Market | Method | Status |
| --- | --- | --- | --- |
| [ai-trader](https://github.com/lenoxspider/ai-trader) | FX majors · XAUUSD | 14-agent LLM pipeline: news gate → macro dollar model → 4 SMC entry agents → risk manager → MT5 | live / MT5 |
| [trendhawk](https://github.com/lenoxspider/trendhawk) | metals · crypto · indices · oil (D1) | Donchian N-day breakout entries, N/2 channel trail, 2×ATR stop; 5-config ensemble | live on swap-free accounts |
| [forex_research](https://github.com/lenoxspider/forex_research) | FX majors | `RANGE_TO_TREND_TFPB`: ADX regime-transition gate + H1 trend filter + 2R target, M15 execution | frozen spec, 27-point robustness, 10k-path Monte Carlo |
| [lynx_er](https://github.com/lenoxspider/lynx_er) | EURUSD (H1) | SMC mean reversion, trailing stop, FTMO rule set | validated - 55.8% WR, +51.5% over 9 months, 7.53% max DD |
| [lynx_limit_edition](https://github.com/lenoxspider/lynx_limit_edition) | EURUSD (H1) | same model, but passive limit entries 0.30×ATR into the stretch instead of market fills | research - beats market entry OOS, under deploy bar |
| [laroi](https://github.com/lenoxspider/laroi) | XAUUSD (M1, 2009-2023 · 5.17M bars) | intraday mean reversion gated by a single XGBoost probability filter, 21 features | validation +83.7%, Sharpe 3.04, 18/24 green months |
| [rex_er](https://github.com/lenoxspider/rex_er) | XAUUSD | dual-timeframe SMC + 4 XGBoost models (1H direction, 15M entry) | research - not profitable. Old headline numbers were a lookahead artifact; honest PF 0.98 |

## systems & low-level

| Project | What it does | Stack |
| --- | --- | --- |
| [victory_stealer](https://github.com/lenoxspider/victory_stealer) | Modular Windows credential/session collector: browsers, wallets, tokens, FTP/SSH/VPN, Wi-Fi, Windows Vault, clipboard; AES-encrypted local queue, Telegram/Discord exfil, Run-key + scheduled-task persistence | C++ · MinGW · NASM |
| [cpp-load-balancer](https://github.com/lenoxspider/cpp-load-balancer) | Load balancer built from scratch | C++ |
| [cpp-atm-simulator](https://github.com/lenoxspider/cpp-atm-simulator) | Transaction/ATM simulation, built from scratch | C++ |
| [Simple-Banking-System-C-](https://github.com/lenoxspider/Simple-Banking-System-C-) | Console banking system | C++ |

## fundamentals & coursework

| Project | What it does | Stack |
| --- | --- | --- |
| [java-exam-toolkit](https://github.com/lenoxspider/java-exam-toolkit) | Exam toolkit: index-number generation, weighted final scores + letter grades, score-matrix analysis | Java |
| [squarex-java](https://github.com/lenoxspider/squarex-java) · [fast-food-kiosk-java](https://github.com/lenoxspider/fast-food-kiosk-java) | Console applications | Java |
| [Student-Management-System](https://github.com/lenoxspider/Student-Management-System) · [Student-Data-Entry-System](https://github.com/lenoxspider/Student-Data-Entry-System) · [Students-grader](https://github.com/lenoxspider/Students-grader) · [cwa-calculator](https://github.com/lenoxspider/cwa-calculator) | Student record CRUD, grading and GPA/CWA calculators | Python |
| [PhoneBook](https://github.com/lenoxspider/PhoneBook) · [toDo-list](https://github.com/lenoxspider/toDo-list) · [cart-manager](https://github.com/lenoxspider/cart-manager) · [party_list-checker](https://github.com/lenoxspider/party_list-checker) · [password-generator](https://github.com/lenoxspider/password-generator) | earlier CLI tools and small utilities | Python |

---

## `$ stats`

<div align="center">

<img height="195" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=lenoxspider&theme=radical" />
<img height="195" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=lenoxspider&theme=radical" />

<br/><br/>

<img src="https://streak-stats.demolab.com?user=lenoxspider&theme=radical&hide_border=true&background=0d1117&ring=9d4edd&fire=9d4edd&currStreakLabel=9d4edd" />

</div>

---

<div align="center">

<img src="https://komarev.com/ghpvc/?username=lenoxspider&style=for-the-badge&color=9d4edd&label=PROFILE+VIEWS" />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:9d4edd,50:4a1d96,100:0d1117&height=120&section=footer" width="100%" />

</div>