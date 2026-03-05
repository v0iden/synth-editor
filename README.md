# Micro:bit Synth Preset Editor

Browser-based editor for [pxt-synth-v2](https://github.com/CaptainCredible/pxt-synth-v2) presets. Audio engine is an exact port of the C++ synth (oscillators, SVF filter, ADSR, FM, LFO) so what you hear matches the Micro:bit output.

**Live:** [v0iden.github.io/synth-editor](https://v0iden.github.io/synth-editor/)

## Features

- Real-time waveform preview
- Editable parameters with sliders and text input
- FL Studio-style QWERTY keyboard (Z–M = C3–B3, Q–I = C4–C5)
- Drag-to-play visual keyboard
- Copy preset string to clipboard

## Preset format

Presets use the same string format as the Micro:bit library:

```
{ OscType::Triangle, OscType::Pulse, 12.000000, 1.000000, ... , false }
```

Edit parameters in the GUI, then copy the output string into your MakeCode project.
