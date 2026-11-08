# Hi, I'm Oluwaseun


CS student at Georgia State (B.S., expected August 2027). I've been shipping multiplayer games since 2018, and that work has reached **63M+ visits** and **$250K+ in revenue**, with one update peaking at about **21K concurrent players**.


Most of what I build is backend and systems code: server-authoritative networking, persistent data, validated economy and inventory systems, and the analytics that show what's actually working. I'm looking for software engineering roles and internships.


## Projects


| Project | Engineering focus |
|---|---|
| **[sessionledger](https://github.com/samsho-lab/sessionledger)** | AI-assisted Python/SQLite systems lab: idempotent rewards, atomic transfers, session fencing, and a hash-chained audit journal. 15 automated tests and Windows/Linux CI. *Python, SQLite, unittest, GitHub Actions* |
| **[wallet-inventory-api](https://github.com/samsho-lab/wallet-inventory-api)** | REST API for an in-game wallet and inventory. Idempotent purchases, no double-spends under concurrency, an append-only ledger. *Python, FastAPI, SQLite, Docker* |
| **[authoritative-arena](https://github.com/samsho-lab/authoritative-arena)** | Real-time multiplayer server where the server decides everything. Fixed tick loop, input validation, speed-hack protection, and a browser client with prediction and reconciliation. *Java 21, WebSockets, JavaScript* |
| **[chip8-emulator](https://github.com/samsho-lab/chip8-emulator)** | CHIP-8 emulator with switchable compatibility quirks, an SDL2 frontend, a headless runner, and 26 opcode tests run under AddressSanitizer in CI. *C++20, CMake, SDL2* |
| **[roblox-remote-guard](https://github.com/samsho-lab/roblox-remote-guard)** | Typed Luau modules for securing Roblox RemoteEvents: argument schemas (including NaN rejection), per-player token-bucket rate limiting, and Janitor cleanup. Tested with the Luau CLI. *Luau, Rojo, Wally* |
| **[player-analytics](https://github.com/samsho-lab/player-analytics)** | Telemetry pipeline: cleans messy event logs, then computes an ordered funnel, Day-N retention and an A/B test result, all in SQL. *Python, SQL, SQLite, matplotlib* |


## Technical skills


- **Languages:** Luau/Lua, Python, Java, SQL, R; additional project experience with C++, C#, JavaScript/TypeScript
- **Tools & platforms:** Git/GitHub, Linux, REST APIs, AWS, Google Cloud, Unity, Unreal Engine
- **Backend & networking:** server-authoritative architecture, RemoteEvents/RPC, input validation, state synchronization, session lifecycle, and client prediction
- **Data & reliability:** persistent data, data modeling, serialization, inventory and economy state, idempotency, and concurrency control
- **Quality & evaluation:** root-cause debugging, code reasoning, automated testing, edge-case validation, and performance analysis
- **Gameplay systems:** combat and hitbox validation, character customization, progression, matchmaking, quests, and UI

