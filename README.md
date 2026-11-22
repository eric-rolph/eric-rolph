# Hi, I'm Eric Rolph

I build **local-first AI tools**, **embedded ESP32 & Raspberry Pi hardware**, **3D/GPU graphics & Blender physics**, **bipedal robotics**, and **browser-based synthesizers & games** — mostly running offline, bare-metal, or on Cloudflare Workers.

Website: **[ericrolph.com](https://ericrolph.com)**

---

### Hardware, Embedded & Edge AI
| Project | What it does | Stack |
|---|---|---|
| **[esp32-radar-tracker](https://github.com/eric-rolph/esp32-radar-tracker)** | Real-time 24GHz mmWave radar motion tracker (HLK-LD2450 + SSD1306 OLED) with Alien Motion Tracker visuals | ESP32-S3, Arduino C++, CircuitPython |
| **[esp-vocat-voice-assistant](https://github.com/eric-rolph/esp-vocat-voice-assistant)** | Direct-to-OpenAI Realtime API voice assistant on Espressif VoCat / Echo Ear — no proxy server | ESP32-S3, ESP-IDF, C++, WebSocket |
| **[pi5-local-voice-assistant](https://github.com/eric-rolph/pi5-local-voice-assistant)** | 100% offline voice assistant (Parakeet ONNX STT → streaming Ollama → TTS) with Voice Bonnet & RGB LEDs | Raspberry Pi 5, Python, ONNX, Ollama |
| **[open-ambilight](https://github.com/eric-rolph/open-ambilight)** | Zero-install browser/PWA Ambilight screen sync & Adalight WS2812B LED controller ([Live App](https://eric-rolph.github.io/open-ambilight/)) | TypeScript, Web Serial API, Vite |
| **[magtag](https://github.com/eric-rolph/magtag)** | Offline e-paper air quality & weather station (PM2.5, BME280, NowCast AQI, persistent history) | CircuitPython, Adafruit MagTag |
| **[m5stack-atom-echo-voice-assistant](https://github.com/eric-rolph/m5stack-atom-echo-voice-assistant)** | Bare-metal OpenAI Realtime voice assistant for the M5Stack ATOM Echo | ESP32, ESP-IDF, C |

### 3D Graphics, Blender Physics & Networking
| Project | What it does | Stack |
|---|---|---|
| **[packet-highway](https://github.com/eric-rolph/packet-highway)** | 3D network traffic & Wireshark `.pcap` visualizer — packets drive down a divided highway by protocol | Python, FastAPI, Scapy, Three.js |
| **[st-flip-blender](https://github.com/eric-rolph/st-flip-blender)** | Large-time-step FLIP liquid simulation add-on for Blender 4/5 (SIGGRAPH 2026 implementation) | Python, CUDA, Blender |
| **[unwrap-variations](https://github.com/eric-rolph/unwrap-variations)** | Variational UV unwrapping add-on for Blender 4/5 — generate, score by distortion, and branch mutations | Python, Blender |
| **[gpu-shape-morphing](https://github.com/eric-rolph/gpu-shape-morphing)** | Atlas-free WebGL 2.0 real-time vector font & Bezier shape morphing ([Live Demo](https://eric-rolph.github.io/gpu-shape-morphing/)) | WebGL2, GLSL, JavaScript |
| **[strange-attractor-lab](https://github.com/eric-rolph/strange-attractor-lab)** | GPU density-rendered strange attractor & chaos visualizer ([Live Demo](https://strange-attractor-lab.ericrolph.workers.dev/)) | TypeScript, WebGL, Cloudflare Workers |

### Robotics, Simulation & Local AI Tooling
| Project | What it does | Stack |
|---|---|---|
| **[microduck-robot-brain](https://github.com/eric-rolph/microduck-robot-brain)** | Four-tier autonomous brain for the Pollen Robotics Microduck / Open Duck Mini 14-DOF biped | Python, C++20, MuJoCo, ONNX |
| **[beamng-mcp](https://github.com/eric-rolph/beamng-mcp)** | Local-first MCP server for BeamNG.drive, BeamNGpy, Lua extensions, and GPU vision | Python, Lua, MCP |
| **[llm-benchmark](https://github.com/eric-rolph/llm-benchmark)** | Reproducible local LLM eval suite for Ollama, LM Studio, vLLM, and llama.cpp (87 tasks, ELO rankings) | Python |
| **[foley-forge](https://github.com/eric-rolph/foley-forge)** | On-device VLM auto-foley for DaVinci Resolve, Premiere Pro & Final Cut Pro (FCPXML / EDL export) | Python, Local VLM |
| **[nv-maser-twin](https://github.com/eric-rolph/nv-maser-twin)** & **[nv-maser-hardware](https://github.com/eric-rolph/nv-maser-hardware)** | Digital twin and open hardware design for an NV-center diamond maser active shimming system | PyTorch, NumPy, RF/Magnetics |

### Interactive Browser Synths, Astronomy & Games
| Project | Live Link | Stack |
|---|---|---|
| **[arp-2600-studio](https://github.com/eric-rolph/arp-2600-studio)** | [Play Live](https://arp-2600-studio.ericrolph.workers.dev) — ARP 2600 semi-modular synth, MIDI & varispeed tape studio | Web Audio, JS, Cloudflare Workers |
| **[tonto-studio](https://github.com/eric-rolph/tonto-studio)** | [Play Live](https://tonto-studio.ericrolph.workers.dev/) — Five-cabinet TONTO modular synthesizer with cross-patching | Web Audio, JS, Cloudflare Workers |
| **[prism-game](https://github.com/eric-rolph/prism-game)** | [Play Live](https://prism.ericrolph.workers.dev/) — Geometric light-refraction roguelite | Rust, WebAssembly, Cloudflare Workers |
| **[lunar-visibility](https://github.com/eric-rolph/lunar-visibility)** | [View Live](https://lunar-visibility.pages.dev) — Global lunar crescent visibility map (Yallop & Odeh criteria) | TypeScript, Cloudflare Pages |
| **[serverless-time-trial-racing-game](https://github.com/eric-rolph/serverless-time-trial-racing-game)** | Edge-verified deterministic C17 Box3D/WASM sim racing with weekly procedural tracks | C17, Rust, WASM, Cloudflare Workers |
| **[Throughput-The-Inference-Grid](https://github.com/eric-rolph/Throughput-The-Inference-Grid)** | [Play Live](https://throughput-the-inference-grid.ericrolph.workers.dev) — GPU data-center builder | Unity WebGL, C#, Cloudflare Workers |
