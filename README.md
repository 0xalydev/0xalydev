<p align="center">
  <img src="assets/avatar_square.png" alt="0xAlyDev" width="160" />
</p>

# 0xAlyDev

AI Systems Engineer and Open-Source Contributor specializing in autonomous agent runtimes, gateway architectures, communication protocols, and developer infrastructure.

---

### Merged Open-Source Contributions

#### elizaOS (Agent Framework & Runtime)
- **[PR #32974](https://github.com/elizaOS/eliza/pull/32974)** - `fix(core): preserve code indentation during assistant text normalization (#30590)`
  - **Status:** Merged into develop by @lalalune
  - Preserves exact code block indentation during assistant text normalization without mangling fenced CommonMark syntax.
  - Re-exports canonical normalizer directly from `@elizaos/core` to eliminate duplicated logic.
- **[PR #30624](https://github.com/elizaOS/eliza/pull/30624)** - `fix(ui): exclude generated mobile build roots from component inventory (#30593)`
  - **Status:** Merged into develop by @lalalune
  - Resolved component inventory contamination where generated native mobile bundles (under `packages/agent/dist-mobile-*` and `packages/app/ios/.../agent-bundle.js`) were incorrectly crawled and indexed.
  - Hardened build tree exclusions to isolate production component manifests from transient compilation outputs.

#### OpenClaw (Autonomous Agent Fleet & Gateway)
- **[PR #145223](https://github.com/openclaw/openclaw/pull/145223)** - `fix(telegram): deliver plain text after legacy rich rejection (#145201)`
  - **Status:** Merged into main by @obviyus
  - Fixed total message delivery blackout on older and self-hosted Telegram Bot API servers that reject rich message payloads with 400 bad request.
  - Implemented automatic classification and seamless fallback to plain text delivery, preventing silent reply drops.

#### NousResearch / Hermes-Agent Ecosystem
- **[PR #104933](https://github.com/NousResearch/hermes-agent/pull/104933)** - `fix(gateway): multiplex routes, busy follow-ups, mid-turn authz and completions stay in the admitting profile`
  - **Status:** Merged upstream into main (salvaging PR #105040)
  - Engineered gateway profile route isolation and secondary adapter discriminator logic to guarantee mid-turn completions stay in admitting profile boundaries.

---

### Active Contributions

- **[tenstorrent/tt-metal](https://github.com/tenstorrent/tt-metal)**:
  - **[PR #55566](https://github.com/tenstorrent/tt-metal/pull/55566)** - `fix(ttnn): correct pole sign assignment and preserve positive overflow in atanh_bw (#54695)`
  - **[PR #55567](https://github.com/tenstorrent/tt-metal/pull/55567)** - `test(ttnn): add signed zeros and zero-grad zero divisor unit tests for div_bw (#55392)`

---

### Tech Stack & Focus Areas

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Bun-000000?style=for-the-badge&logo=bun&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
</p>

- **Core Focus:** Autonomous Agent Frameworks, Distributed Gateways, Messaging Protocols, Execution Sandboxes, High-Performance Compute Runtimes
- **GitHub Backup Reference:** https://github.com/Aly0xDev

---

<p align="center">
  <i>"Relentlessly building and shipping open-source intelligence."</i>
</p>
