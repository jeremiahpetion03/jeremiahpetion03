### Hi, I'm Jeremiah 👋

Software engineer based in New York, working on ML systems and full-stack applications, with a B.S. in Computer Programming & Information Systems from Farmingdale State College. I build and debug ML training and inference systems in Python and PyTorch, and full-stack apps from React front ends to Node.js APIs, databases, and lower-level systems. One of my biggest priorities is testing: proving code is correct, not just assuming it is. I've also worked in AI training, evaluating model output against strict rubrics.

**Languages:** Python · TypeScript · JavaScript · Java · Rust · C++ · Go · SQL
**ML:** PyTorch · NumPy · Hugging Face Transformers · CUDA
**Tools:** React · Node.js · Next.js · PostgreSQL · SQLite · Prisma · Playwright · pytest · Docker · GitHub Actions

### Machine learning engineering

| Project | What it is | Stack |
|---|---|---|
| [**Forge**](https://github.com/jeremiahpetion03/forge) | Harness that creates and validates ML engineering tasks: 10 tasks, 60 hidden checks, 46/46 planted wrong solutions caught, CI on Linux and Windows | Python, NumPy, pytest |
| [**Kestrel**](https://github.com/jeremiahpetion03/kestrel) | PyTorch training and inference pipeline with KV caching, gradient checkpointing, and int8 quantization, each verified before benchmarking on CPU and GPU | Python, PyTorch, CUDA |
| [**kvdiff**](https://github.com/jeremiahpetion03/kvdiff) | Differential tester for KV-cache and padding correctness in Hugging Face Transformers; found and instrumented a NaN in Qwen2's eager fp16 attention and tested two fixes | Python, PyTorch |
| [**gradproof**](https://github.com/jeremiahpetion03/gradproof) | GPT-style transformer in pure NumPy with hand-written backprop, verified against finite differences and PyTorch autograd | Python, NumPy |

**Open source:** reported [huggingface/transformers#51079](https://github.com/huggingface/transformers/issues/51079), a NaN in Qwen2 eager attention under fp16 with left padding, with a standalone reproduction, the measured cause, and two tested fixes.

### Systems and full-stack

| Project | What it is | Stack |
|---|---|---|
| [**Lanes**](https://github.com/jeremiahpetion03/lanes) | Real-time collaborative Kanban board with auth, permissions, drag-and-drop, and live multi-user sync | React, TypeScript, Node.js, SQLite |
| [**Waypoint**](https://github.com/jeremiahpetion03/waypoint) | Route planner implementing Dijkstra, A\*, bidirectional search, and Traveling Salesman solvers, cross-checked against brute force | Python |
| [**ferrodb**](https://github.com/jeremiahpetion03/ferrodb) | Multi-threaded, Redis-compatible database with crash-safe persistence; works with standard Redis tools | Rust |
| [**ferrobench**](https://github.com/jeremiahpetion03/ferrobench) | Load tester for Redis servers that verifies every reply and fails on lost or corrupted writes | Go |
| [**ttl-lru**](https://github.com/jeremiahpetion03/ttl-lru) | Header-only C++17 LRU cache with per-key expiry, cross-checked against a reference model under AddressSanitizer and UBSan | C++ |

Each project has a README covering its design decisions, plus automated tests that run on every push.

📫 jeremiahpetion03@gmail.com
