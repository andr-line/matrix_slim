# Matrix Slim

> Attention: This keyboard is in developement and the pcb is not yet functional.
> 
> The description below describes a future version of the keyboard, at the moment it is the circuitry of a nice!nano and the antenna matching circuit is not functional yet.

> The project is currently on hold so I can focus on Uni, at least until summer 2025.

This is the successor to my original Matrix keyboard, which was far from perfect. It aims to be as compact as possible while still providing enough keys to not have to re-learn to type. Using the new surface mounted kailh CPG1316M01D02 and the corresponding slim CPG1316S01D02 switches the size was able to be reduced to just [INSERT SIZE HERE] cm by [INSERT THICKNESS HERE] mm. This version also introduces column stagger for more comfort, especially for the little finger.

## Design remarks
Since stacking controller (nice!nano or seeduino) and battery vertically would increase the thickness, I decided to implement the seeduino xiao ble directly in the pcb (by copying their design). This results in the circuitry being very compact and allows for the addition of a e-ink display on top of the battery. (Alternatively more keys or different accessories could be added). Note that this is my first pcb with a microchip and there could be errors / bad design.

## Incomplete:

- [ ] New iteration using copied seeduino xiao ble instead of nice!nano
- [ ] Use NRF52840-CKAA-R footprint for compactness
- [ ] Use new free space for battery and maybe display (Chip should be entirely in old thumbcluster)

## Potential additions:

- [ ] Display
- [ ] Trackpoint
