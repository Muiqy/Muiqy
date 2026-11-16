# muiqy.lua

**Lua · GameSense / CS:GO · Learning project**

A small UI experiment by **Muiqy / Elivien** exploring animated text labels in the GameSense Lua environment.

## What I explored

- Parsing an inline animation tag to configure colors, speed and mode.
- Converting HEX color strings into RGBA values.
- Interpolating between colors with a progress value and a direction.
- Three animation approaches: a whole-label color transition, a per-character left-to-right gradient and a center-to-edge gradient.
- Wrapping `ui.new_label` and using a `paint` callback to advance animation state.

This is a learning prototype: an experiment in Lua, color and UI animation, with room for further refinement.

[← Back to my profile](https://github.com/Muiqy)
