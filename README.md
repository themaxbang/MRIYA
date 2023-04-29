# MRIYA
**MRIYA** (Ukrainian for «Dream») is a 42-key column-staggered split keyboard based on [Corne Cherry v.3.0.1](https://github.com/foostan/crkbd)

[![MRIYA](https://i.imgur.com/i5s8GfO.jpg)](https://i.imgur.com/i5s8GfO.jpg)

## Features
- Design optimized for wireless
- Updated thumb cluster (inspired by [jian](https://github.com/KGOH/Jian-Info))
- Reset buttons
- Native nice!view support
- Updated pinky stagger
- No LEDs
- Hot-swap MX
- QMK/ZMK support

## Possible issues
- Controllers longer than 35mm (ProMicro from AliExpress) will stick out from the cover
- Required thickness for the bottom fr4 plate at least 1.6mm because of construction specifics (only 4 mounting points)
- Limited keycap compatibility (e.g. MT3 ortho sets) because of the 1.25u thumb keys

## PCB
[Kicad 7.0.2 Stable](https://www.kicad.org/)

**Silkscreen font:** [Roboto](https://fonts.google.com/specimen/Roboto) / [Roboto condensed](https://fonts.google.com/specimen/Roboto+Condensed)

 Left | Right    
 ---- | -----  
![](https://github.com/themaxbang/MRIYA/blob/main/renders/mriya-pcb-left-top.jpeg)|![](https://github.com/themaxbang/MRIYA/blob/main/renders/mriya-pcb-right-top.jpeg)     
![](https://github.com/themaxbang/MRIYA/blob/main/renders/mriya-pcb-left-back.jpeg)|![](https://github.com/themaxbang/MRIYA/blob/main/renders/mriya-pcb-right-back.jpeg)   

## PCB Plates
Top | Bottom    
 ---- | -----  
![](https://github.com/themaxbang/MRIYA/blob/main/renders/mriya-top-plate.jpeg)|![](https://github.com/themaxbang/MRIYA/blob/main/renders/mriya-bottom-plate.jpeg)   

## BOM
work in progress..
|Reference|Name|Qty|LCSC|AliExpess
 ------- | ------- | ------- | ------- | ------- 
U1, U2 | Microcontroller ProMicro | 2 | --- | ---
SW1-SW42 | Kailh Hotswap Socket | 42 | --- | ---
D1-D42 | Diode 1N4148W (SOT-123) | 42 | --- | ---
PSW1, PSW2 | Power Switch | 2 | --- | ---


## Inspired by
- [corne](https://github.com/foostan/crkbd)
- [cantor](https://github.com/diepala/cantor)
- [jian](https://github.com/KGOH/Jian-Info)
- [chocofi](https://github.com/pashutk/chocofi) / [fifi](https://github.com/raychengy/fifi_split_keeb)
- [slice36](https://github.com/MReavley/Slice36)
