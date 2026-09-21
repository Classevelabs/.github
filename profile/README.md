## ClassEve

**Independent software lab. We ship solved problems.**

Every ClassEve product exists because we ran into a problem that wasn't solved well enough — so we solved it and shipped the solution. Claims are provable, not superlative: measured, benchmarked, or plainly qualified as our own result. Full statement: **[classeve.com/philosophy](https://classeve.com/philosophy)**

Website: **[classeve.com](https://classeve.com)**

### Everything we ship

| Product | What it solves |
| --- | --- |
| **[Lven Instant](https://classeve.com/releases/lven)** | Offline voice-to-text for Windows, Linux, and Android — on-device, audio never uploaded |
| **[Lven Cloud](https://classeve.com/releases/lven/cloud)** | Server-transcribed dictation for hardware below the on-device floor |
| **[REX](https://classeve.com/rex)** | A coding agent that runs your whole Windows PC — writes code and works your apps by voice or text |
| **[earslate](https://classeve.com/releases/earslate)** | Free live speech translation on Android, on your own Gemini/OpenAI key |
| **[Folio PDF](https://classeve.com/public/folio-pdf)** | Free Android document opener — PDF, DOCX, XLSX, and more |
| **[Context Zero Engine](https://classeve.com/public/context-zero-engine)** | Code intelligence for AI agents — a local code graph over MCP |
| **[Credential Airlock](https://classeve.com/public/airlock)** | Keeping real API keys out of AI agents' hands |
| **[RAI](https://classeve.com/public/rai)** | CPU-only LLM inference — no GPU required |

Plain-language explainers of the tech behind these: **[classeve.com/learn](https://classeve.com/learn)**

### Open source

All Apache-2.0.

| Project | What it is |
| --- | --- |
| **[context-zero-engine](https://github.com/Classevelabs/context-zero-engine)** | Local code-intelligence engine for AI agents — indexes a repository into a PostgreSQL code graph and serves token-budgeted context (symbols, effects, contracts, blast radius, similar code) over MCP and HTTP. |
| **[rai](https://github.com/Classevelabs/rai)** | CPU-only LLM inference engine in pure Rust — 4-bit quantized AVX2 kernels, speculative decoding, and a local HTTP/MCP server. No GPU, no Python runtime. |
| **[credential-airlock](https://github.com/Classevelabs/credential-airlock)** | Self-hosted credential firewall for AI agents — agents see only dummy keys; a deny-by-default local proxy injects the real credential for allow-listed hosts and seals secrets at rest with the OS root of trust. |
| **[earslate](https://github.com/Classevelabs/earslate)** | Free, open-source Android live speech translation — bring your own Gemini or OpenAI key and it translates nearby speech in real time into your earbuds. |
| **[pulse](https://github.com/Classevelabs/pulse)** | Independent uptime witness for ClassEve's public surfaces, run from GitHub Actions. |

### Official identity

This organization — **[@Classevelabs](https://github.com/Classevelabs)** — is the official ClassEve GitHub organization. The canonical list of every official ClassEve account and domain is published at **[classeve.com/official](https://classeve.com/official)**.

| Surface | Official location |
| --- | --- |
| Website | [classeve.com](https://classeve.com) — the only official ClassEve domain |
| Open-source code | this organization |
| Rust crates | the `classeve-rai-*` namespace on [crates.io](https://crates.io/crates/classeve-rai-infer) |
| Security contact | [security.txt](https://classeve.com/.well-known/security.txt) — security@classeve.com |

**Not affiliated with ClassEve:** the GitHub account [`github.com/ClassEve`](https://github.com/ClassEve) has a username matching our brand name but is an unrelated third-party personal account, created in 2016, holding unrelated web projects. It has no connection to ClassEve and we have never operated under it. It is named here only so it is not mistaken for ours.

**Some products are not open-source.** REX, Lven Instant, Lven Cloud, and Folio PDF are closed-source and their repositories are private. The projects above are ClassEve's public-source code. A missing public repository for a closed-source ClassEve product is expected, not a sign you are on the wrong account.
