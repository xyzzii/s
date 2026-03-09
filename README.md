# Differential Equation Solver

**Key features:**
- Solves first-order ODEs: dy/dt = f(y, t) using Euler's method
- Interactive graph with pan/zoom capabilities
- Real-time parameter adjustment
- Preset equations for exploration

## How It Works

**Math Engine:**
- Parses text equations into JavaScript functions
- Uses Euler's method to numerically solve dy/dt = f(y,t)
- Solves both forward and backward from the initial condition

**Interactive Features:**
1. **Click** on the graph to set a new initial condition
2. **Drag** to pan the viewport
3. **Scroll** to zoom in/out centered on cursor
4. **Presets dropdown** for common equations to explore

**Design Choices:**
- System fonts only (`system-ui` + monospace for math)
- Pure CSS variables that switch with `prefers-color-scheme`
- No external dependencies - completely self-contained
- Minimalist black/white aesthetic with intentional use of space
- Respects `prefers-reduced-motion` for accessibility
