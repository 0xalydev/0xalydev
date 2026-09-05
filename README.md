# Hi there, I'm Aly 👋

AI Systems Architect & Open-Source Contributor specializing in autonomous agent runtimes, sandbox orchestration, procedural generation, and distributed LLM infrastructure.

---

### 🚀 Key Open-Source Contributions & Innovations

#### 🌌 **NousResearch / Hermes-Agent Ecosystem**
- **[PR #103581](https://github.com/NousResearch/hermes-agent/pull/103581) — `fix(agent): preserve external memory-provider tools on review fork for cache parity (#103579)`**
  - Eliminated prompt-cache misses during background evaluation by preserving byte-exact `tools[]` schema parity on review forks when external memory providers are loaded.
  - Fixes 60k+ token cold-reads on prefix-caching providers (Fireworks, Anthropic, OpenRouter) with comprehensive unit regression suite.
- **[PR #103580](https://github.com/NousResearch/hermes-agent/pull/103580) — `feat(tools): add send_file tool for sandbox-to-user file transfer (#466)`**
  - Designed and engineered the core `send_file` tool solving issue #466 (sandbox-to-user file transfer & media delivery).
  - Seamless dual extraction across local & sandboxed environments (Docker, SSH, Modal, Singularity, Daytona, Vercel) via binary-safe base64 streaming with gateway media attachment pipeline integration (`MEDIA:<path>`).
  - Added full test suite with 15/15 unit tests covering security boundaries, device blocking, and size guards.
- **[PR #103503](https://github.com/NousResearch/hermes-agent/pull/103503) — `feat(skills): add procedural-3d-studio for 3D mesh and game asset generation`**
  - Designed and built a complete procedural 3D modeling and game asset studio natively for Hermes Agent.
  - Zero external heavyweight dependencies, generating OBJ, GLTF/GLB, STL, Three.js, and Godot 4 mesh formats.
- **[PR #103550](https://github.com/NousResearch/hermes-agent/pull/103550) — `feat(plugins): add hf-inspector plugin for Hugging Face model and GGUF quant discovery`**
  - Tool plugin for querying Hugging Face Hub, inspecting GGUF quantization trees, parameter counts, context limits, and hardware VRAM fit estimations.
- **[PR #103547](https://github.com/NousResearch/hermes-agent/pull/103547) — `fix(recovery): skip damaged phantom rows violating destination constraints (#102240)`**
  - Robust SQLite foreign key repair & corruption recovery engine for broken relational databases.

---

### 🛠️ Core Tech Stack & Tooling

```
Languages  : Python, TypeScript / JavaScript, Rust, C++
Runtimes   : Node.js, Bun, PyTorch, llama.cpp, vLLM
AI / ML    : Hermes-3, Llama-3, Agent Architectures, Function Calling, Prompt Engineering
Engines    : Three.js, Godot Engine, WebGL, Procedural Mesh Synthesis
Systems    : Docker, Sandbox Isolation, IPC Protocols, WebSocket / Gateway APIs
```

---

### 📈 Activity & Focus
- **Agent Sandbox Protocols**: Building rock-solid, zero-leak file transfer and execution protocols for autonomous code interpreters.
- **Agent Tooling**: High-leverage skills and CLI tools for developer productivity.
- **Procedural Toolchains**: Light-weight math-first asset generation for games and simulations.

📫 *Let's build the open agentic future together.*
