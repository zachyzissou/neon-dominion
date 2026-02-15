# Architecture (placeholder)

This will evolve once the Unity project is generated.

## Target structure (high level)
- **Simulation**
  - Time step + determinism strategy
  - Economy/resources
  - Citizens/agents (optional early)
  - Utilities (power/water/data)
- **Governance**
  - Edicts/policies as data-driven modifiers
  - City "state" (laws, surveillance, morale)
- **Expeditions**
  - POI definitions
  - Mission state machine + outcomes
  - Narrative card system
- **Presentation**
  - UI Toolkit design system (tokens/components)
  - Map rendering + overlays
- **Persistence**
  - Save/load format (TBD)

## Guiding constraints
- Data-driven first.
- Keep subsystems testable and observable.
- Optimize with DOTS only after design stabilizes.
