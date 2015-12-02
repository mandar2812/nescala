### Nescala

A NES emulator written in Scala.

### How to run

    ~ sbt run 

### Controls

Joysticks are supported, although the button mapping is currently hard-coded.
Keyboard controls are:

| Nintendo              | Emulator    |
| --------------------- | ----------- |
| Up, Down, Left, Right | Arrow Keys  |
| Start                 | Enter       |
| Select                | Right Shift |
| A                     | Z           |
| B                     | X           |
| A (Turbo)             | A           |
| B (Turbo)             | S           |

### Mappers

The following mappers have been implemented:

* NROM (0)
* MMC1 (1)
* UNROM (2)
* CNROM (3)
* MMC3 (4)

### Known Issues

* PPU freeze on drawing above screen height
* Controller can crash when button mashing
* APU emulation needs attention in regards to timing and DMA 
