# XBot CAD

CAD models of XBot, a hybrid leg-wheel quadruped robot with four legs and a
rectangular chassis (700 x 500 mm).

## Contents

| Folder        | Format          | Use                                  |
|---------------|-----------------|--------------------------------------|
| `STEP/`       | STEP AP214      | Exchange format, any CAD software    |
| `STL/`        | STL             | 3D printing                          |
| `Solidworks/` | SLDPRT          | Native SolidWorks files              |
| `urdf/`       | URDF + meshes   | Robot description                    |

## Parts

- **Top joint** (`assembly top joint`, `assembly top joint mirror`)
- **Bottom joint** (`assembly bot_joint`, `assembly bot_joint mirror`)
- **Top leg** (`assembly top leg`, `assembly top leg mirror`)
- **Top assembly** (`Assembly top`, `Assembly top mirror`)
- **Wheel** (`Assembly wheel`, `WHEEL`)
- **Lid** (`tampo v1`)

The `mirror` versions are the mirrored counterparts used on the opposite side
of the robot.

## License

CC-BY-4.0 (https://creativecommons.org/licenses/by/4.0/)
