# 🏴‍☠️ The GoyGram Project

<p align="center">
  <img src="[https://raw.githubusercontent.com/sepiol026-wq/GoyGram/refs/heads/main/GoyGram.png](https://raw.githubusercontent.com/sepiol026-wq/GoyGram/refs/heads/main/GoyGram.png)" alt="GoyGram Logo" width="650">
</p>

**Production-grade speed, absolute control, and maximum OpSec.**

Welcome to the official GitHub organization for the GoyGram project. We build low-level, split-brain Telegram tooling that strips away enterprise bloat in favor of surgical precision. 

## ⚡ Our Philosophy
We believe that developers interacting with Telegram's API and MTProto protocols shouldn't be handcuffed by heavy abstractions, hidden background tasks, or memory-hogging Pydantic classes. 

Our tools are built on three core pillars:
1. **Zero-Cost Abstractions:** Python handles the orchestration, Rust handles the heavy lifting (crypto and codec). No runtime code generation, no useless memory overhead.
2. **Total Transparency:** If the network fails, it fails loud. No silent retries, no hidden middleware. You control the event loop.
3. **OpSec First:** Secure vault sessions derived from machine-IDs, aggressive memory zeroization, and zero hardcoded secrets.

## 📦 Main Repositories

* **[GoyGram/GoyGram](https://github.com/GoyGram/GoyGram)** — The core framework. Dual transport (Bot API + MTProto), dynamic dispatch, and raw TCP performance.
* *More modules and FOSS tooling coming soon.*

## 📚 Resources
* [**Official Wiki**](https://github.com/GoyGram/GoyGram/wiki) — 55+ pages of hardcore documentation. Read the manual.
* [**PyPI Package**](https://pypi.org/project/goygram/) — Pre-built wheels for Linux, Windows, and macOS (x86-64 + ARM64).

---
*Code without compromises. Licensed under AGPLv3.*
