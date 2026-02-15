# Tech stack (target)

## Engine
- **Unity 6 / 6000 LTS**

## Rendering
- **URP**
- Post effects: bloom, grain, vignette (subtle), chromatic aberration (light touch)

## UI
- **UI Toolkit** for layout + USS styling (treat as a design system)
- **TextMeshPro** for mono/OCR fonts and crisp glyph control

## Visual FX
- **Shader Graph**: CRT scanlines, distortion, glitch frames, phosphor persistence/fade

## Simulation performance path
- Start with straightforward C# architecture (data-driven + testable)
- Graduate to **DOTS** (ECS/Jobs/Burst) where scale demands it

## Animation / motion
- DOTween (or equivalent) for typewriter, flicker, micro-pulses

## Notes
Versions for URP/UI Toolkit packages should be selected to match the chosen Unity 6000 LTS editor version.
