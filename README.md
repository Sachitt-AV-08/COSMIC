# COSMIC

**Connected Operating System for Multimodal Intelligent Computing**

> One virtual device that connects everything you ever need. No irritation. Just flow.

[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://python.org)
[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![COSMIC Ecosystem](https://img.shields.io/badge/ecosystem-COSMIC-purple.svg)](#projects)

## What is COSMIC?

COSMIC is a unified AI operating system built from independent, composable projects. Each project works standalone. Together, they form a virtual device that connects everything — code, voice, gesture, files, services, security — into one seamless experience.

No cloud dependency. No API keys. No subscription. Just your hardware and your data.

## Architecture

```
                    ┌─────────────────────────┐
                    │       COSMIC            │
                    │   (The Device)          │
                    └────────────┬────────────┘
                                 │
        ┌────────────┬───────────┼───────────┬────────────┐
        │            │           │           │            │
   ┌────┴────┐ ┌─────┴─────┐ ┌──┴──┐ ┌─────┴─────┐ ┌───┴───┐
   │  Vayu   │ │   Vac     │ │Prana│ │  Drishti  │ │Rupa   │
   │ Files   │ │  Voice    │ │ OS  │ │  Gesture  │ │ 3D    │
   └─────────┘ └───────────┘ └─────┘ └───────────┘ └───────┘
        │            │           │           │            │
   ┌────┴────┐ ┌─────┴─────┐ ┌──┴──┐ ┌─────┴─────┐ ┌───┴───┐
   │Nakshatra│ │   Sutra   │ │Kala │ │  Chakra   │ │Kavach │
   │  Graph  │ │ Pipeline  │ │Debug│ │ Registry  │ │Secure │
   └─────────┘ └───────────┘ └─────┘ └───────────┘ └───────┘
```

## Projects

### Core

| Project | What It Does | Lines |
|---------|-------------|-------|
| [**Vayu**](../vayu) | File explorer — flies through code like the wind | ~1,600 |
| [**Vac**](../vac) | Voice pipeline — speaks and listens locally | ~2,100 |
| [**Prana**](../prana) | AI operating system — the life force of your device | ~3,400 |
| [**Drishti**](../drishti) | Gesture engine — sees what you mean before you touch | ~2,500 |
| [**Nakshatra**](../nakshatra) | Code graph — maps your code like star constellations | ~1,400 |

### Infrastructure

| Project | What It Does | Lines |
|---------|-------------|-------|
| [**Sutra**](../sutra) | Pipeline builder — threads of execution | ~1,700 |
| [**Chakra**](../chakra) | Service registry — the energy center | ~1,200 |
| [**Rupa**](../rupa) | Sketch to 3D — gives form to ideas | ~1,500 |
| [**Kala**](../kala) | Debugger — traces through time | ~1,300 |
| [**Kavach**](../kavach) | Supply chain security — the armor | ~1,350 |

### Companion Projects

| Project | What It Does |
|---------|-------------|
| [**neural**](../neural) | Unified CLI for local + cloud LLMs |
| [**envcheck**](../envcheck) | Environment variable validator |
| [**patchwork**](../patchwork) | Config file patcher |
| [**servehere**](../servehere) | Instant file server with QR code |
| [**modelview**](../modelview) | 3D model viewer (GLB/OBJ/STL) |
| [**imagediff**](../imagediff) | Before/after image comparison |
| [**picgrid**](../picgrid) | Image grid comparator |
| [**pixelflow**](../pixelflow) | Terminal image toolbox |

## Quick Start

```bash
# Clone the ecosystem
git clone --recurse-submodules https://github.com/Sachitt-AV-08/COSMIC.git

# Or install individual projects
pip install fastapi uvicorn numpy
```

Each project is independently installable. See individual READMEs for details.

## Philosophy

- **Local-first** — No cloud. No API keys. Your hardware, your data.
- **Composable** — Each project works standalone. Combine them for more power.
- **Mythological** — Named after Hindu/Vedic concepts. Vayu (wind), Vac (speech), Prana (breath), Drishti (sight), Nakshatra (stars).
- **Beautiful** — Dark cosmic theme across all projects. Glowing nodes. Particle effects. Clean UI.
- **Functional** — Real code, not stubs. Every project runs and does something useful.

## Built By

**A.V. Sachitt** — [GitHub](https://github.com/Sachitt-AV-08)

Part of the [CODA](https://github.com/Sachitt-AV-08) ecosystem.

## License

MIT — use anywhere, modify freely, no restrictions.
