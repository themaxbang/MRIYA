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
U1, U2 | Microcontroller ProMicro | 2 | --- | [AliExpress](https://aliexpress.ru/item/1005004242820623.html?sku_id=12000028500661497&spm=a2g2w.productlist.search_results.17.53474aa6zfoJcj)
SW1-SW42 | Kailh Hotswap Socket | 42 | [LCSC](https://www.lcsc.com/product-detail/Mechanical-Keyboard-Shaft_span-style-background-color-ff0-Kailh-span-CPG151101S11-16_C5156480.html) | [AliExpress](https://aliexpress.ru/item/1005003873653184.html?spm=a2g2w.orderdetail.0.0.3e484aa6uTmLrs&sku_id=12000031057687324)
D1-D42 | Diode 1N4148W (SOD-123) | 42 | [LCSC](https://www.lcsc.com/product-detail/Diodes-General-Purpose_RealChip-1N4148W_C5443965.html) | [AliExpress](https://aliexpress.ru/item/32354597825.html?sku_id=58815690427&spm=a2g2w.productlist.search_results.0.18174aa6pNF4Nj)
PSW1, PSW2 | Power Switch SSSS811101 | 2 | [LCSC](https://www.lcsc.com/product-detail/Slide-Switches_ALPSALPINE-SSSS811101_C109335.html) | [AliExpress](https://aliexpress.ru/item/1005002925147725.html?spm=a2g2w.orderdetail.0.0.398b4aa6ZWxzok&sku_id=12000022829402177)
RSW1, RSW2 | Reset Switch TC-1109-C-A (4.5x4.5x**5.5**mm) | 2 | [LCSC](https://www.lcsc.com/product-detail/Tactile-Switches_XKB-Connectivity-TC-1109-C-A_C561500.html) | [AliExpress](https://aliexpress.ru/item/1005001629344310.html?spm=a2g2w.orderdetail.0.0.71e54aa6nRE0h1&sku_id=12000016890022339)
J1, J2 | Nice!View Display | 2 | --- | ---
J3, J4 | Audio connector DIP PJ-320A | 2 | [LCSC](https://www.lcsc.com/product-detail/Audio-Connectors_XKB-Connectivity-PJ-320A_C2884926.html) | [AliExpress](https://aliexpress.ru/item/4000661212458.html?sku_id=10000005518588253&spm=a2g2w.productlist.search_results.3.61834aa6M9b3i4)
--- | --- | --- | --- | ---
--- | --- | --- | --- | ---
--- | --- | --- | --- | ---
--- | --- | --- | --- | ---
--- | --- | --- | --- | ---
--- | --- | --- | --- | ---

## Inspired by
- [corne](https://github.com/foostan/crkbd)
- [cantor](https://github.com/diepala/cantor)
- [jian](https://github.com/KGOH/Jian-Info)
- [chocofi](https://github.com/pashutk/chocofi) / [fifi](https://github.com/raychengy/fifi_split_keeb)
- [slice36](https://github.com/MReavley/Slice36)
