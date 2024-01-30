## Work in progress.. Updates coming soon
# MRIYA
**MRIYA** (Ukrainian for «Dream») is a 42-key column-staggered split keyboard based on [Corne Cherry v.3.0.1](https://github.com/foostan/crkbd)

[![MRIYA](https://github.com/themaxbang/MRIYA/blob/main/pictures/mriya.jpeg)](https://github.com/themaxbang/MRIYA/blob/main/pictures/mriya.jpeg)

## Features
- Design optimized for wireless
- Updated thumb cluster (inspired by [jian](https://github.com/KGOH/Jian-Info))
- Reset buttons
- Native nice!view support
- Updated column stagger
- No LEDs
- Hot-swap MX
- ZMK support

## PCB
[Kicad 7.0.2 Stable](https://www.kicad.org/)

**Silkscreen font:** [Roboto](https://fonts.google.com/specimen/Roboto) / [Roboto condensed](https://fonts.google.com/specimen/Roboto+Condensed)

**PCB Art:** Olga Rai [[Shutterstock](https://www.shutterstock.com/g/OlgaRai) | [Adobe Stock](https://stock.adobe.com/contributor/209778624/olga-rai)]

#### Top
![](https://github.com/themaxbang/MRIYA/blob/main/renders/mriya-pcb-left-top.png)|![](https://github.com/themaxbang/MRIYA/blob/main/renders/mriya-pcb-right-top.png) 
 ---- | -----  

#### Bottom
![](https://github.com/themaxbang/MRIYA/blob/main/renders/mriya-pcb-right-bottom.png)|![](https://github.com/themaxbang/MRIYA/blob/main/renders/mriya-pcb-left-bottom.png)   
 ---- | -----  

## PCB Plates
Top | Bottom    
 ---- | -----  
![](https://github.com/themaxbang/MRIYA/blob/main/renders/mriya-top-plate.png)|![](https://github.com/themaxbang/MRIYA/blob/main/renders/mriya-bottom-plate.png)   

## BOM
Reference|Name|Qty|LCSC|AliExpess
 ------- | ------- | ------- | ------- | ------- 
U1, U2 | Microcontroller nRFMicro / SuperMini / nice!nano | 2 | --- | [AliExpress]()
SW1-SW42 | Kailh Hotswap Socket | 42 | [LCSC](https://www.lcsc.com/product-detail/Mechanical-Keyboard-Shaft_span-style-background-color-ff0-Kailh-span-CPG151101S11-16_C5156480.html) | [AliExpress]()
D1-D42 | Diode 1N4148W (SOD-123) | 42 | [LCSC](https://www.lcsc.com/product-detail/Diodes-General-Purpose_RealChip-1N4148W_C5443965.html) | [AliExpress]()
PSW1, PSW2 | Power Switch SSSS811101 / MSK-12C01-07 | 2 | [LCSC](https://www.lcsc.com/product-detail/Slide-Switches_ALPSALPINE-SSSS811101_C109335.html) | [AliExpress]()
RSW1, RSW2 | Reset Button TC-1109-C-A (4.5x4.5x**5.5**mm) 4pin DIP | 2 | [LCSC](https://www.lcsc.com/product-detail/Tactile-Switches_XKB-Connectivity-TC-1109-C-A_C561500.html) | [AliExpress]()
J1, J2 | Nice!View Display (optional) | 2 | --- | ---
J3, J4 | Audio connector DIP PJ-320A | 2 | [LCSC](https://www.lcsc.com/product-detail/Audio-Connectors_XKB-Connectivity-PJ-320A_C2884926.html) | [AliExpress]()
--- | Socket PH5 12pin (Female headers) pitch 2.54mm | 4 | --- | [AliExpress]()
--- | Socket PH5 5pin (Female headers) pitch 2.54mm | 2 | --- | [AliExpress]()
--- | LiPo Battery 301230 | 2 | --- | [AliExpress]()
--- | Silicone Bumpers 10x2mm | 12 | --- | [AliExpress]()
--- | Round Aluminum Standoff M2 (for MCU cover) 8mm | 6 | --- | [AliExpress]()
--- | Brass Round Standoff Spacer Female M2 7mm | 8 | --- | [AliExpress]()
--- | Screw M2 4mm | 28 | --- | [AliExpress]()

## Firmware
You can use any firmware compatible with the Corne keyboard.
[ZMK Config](https://github.com/themaxbang/mriya-zmk-config) for the MRIYA

## Inspiration
- [corne](https://github.com/foostan/crkbd)
- [cantor](https://github.com/diepala/cantor)
- [jian](https://github.com/KGOH/Jian-Info)
- [chocofi](https://github.com/pashutk/chocofi) / [fifi](https://github.com/raychengy/fifi_split_keeb)
- [slice36](https://github.com/MReavley/Slice36)
