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
   │  code-  │ │  VoxFlow  │ │ghost│ │ spectra   │ │neural-│
   │  graph  │ │  Voice    │ │ OS  │ │  Gesture  │ │canvas │
   └─────────┘ └───────────┘ └─────┘ └───────────┘ └───────┘
        │            │           │           │            │
   ┌────┴────┐ ┌─────┴─────┐ ┌──┴──┐ ┌─────┴─────┐ ┌───┴───┐
   │nakshatra│ │ flowpipe  │ │debug│ │  codahub  │ │supply-│
   │  Graph  │ │ Pipeline  │ │lens │ │ Registry  │ │ chain │
   └─────────┘ └───────────┘ └─────┘ └───────────┘ └───────┘
```

## Projects

### Core

| Project | What It Does | Lines |
|---------|-------------|-------|
| [**codegraph**](../codegraph) | Interactive 3D codebase knowledge graph — navigate code like star constellations | ~1,600 |
| [**VoxFlow**](../VoxFlow) | Local-first voice pipeline — no cloud, no API keys, just your voice | ~2,100 |
| [**ghostos**](../ghostos) | Local AI operating system — the life force of your device | ~3,400 |
| [**spectra**](../spectra) | Gesture recognition engine — sees what you mean before you touch | ~2,500 |
| [**nakshatra**](../nakshatra) | 3D codebase graph — maps your code like star constellations | ~1,400 |

### Infrastructure

| Project | What It Does | Lines |
|---------|-------------|-------|
| [**flowpipe**](../flowpipe) | Visual pipeline builder — drag-and-drop workflow execution | ~1,700 |
| [**codahub**](../codahub) | Local service registry — discover and health-check your services | ~1,200 |
| [**neural-canvas**](../neural-canvas) | AI sketch-to-3D — draw a sketch, get a 3D model | ~1,500 |
| [**debuglens**](../debuglens) | Visual code debugger — paste an error, see the fix | ~1,300 |
| [**supplychain**](../supplychain) | Supply chain security — scan dependencies for vulnerabilities | ~1,350 |

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
git clone https://github.com/Sachitt-AV-08/COSMIC.git

# Or install individual projects
pip install fastapi uvicorn numpy
```

Each project is independently installable. See individual READMEs for details.

## Philosophy

- **Local-first** — No cloud. No API keys. Your hardware, your data.
- **Composable** — Each project works standalone. Combine them for more power.
- **Beautiful** — Dark cosmic theme across all projects. Glowing nodes. Particle effects. Clean UI.
- **Functional** — Real code, not stubs. Every project runs and does something useful.

## Built By

**A.V. Sachitt** — [GitHub](https://github.com/Sachitt-AV-08)

Part of the [CODA](https://github.com/Sachitt-AV-08) ecosystem.

## License

MIT — use anywhere, modify freely, no restrictions.
