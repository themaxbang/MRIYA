## Work in progress.. testing the release version

# MRIYA
**MRIYA** (Ukrainian for «Dream») is a 42-key column-staggered split keyboard based on [Corne Cherry v.3.0.1](https://github.com/foostan/crkbd)

[![MRIYA](https://github.com/themaxbang/MRIYA/blob/main/pictures/mriya.jpeg)](https://github.com/themaxbang/MRIYA/blob/main/pictures/mriya.jpeg)

## Features
- Design optimized for wireless
- Updated thumb cluster (inspired by [Jian](https://github.com/KGOH/Jian-Info))
- Reset buttons
- Native nice!view support
- Updated column stagger
- 3DP bumper case (inspired by [Dao Choc BLE](https://github.com/yumagulovrn/dao-choc-ble))
- CNC plates
- BSI-10H Slide Switches
- Molex PicoBlade 1.25mm connectors
- LiPo Battery 301230/301645 support
- No-Solder Spring Headers support
- No LEDs
- Hotswap MX
- ZMK support

## PCB
<table align="center">
    <tr>
        <td align="left">Software</td>
        <td align="left"><a href="https://www.kicad.org/">KiCad 8.0.9 Stable</a></td>
    </tr>
    <tr>
        <td align="left">Silkscreen font</td>
        <td align="left"><a href="https://fonts.google.com/specimen/Roboto">Roboto</a> | <a href="https://fonts.google.com/specimen/Roboto+Condensed">Roboto condensed</a></td>
    </tr>
    <tr>
        <td align="left">Bird logo</td>
        <td align="left"><a href="https://pngtree.com/freepng/minimalist-bird-logo_4124682.html">pngtree.com</a></td>
    </tr>
    <tr>
        <td align="left">PCB Art</td>
        <td align="left"> Olga Rai <a href="https://www.shutterstock.com/g/OlgaRai">Shutterstock</a> | <a href="https://stock.adobe.com/contributor/209778624/olga-rai">Adobe Stock</a></td>
    </tr>
</table>

#### <div align="center">Top<div>
![](https://github.com/themaxbang/MRIYA/blob/main/renders/mriya-pcb-left-top.png)|![](https://github.com/themaxbang/MRIYA/blob/main/renders/mriya-pcb-right-top.png) 
 ---- | -----  

#### <div align="center">Bottom<div>
![](https://github.com/themaxbang/MRIYA/blob/main/renders/mriya-pcb-right-bottom.png)|![](https://github.com/themaxbang/MRIYA/blob/main/renders/mriya-pcb-left-bottom.png)   
 ---- | -----  

## PCB Plates
<table align="center">
    <tr>
        <td align="left">Logo font</td>
        <td align="left"><a href="https://fontbundles.net/integritype-studio/1610789-william-narasi-calligraphy-font">William Narasi</a></td>
    </tr>
</table>

![](https://github.com/themaxbang/MRIYA/blob/main/renders/mriya-top-plate.png)|![](https://github.com/themaxbang/MRIYA/blob/main/renders/mriya-bottom-plate.png)   
 ---- | -----

## 3D Printed Bumper Case
#### <div align="center">SLA (Black Resin)<div>
![](https://github.com/themaxbang/MRIYA/blob/main/renders/mriya-bumper-case-SLA-01.png)|![](https://github.com/themaxbang/MRIYA/blob/main/renders/mriya-bumper-case-SLA-02.png)
 ---- | -----

#### <div align="center">FDM<div>
![](https://github.com/themaxbang/MRIYA/blob/main/renders/mriya-bumper-case-FDM-01.png)|![](https://github.com/themaxbang/MRIYA/blob/main/renders/mriya-bumper-case-FDM-02.png)
 ---- | -----

## BOM
Reference|Name|Qty|LCSC|AliExpess
 ------- | ------- | ------- | ------- | ------- 
U1, U2 | Microcontroller: [nRFMicro](https://github.com/joric/nrfmicro) / SuperMini nRF52840 / nice!nano | 2 | --- | [AliExpress](https://aliexpress.com/item/1005006282506884.html?sku_id=12000036599296319)
SW1-SW42 | Kailh Hotswap Socket CPG151101S11 | 42 | [LCSC](https://www.lcsc.com/product-detail/Mechanical-Keyboard-Shaft_span-style-background-color-ff0-Kailh-span-CPG151101S11-16_C5156480.html) | [AliExpress](https://aliexpress.com/item/1005007639688349.html?sku_id=12000041605806628)
D1-D42 | Diode 1N4148W (SOD-123) | 42 | [LCSC](https://www.lcsc.com/product-detail/Switching-Diodes_JSMSEMI-1N4148W_C917030.html) | [AliExpess](https://aliexpress.com/item/1005008224039255.html?sku_id=12000044288109815)
PSW1, PSW2 | Power Switch SUNGMUN BSI-10H | 2 | [LCSC](https://www.lcsc.com/product-detail/Slide-Switches_SM-Switch-BSI-10H_C5775777.html) | [AliExpress](https://aliexpress.com/item/1005006561513178.html?sku_id=12000037678382032)
RSW1, RSW2 | Reset Button TC-1109-C-A (4.5x4.5x**5.5**mm) 4pin DIP | 2 | [LCSC](https://www.lcsc.com/product-detail/Tactile-Switches_XKB-Connectivity-TC-1109-C-A_C561500.html) | [AliExpress](https://aliexpress.com/item/1005001629344310.html?sku_id=12000016890022339)
J1, J2 | Display nice!view [optional] | 2 | --- | [AliExpess](https://aliexpress.com/item/1005007972384358.html?sku_id=12000043094547978)
J3, J4 | Molex PicoBlade 532610271 connector | 2 | [LCSC](https://www.lcsc.com/product-detail/Wire-To-Board-Wire-To-Wire-Connector_MOLEX-532610271_C189700.html) | [AliExpress](https://aliexpress.com/item/1005004425197503.html?sku_id=12000029142536237)
--- | Socket PH5 12pin (Female header) pitch 2.54mm | 4 | --- | [AliExpress](https://aliexpress.com/item/1005006055026707.html?sku_id=12000037525939024)
--- | Socket PH5 5pin (Female header) pitch 2.54mm | 2 | --- | [AliExpress](https://aliexpress.com/item/1005006055026707.html?sku_id=12000037525939018)
--- | LiPo Battery 301230 | 2 | --- | [AliExpress](https://aliexpress.ru/item/1005008151618452.html?sku_id=12000044007992383)
--- | LiPo Battery 301645 [optional] | 2 | --- | [AliExpress](https://aliexpress.com/item/32822552643.html?sku_id=64950436890)
--- | Jst Connector 1.25mm Dual Head Wire Cable 2 Pin Female Plug [optional] | 2 | --- | [AliExpress](https://aliexpress.com/item/1005006000774395.html?sku_id=12000035250620558)
--- | Silicone Bumpers 8x2mm (for Classic case or CNC plates) | 12 | --- | [AliExpress](https://aliexpress.com/item/1005005467943079.html?sku_id=12000033199265741)
--- | Silicone Bumpers 8x1.5mm (for FR4 bottom plates) | 12 | --- | [AliExpress](https://aliexpress.com/item/1005002478823169.html?sku_id=12000038015770755)
--- | Brass Round Standoff Spacer Female M2 10mm | 4 | --- | [AliExpress](https://aliexpress.com/item/1005002979083511.html?sku_id=12000023043529034)
--- | Brass Round Standoff Spacer Female M2 7mm | 8 | --- | [AliExpress](https://aliexpress.com/item/1005002979083511.html?sku_id=12000023043529031)
--- | M3 ABS Nylon Round Standoff Spacer 3.5mm | 12 | --- | [AliExpress](https://aliexpress.com/item/1005004162177818.html?sku_id=12000028239766646)
--- | M3 Black ABS Non-Threaded Hollowed Nylon Spacer 5mm | 4 | --- | [AliExpress](https://aliexpress.com/item/1005006120526666.html?sku_id=12000035843885709)
--- | M2 Stainless Steel Torx Six-Lobe Ultra Thin Head Screw 4mm | 24 | --- | [AliExpress](https://aliexpress.com/item/1005002461101939.html?sku_id=12000025423430581)
--- | M2 Stainless Steel Torx Head Flat Countersunk Screw 8 mm (for Classic case + FDM plates) | 12 | --- | [AliExpress](https://aliexpress.com/item/1005007404555871.html?sku_id=12000040603875540)
--- | M2 Stainless Steel Torx Head Flat Countersunk Screw 5 mm (for Classic case + FR4 plates) | 12 | --- | [AliExpress](https://aliexpress.com/item/1005007404555871.html?sku_id=12000040603875538)
--- | M2 grade 12.9 Insert Torx Screw 5mm [optional] (for CNC covers) | 4 | --- | [AliExpress](https://aliexpress.com/item/1005005241011259.html?sku_id=12000032329870357)

## Firmware
You can use any firmware compatible with the Corne keyboard.
[ZMK Config](https://github.com/themaxbang/mriya-zmk-config) for the MRIYA

## Inspiration
- [Corne](https://github.com/foostan/crkbd) | [Corne Ultralight](https://github.com/petejohanson/crkbd/tree/board/corne-ultralight)
- [Jian](https://github.com/KGOH/Jian-Info)
- [Chocofi](https://github.com/pashutk/chocofi) | [Fifi](https://github.com/raychengy/fifi_split_keeb)
- [Dao Choc BLE](https://github.com/yumagulovrn/dao-choc-ble)
