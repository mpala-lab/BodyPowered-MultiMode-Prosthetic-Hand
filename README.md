# BodyPowered-MultiMode-Prosthetic-Hand

Open-source CAD for a low-cost, body-powered prosthetic hand with a gear-based selective clutch that routes a single input cable to multiple functional modes. It accompanies our Humanoids 2026 paper, "Open-Source Body-Powered Prosthesis with a Selective Gear-Based Clutch Mechanism for Switching Grasp Types." This repository contains the CAD models for a body-powered, underactuated prosthetic hand featuring a gear-based selective clutch for discrete mechanical mode switching. 

<img width="1103" height="657" alt="body-powered_system" src="https://github.com/user-attachments/assets/56eba556-0def-4cfb-8066-6da465bd0b91" />

## Modes

A sliding gear selects one output at a time. Inactive outputs are locked by fixed sector gears.

- Finger flexion/extension (all fingers)
- Finger adduction/abduction (four fingers)
- Thumb opposition
- Neutral (rest)

## Key Specifications

| | |
|---|---|
| Input | Single body-powered cable |
| Differentials | Two whiffletrees |
| Hand mass | 331 g |
| Hardware cost | $138 (excluding filament and silicone) |
| Materials | PLA, PETG, cast silicone (Smooth-On Dragonskin 20) |

## Repository

- `Gear-Based Clutch Mechanism/`: clutch CAD. The full assembly is in `Shifting Gearbox V12.step`.
- `Underactuated Prosthetic Hand/`: hand CAD.

CAD was created in SolidWorks 2024. STEP files are provided for other CAD tools.

## Fabrication

Custom parts are FDM-printed in PLA or PETG, and fingerpads are cast in silicone using printed molds. All other parts (shafts, pins, fasteners, needle roller bearings) are off-the-shelf.

## Citation

```bibtex
@inproceedings{kontoudis2026bodypowered,
  title     = {Open-Source Body-Powered Prosthesis with a Selective Gear-Based Clutch Mechanism for Switching Grasp Types},
  author    = {Pacic, Evan and Jones, Remi and Paiz, Elijah and Kontoudis, George P. },
  booktitle = {IEEE-RAS International Conference on Humanoid Robots (Humanoids)},
  year      = {2026}
}
```

## License

[License](LICENSE.txt)
