# Unity setup (placeholder)

This repo includes a `UnityProject/` folder as a placeholder project root.

## Create the project
1. Open **Unity Hub**
2. Add/Open project at: `./UnityProject`
3. Select **Unity 6 / 6000 LTS** (exact patch version TBD)

## Configure (targets)
- Install/enable **URP**
- Set up post-processing (subtle bloom/grain/vignette)
- Use **UI Toolkit** + USS as the core UI system
- Add CRT/scanline/persistence shaders via Shader Graph

## First prototype goal
Build one canonical screen:
- **City Diagnostics Terminal** (resource bars + graphs + alert banner)

Once the canonical screen feels right, derive all other panels from the same tokens/components.
