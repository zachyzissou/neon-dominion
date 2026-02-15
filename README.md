# Neon Dominion

A retro-futurist **city builder / governance sim** with an expedition layer.

**Creative direction:** industrial, diegetic interfaces (CRT / phosphor terminals) and corporate-brutalist cityscapes—closer to *Alien* / *Blade Runner 2049* / *Prometheus* than glossy neon holograms.

This repo is the **reconstructed foundation** after a GitLab data-loss event. The original code is gone; the design documentation survived in an Obsidian vault and is preserved here for version control.

## Gameplay pillars
1. **City Simulation** — zoning/infrastructure/utilities + emergent district identity.
2. **Governance & Morality** — edicts and policy tradeoffs that reshape both systems *and* aesthetics.
3. **Expeditions (“Badlands”)** — external missions that return modifiers, discoveries, and narrative cards.

See: [`docs/gameplay-pillars.md`](docs/gameplay-pillars.md)

## Tech stack (target)
- **Unity 6 / 6000 LTS**
- **URP** (post FX: bloom/grain/vignette kept subtle)
- **UI Toolkit** (USS-styled modular UI) + **TextMeshPro** (mono/OCR fonts)
- **Shader Graph** (CRT/scanlines/glitch/persistence)
- **DOTS (optional / later)** for scale (ECS/Jobs/Burst) once mechanics stabilize

See: [`docs/tech-stack.md`](docs/tech-stack.md)

## Factions (initial concepts)
- **The Directorate** — corporate security/governance, order and quotas.
- **The Syndics** — street-level collectivists, anti-surveillance, subversion.
- **The Archivists** — technomonks of preservation; knowledge has a cost.
- **The Ordinators** — enforcement zealots with a quasi-religious AI aesthetic.

See: [`docs/factions.md`](docs/factions.md)

## Repo layout
- `DESIGN.md` — aesthetic bible + references + visual rules
- `docs/` — gameplay/tech/faction docs
- `UnityProject/` — placeholder Unity project structure (to be generated/filled by Unity Hub)

## Status
**Foundation / docs-first.** Next step is to stand up a clean Unity project, then prototype one canonical UI screen (Diagnostics/Terminal) to lock the visual system.

## Provenance
Primary source note in the Obsidian vault:
- `Mind Map/Articles/AI/ImageGen/Best engine for city builder.md`

(Additional lore templates in the vault informed faction tone and voice; see `DESIGN.md` for citations.)
