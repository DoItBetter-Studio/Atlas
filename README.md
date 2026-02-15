# Atlas

> Proprietary Software — DoItBetter Studio

**Atlas** is the world and spatial data engine powering the Glyphborn ecosystem.

Development began in August 2025 as part of DoItBetter Studio’s long-term effort to build a modular, deterministic game engine and editor suite.

---

## Overview

Atlas is responsible for:

- Tile and grid management
- World layout representation
- Spatial queries and coordinate systems
- Multi-floor world structuring
- Floor-based visibility coordination
- Map serialization and deserialization
- Deterministic world state handling

Atlas defines how space is structured, queried, and persisted within the engine.

It provides authoritative world data while remaining fully decoupled from rendering, audio, and gameplay systems.

---

## Architectural Role

The Glyphborn ecosystem is intentionally modular.

Atlas handles:

✔ World topology and structure  
✔ Coordinate systems and spatial reasoning  
✔ Floor-aware data organization  
✔ Deterministic world state  

Atlas does **not** handle:

✖ Rendering  
✖ Audio  
✖ Game rules or combat logic  
✖ Networking  
✖ UI  

This strict separation ensures architectural clarity, clean dependencies, and long-term maintainability.

Atlas is designed to remain engine-agnostic and free of presentation-layer concerns.

---

## Design Principles

Atlas follows the core engineering principles established by DoItBetter Studio:

- **Deterministic Behavior** — Identical inputs produce identical world states  
- **Engine-Agnostic Core Logic** — No rendering or framework coupling  
- **Strict Separation of Concerns** — Clear domain boundaries  
- **Modular Versioning** — Independent repository and release cycle  
- **Testability First** — Logic designed for isolated validation  

---

## Ecosystem Integration

Atlas integrates with:

- Echo — Audio systems  
- Mapper — World and content tooling  
- Glyphborn — Core runtime and gameplay systems  

Each component exists in its own repository to allow independent iteration, versioning, and long-term scalability.

---

## Project Status

Atlas is currently in active development.

The broader Glyphborn engine will eventually be rebranded and released as:

**Damascus — The Steel Editor Suite**

Until official release, this repository is publicly visible for transparency and portfolio purposes but is not open source.

---

## Ownership & License

Copyright © 2025–2026 DoItBetter Studio

All rights reserved.

This software and associated documentation are proprietary intellectual property of DoItBetter Studio.

No license is granted to use, copy, modify, distribute, sublicense, reverse engineer, or create derivative works without prior written permission.

DoItBetter Studio reserves the right to relicense this software under an open-source license upon official release.
