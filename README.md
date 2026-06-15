# Hamza Plojović

Senior Python and backend engineer. I work mostly on the infrastructure around AI agents: MCP integrations, agent supervision, RAG, and eval tooling.

About 5 years in. I contract remotely (B2B) from Serbia. Some of my work is on [PyPI](https://pypi.org/user/hamzaplojovic/) and [Homebrew](https://github.com/hamzaplojovic/homebrew-tap).

## Some things I've built

[godel-rwkv](https://github.com/hamzaplojovic/godel-rwkv) is a supervisor for Claude Code that watches for stuck patterns. It's a small ML model (101K params) trained on 84K real SWE-bench agent trajectories to spot when a coding agent has started looping. Runs locally on MLX / Apple Silicon, around 5ms per inference, no API cost.

[ccpair](https://github.com/hamzaplojovic/ccpair) does peer-to-peer agent pairing sessions over a local network, using mDNS for discovery. Install with `uv tool install ccpair`.

[remind](https://github.com/hamzaplojovic/remind) is a terminal reminder tool with Claude Code MCP integration. It's on PyPI and Homebrew.

[esim-gateway](https://github.com/hamzaplojovic/esim-gateway) is a FastAPI gateway that sits in front of several eSIM providers. Handles retries and circuit breakers.

I've also published a few smaller CLI tools: [dotenvguard](https://github.com/hamzaplojovic/dotenvguard), [cronguard](https://github.com/hamzaplojovic/cronguard), [branchguard](https://github.com/hamzaplojovic/branchguard), [certguard](https://github.com/hamzaplojovic/certguard), and [freeport](https://github.com/hamzaplojovic/freeport).

## Tech

`Python` `FastAPI` `Django` `PostgreSQL` `Redis` `Kubernetes` `MCP / RAG / Agents` `Pydantic` `SQLAlchemy` `uv` `Go`

## Links

[![Website](https://img.shields.io/badge/Web-hamzaplojovic.me-black)](https://hamzaplojovic.me)
[![Homebrew](https://img.shields.io/badge/Homebrew-tap-orange?logo=homebrew&logoColor=white)](https://github.com/hamzaplojovic/homebrew-tap)
[![PyPI](https://img.shields.io/badge/PyPI-hamzaplojovic-blue?logo=pypi&logoColor=white)](https://pypi.org/user/hamzaplojovic/)
