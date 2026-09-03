# Ghost // Minimal

A high-performance, minimalist utility designed for low-level execution environments (Low sUNC / Lua 5.1). Features an ultra-compact, zero-corner geometric interface delivering FilteringEnabled invisibility and variable-speed directional flight mechanics.

<p align="center">
  <img width="322" height="202" alt="Ghost Minimal Interface Preview" src="https://github.com/user-attachments/assets/e878da6c-7184-4e51-af96-810aa35c403f" />
</p>

---

### Compatibility Disclaimer

Optimized natively for standard low-sUNC environments (e.g., Solara). Functionality and execution stability across untested or alternative executors are not guaranteed.

---

### Core Mechanics

- **Trans Ghost (FE Invisible):** Front-End safe replication bypass that shifts the player into a ghost state, desyncing server-side visibility while maintaining client-side physics and control.
- **Winding Ghost (Flight):** Camera-oriented directional flight system bound to WASD, Space, and Left Shift.
- **Dynamic Speed Calibration:** Integrated geometric slider allowing instantaneous flight velocity adjustments from 10 to 200 units.
- **Geometric Minimal UI:** Strict zero-corner architecture with high-contrast slate aesthetics, collapsible icon minimization, and amplified feedback sound events.

---

### Execution

Execute the utility directly in your client environment:

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_REPO/main/source.lua"))()
