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

See [ARCHITECTURE.md](ARCHITECTURE.md) for the full semantic layering and connected graph.

```
                         ┌──────────────┐
                         │     USER     │
                         └──────┬───────┘
                                │
               ┌────────────────┼────────────────┐
               │                │                │
         ┌─────┴─────┐   ┌─────┴─────┐   ┌─────┴─────┐
         │  Cosmic   │   │  Cosmic   │   │  Cosmic   │
         │  Voice    │   │  Vision   │   │  Explore  │
         │  Speak    │   │  Gesture  │   │  Navigate │
         └─────┬─────┘   └─────┬─────┘   └─────┬─────┘
               └────────────────┼────────────────┘
                                │
                         ┌──────┴───────┐
                         │ Cosmic Core  │
                         │   (AI OS)    │
                         └──────┬───────┘
                                │
          ┌─────────────────────┼─────────────────────┐
          │                     │                     │
   ┌──────┴──────┐      ┌──────┴──────┐      ┌──────┴──────┐
   │  Cosmic     │      │  Cosmic     │      │  Cosmic     │
   │  Flow       │      │  Connect    │      │  Debug      │
   │  Pipelines  │      │  Services   │      │  Errors     │
   └──────┬──────┘      └──────┬──────┘      └──────┬──────┘
          └─────────────────────┼─────────────────────┘
                                │
                    ┌───────────┼───────────┐
                    │                       │
             ┌──────┴──────┐         ┌──────┴──────┐
             │  Cosmic     │         │  Cosmic     │
             │  Atlas      │         │  Shield     │
             │  Code Map   │         │  Security   │
             └─────────────┘         └─────────────┘
```

## Projects

### Experience Layer — How You Interact

| Project | What It Does | Lines |
|---------|-------------|-------|
| [**Cosmic Explore**](https://github.com/Sachitt-AV-08/Cosmic%20Explore) | Navigate code by meaning, not folders | ~1,600 |
| [**Cosmic Voice**](https://github.com/Sachitt-AV-08/Cosmic%20Voice) | Local-first voice — no cloud, no API keys | ~2,100 |
| [**Cosmic Vision**](https://github.com/Sachitt-AV-08/Cosmic%20Vision) | Gesture control — hands, body, face | ~2,500 |
| [**Cosmic Canvas**](https://github.com/Sachitt-AV-08/Cosmic%20Canvas) | Draw a sketch, get a 3D model | ~1,500 |

### Intelligence Layer — The Brain

| Project | What It Does | Lines |
|---------|-------------|-------|
| [**Cosmic Core**](https://github.com/Sachitt-AV-08/Cosmic%20Core) | AI operating system — agents, memory, tools, automation | ~3,400 |

### Orchestration Layer — Connecting Things

| Project | What It Does | Lines |
|---------|-------------|-------|
| [**Cosmic Flow**](https://github.com/Sachitt-AV-08/Cosmic%20Flow) | Visual pipeline builder — drag, drop, execute | ~1,700 |
| [**Cosmic Connect**](https://github.com/Sachitt-AV-08/Cosmic%20Connect) | Service registry — discover & health-check | ~1,200 |
| [**Cosmic Debug**](https://github.com/Sachitt-AV-08/Cosmic%20Debug) | Visual debugger — paste error, see the fix | ~1,300 |
| [**Cosmic Atlas**](https://github.com/Sachitt-AV-08/Cosmic%20Atlas) | 3D codebase knowledge graph — map your code | ~1,400 |

### Security Layer — Protection

| Project | What It Does | Lines |
|---------|-------------|-------|
| [**Cosmic Shield**](https://github.com/Sachitt-AV-08/Cosmic%20Shield) | Supply chain security — scan deps, CVEs, SBOM | ~1,350 |

### Infrastructure — Developer Tools

| Project | What It Does |
|---------|-------------|
| [**neural**](https://github.com/Sachitt-AV-08/neural) | Unified CLI for local + cloud LLMs |
| [**envcheck**](https://github.com/Sachitt-AV-08/envcheck) | Environment variable validator |
| [**patchwork**](https://github.com/Sachitt-AV-08/patchwork) | Config file patcher |
| [**servehere**](https://github.com/Sachitt-AV-08/servehere) | Instant file server with QR code |
| [**modelview**](https://github.com/Sachitt-AV-08/modelview) | 3D model viewer (GLB/OBJ/STL) |
| [**imagediff**](https://github.com/Sachitt-AV-08/imagediff) | Before/after image comparison |
| [**picgrid**](https://github.com/Sachitt-AV-08/picgrid) | Image grid comparator |
| [**pixelflow**](https://github.com/Sachitt-AV-08/pixelflow) | Terminal image toolbox |

## Quick Start

```bash
# Clone the ecosystem
git clone https://github.com/Sachitt-AV-08/COSMIC.git

# Or install individual projects
pip install fastapi uvicorn numpy
```

Each project is independently installable. See individual READMEs for details.

## Philosophy

- **Local-first** — No cloud. No API keys. Your hardware, your data.
- **Composable** — Each project works standalone. Combine them for more power.
- **Layered** — Infrastructure → Security → Orchestration → Intelligence → Experience.
- **Connected** — Every component can talk to every other component.
- **Beautiful** — Dark cosmic theme. Glowing nodes. Clean UI across all projects.
- **Functional** — Real code, not stubs. Every project runs and does something useful.

## Built By

**A.V. Sachitt** — [GitHub](https://github.com/Sachitt-AV-08)

Part of the [CODA](https://github.com/Sachitt-AV-08) ecosystem.

## License

MIT — use anywhere, modify freely, no restrictions.
