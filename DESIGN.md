# Neon Dominion — Design Bible (v0)

This document captures the **aesthetic direction**, **visual language**, and **reference lineage** for *Neon Dominion*.

> Guiding principle: **Alien-style UI succeeds because it feels engineered, not designed.**

## 1) One-line identity
A city that hums like a dying hard drive—managed through cold, flickering terminals where *policy* and *entropy* are the main resources.

## 2) Creative direction
### Target feel
- **Industrial-diegetic**: interfaces feel like hardware embedded in the world, not modern overlays.
- **Retro-futurist realism**: 70s/80s limitations recreated digitally (downsample, persistence, bloom).
- **Corporate-brutalist**: functional minimalism, propaganda-adjacent copy, institutional scale.
- **Cyber-industrial (not glossy)**: neon exists, but it’s signage and spill—never “hologram UI couture.”

### Avoid
- Glossy translucent panels
- Over-neon rainbow palettes
- Hyper-smooth motion everywhere
- “UI-as-art” dashboards that don’t imply real circuitry

## 3) Reference lineage (primary)
- *Alien (1979)* — MU-TH-UR 6000 terminals; typographic and layout discipline
- *Alien: Isolation* — 70s tech constraints + interaction pacing (flicker/lag)
- *Blade Runner 2049* — corporate scale, light pollution, architectural mood
- *Prometheus* — clean-but-cold systems and telemetry framing
- *Europa Report* / *Moon* — pragmatic instrumentation and mission display language

### Reference archives
- HUDS+GUIS (archive): https://www.hudsandguis.com/archive
- Movie-Interfaces: https://movie-interfaces.com
- Typeset in the Future (typography analysis): https://typesetinthefuture.com
- Territory Studio (film UI work): https://territorystudio.com/work/
- Interface In Game (game UI stills): https://interfaceingame.com/
- Ash Thorp (ALT-C): https://www.altcinc.com/
- GMUNK: https://gmunk.com/

More: [`docs/references.md`](docs/references.md)

## 4) Visual language
### 4.1 Color
**Rule of thumb:** charcoal/black base + *one* dominant phosphor accent.

Suggested accents (pick per mode/faction):
- Phosphor green: `#00FF66`
- Amber: `#FFB400`
- Soft teal-blue: `#9EE6E6`

Supporting neutrals:
- Near-black: `#0B0D10`
- Charcoal: `#13161A`
- Steel: `#3B424A`
- Off-white text: `#D9D6D2`

### 4.2 Typography
Target families (license/availability TBD):
- OCR-A Extended
- Eurostile / Microgramma-like (extended)
- VT323 / Share Tech Mono (prototyping)

Rules:
- Prefer **ALL CAPS**, increased tracking, monospaced alignment where possible.
- Use strict hierarchy (Header / Label / Value / Alert).

### 4.3 Layout & shapes
- Modular grids; hard frames; clipped corners; occasional radial telemetry.
- Frames should imply manufacturing: bevels, bezels, screw heads, stamped IDs.
- Layers:
  1. Base: world/map
  2. Data overlays
  3. Terminals/diagnostics panels
  4. Critical alerts

### 4.4 Motion
- “Breathing systems”: micro-pulses, subtle persistence, burst updates.
- **Types in / flickers in / updates in bursts**; avoid modern easing everywhere.
- Suggested timings:
  - UI reveal: 0.2–0.4s
  - Active blink: 1–2 Hz
  - Glitch: 1–2 frames, randomized

### 4.5 Copywriting (system voice)
Machine syntax that reads like instrumentation:
- `POWER ROUTING: STABLE`
- `ATMOS PRESSURE: 0.97`
- `BIO-DOME BREACH DETECTED`

Short, institutional, and slightly threatening.

## 5) City aesthetics
### Macro layers
1. **Core / Spire districts** — brutalist towers, cold corporate light, ads in outdated resolutions.
2. **Mid-city habitats** — dense modular housing, exposed infrastructure, markets.
3. **Badlands** — half-functional ruins, collapsed transit, storm-scoured outskirts.

### Weather & atmosphere
- Perpetual dusk baseline; sodium fog; acid rain as a mood multiplier.
- Event ideas: blackouts (UI becomes primary light source), “data storms” (visual distortions).

## 6) UI component set (initial)
- Mission terminal (expeditions) — statuses: `IN TRANSIT`, `CONTACT LOST`, `EXTRACTION SUCCESSFUL`
- City diagnostics — ASCII bars/graphs for power/morale/crime
- Edict console — teletype decree output
- Crisis alerts — flashing border + sound cue (not pop-ups)
- Comms overlay — glitch waveforms / scrambled intercept text

## 7) Factions (aesthetic hooks)
Full writeup: [`docs/factions.md`](docs/factions.md)

- **Directorate**: black/chrome + amber; stamped identifiers; procedural language.
- **Syndics**: magenta accents; repurposed frames; anti-surveillance graffiti glyphs.
- **Archivists**: muted teal; cataloguing grids; “knowledge at any cost” tension.
- **Ordinators**: sterile whites; LED halos; synthetic voice and ritualized enforcement.

## 8) Sources used for reconstruction
Primary:
- Obsidian note: `Mind Map/Articles/AI/ImageGen/Best engine for city builder.md`

Secondary (tone/lore scaffolding for faction voice):
- `🔧 Projects/Bloom/Audio Scripts/ARC-01A_ArchivistIndex.md`
- `🔧 Projects/Bloom/Dialogue Templates/DIR_Directorate_Dialogues.md`
- `🔧 Projects/Bloom/Quest Templates/DIRECTORATE-Quests.md`

These are treated as **inspiration/structure**, not necessarily canonical.
