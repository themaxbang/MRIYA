## Work in progress.. Updates coming soon
# MRIYA
**MRIYA** (Ukrainian for «Dream») is a 42-key column-staggered split keyboard based on [Corne Cherry v.3.0.1](https://github.com/foostan/crkbd)

[![MRIYA](https://github.com/themaxbang/MRIYA/blob/main/pictures/mriya.jpeg)](https://github.com/themaxbang/MRIYA/blob/main/pictures/mriya.jpeg)

## Features
- Design optimized for wireless
- Updated thumb cluster (inspired by [Jian](https://github.com/KGOH/Jian-Info))
- Reset buttons
- Native nice!view support
- Updated column stagger
- 3DP bumper cases (inspired by [Dao Choc BLE](https://github.com/yumagulovrn/dao-choc-ble))
- CNC plates
- BSI-10H Slide Switches
- Molex PicoBlade 1.25mm connectors
- No LEDs
- Hotswap MX
- ZMK support

## PCB
<table align="center">
    <tr>
        <td align="left">Software</td>
        <td align="left"><a href="https://www.kicad.org/">Kicad 7.0.11 Stable</a></td>
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

## Bumper case

![SLA](https://github.com/themaxbang/MRIYA/blob/main/renders/mriya-bumper-case.png)|![]()
 ---- | -----

## BOM
Reference|Name|Qty|LCSC|AliExpess
 ------- | ------- | ------- | ------- | ------- 
U1, U2 | Microcontroller: [nRFMicro](https://github.com/joric/nrfmicro) / SuperMini nRF52840 / nice!nano | 2 | --- | [AliExpress](https://aliexpress.com/item/1005007234033991.html?sku_id=12000039900820695&spm=a2g2w.productlist.search_results.7.5c956b946tHZyP)
SW1-SW42 | Kailh Hotswap Socket | 42 | [LCSC](https://www.lcsc.com/product-detail/Mechanical-Keyboard-Shaft_span-style-background-color-ff0-Kailh-span-CPG151101S11-16_C5156480.html) | [Ali]()
D1-D42 | Diode 1N4148W (SOD-123) | 42 | [LCSC](https://www.lcsc.com/product-detail/Diodes-General-Purpose_RealChip-1N4148W_C5443965.html) | [Ali]()
PSW1, PSW2 | Power Switch SUNGMUN BSI-10H | 2 | [LCSC](https://www.lcsc.com/product-detail/Slide-Switches_SUNGMUN-BSI-10H_C411270.html) | [Ali]()
RSW1, RSW2 | Reset Button TC-1109-C-A (4.5x4.5x**5.5**mm) 4pin DIP | 2 | [LCSC](https://www.lcsc.com/product-detail/Tactile-Switches_XKB-Connectivity-TC-1109-C-A_C561500.html) | [AliExpress](https://aliexpress.com/item/1005001629344310.html?spm=a2g2w.orderdetail.0.0.67d34aa6KalrlU&sku_id=12000016890022339)
J1, J2 | Display nice!view (optional) | 2 | --- | ---
J3, J4 | Molex PicoBlade 532610271 connector | 2 | [LCSC](https://www.lcsc.com/product-detail/Wire-To-Board-Wire-To-Wire-Connector_MOLEX-532610271_C189700.html) | [Ali]()
--- | Socket PH5 12pin (Female headers) pitch 2.54mm | 4 | --- | [Ali]()
--- | Socket PH5 5pin (Female headers) pitch 2.54mm | 2 | --- | [Ali]()
--- | LiPo Battery 301230 | 2 | --- | [Ali]()
--- | Silicone Bumpers 8x2mm | 12 | --- | [Ali]()
--- | 304 Stainless Steel Hex Standoff Spacer M2 (for MCU cover) 10mm | 4 | --- | [AliExpress](https://aliexpress.com/item/1005005442165195.html?spm=a2g2w.orderdetail.0.0.2d804aa6CZhJAg&sku_id=12000033098792235)
--- | Brass Round Standoff Spacer Female M2 7mm | 8 | --- | [Ali]()
--- | Screw M2 4mm | 28 | --- | [Ali]()

## Firmware
You can use any firmware compatible with the Corne keyboard.
[ZMK Config](https://github.com/themaxbang/mriya-zmk-config) for the MRIYA

## Inspiration
- [corne](https://github.com/foostan/crkbd)
- [cantor](https://github.com/diepala/cantor)
- [jian](https://github.com/KGOH/Jian-Info)
- [chocofi](https://github.com/pashutk/chocofi) / [fifi](https://github.com/raychengy/fifi_split_keeb)
- [slice36](https://github.com/MReavley/Slice36)

