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
        <td align="left"><a href="https://www.kicad.org/">KiCad 7.0.11 Stable</a></td>
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
U1, U2 | Microcontroller: [nRFMicro](https://github.com/joric/nrfmicro) / SuperMini nRF52840 / nice!nano | 2 | --- | [AliExpress](https://aliexpress.com/item/1005007234033991.html?sku_id=12000039900820695&spm=a2g2w.productlist.search_results.7.5c956b946tHZyP)
SW1-SW42 | Kailh Hotswap Socket | 42 | [LCSC](https://www.lcsc.com/product-detail/Mechanical-Keyboard-Shaft_span-style-background-color-ff0-Kailh-span-CPG151101S11-16_C5156480.html) | [AliExpress](https://aliexpress.com/item/1005006262845453.html?sku_id=12000036517920676&spm=a2g2w.productlist.search_results.0.4fb06266Y1ZXxX)
D1-D42 | Diode 1N4148W (SOD-123) | 42 | [LCSC](https://www.lcsc.com/product-detail/Diodes-General-Purpose_RealChip-1N4148W_C5443965.html) | [AliExpess](https://aliexpress.com/item/1005005537832969.html?sku_id=12000033458494245&spm=a2g2w.productlist.search_results.5.6e951e06EKxRY6)
PSW1, PSW2 | Power Switch SUNGMUN BSI-10H | 2 | [LCSC](https://www.lcsc.com/product-detail/Slide-Switches_SUNGMUN-BSI-10H_C411270.html) | [AliExpress](https://aliexpress.com/item/1005006561513178.html?sku_id=12000037678382032&spm=a2g2w.productlist.search_results.10.44de5a4fSMMf80)
RSW1, RSW2 | Reset Button TC-1109-C-A (4.5x4.5x**5.5**mm) 4pin DIP | 2 | [LCSC](https://www.lcsc.com/product-detail/Tactile-Switches_XKB-Connectivity-TC-1109-C-A_C561500.html) | [AliExpress](https://aliexpress.com/item/1005001629344310.html?spm=a2g2w.orderdetail.0.0.67d34aa6KalrlU&sku_id=12000016890022339)
J1, J2 | Display nice!view [optional] | 2 | --- | [typeractive](https://typeractive.xyz/products/nice-view)
J3, J4 | Molex PicoBlade 532610271 connector | 2 | [LCSC](https://www.lcsc.com/product-detail/Wire-To-Board-Wire-To-Wire-Connector_MOLEX-532610271_C189700.html) | [AliExpress](https://aliexpress.com/item/1005004425197503.html?sku_id=12000029142536237&spm=a2g2w.productlist.search_results.1.62a247c6KjWDQ2)
--- | Socket PH5 12pin (Female header) pitch 2.54mm | 4 | --- | [Ali]()
--- | Socket PH5 5pin (Female header) pitch 2.54mm | 2 | --- | [Ali]()
--- | LiPo Battery 301230 | 2 | --- | [AliExpress](https://aliexpress.com/item/1005007211356412.html?sku_id=12000039821419568&spm=a2g2w.productlist.search_results.8.355678e0tXjjaI)
--- | LiPo Battery 301645 [optional] (No display support. You can install it above the microcontroller) | 2 | --- | [AliExpress](https://aliexpress.com/item/32822552643.html?spm=a2g2w.orderdetail.0.0.6b594aa68QZKt3&sku_id=64950436890)
--- | Silicone Bumpers 8x2mm | 12 | --- | [AliExpress](https://aliexpress.com/item/1005005467943079.html?spm=a2g2w.orderdetail.0.0.711a4aa6AFao3v&sku_id=12000033199265741)
--- | 304 Stainless Steel Hex Standoff Spacer M2 (for MCU cover) 10mm | 4 | --- | [AliExpress](https://aliexpress.com/item/1005005442165195.html?spm=a2g2w.orderdetail.0.0.2d804aa6CZhJAg&sku_id=12000033098792235)
--- | Brass Round Standoff Spacer Female M2 7mm | 8 | --- | [AliExpress](https://aliexpress.com/item/1005002979083511.html?spm=a2g2w.orderdetail.0.0.6aac4aa6dg8vSw&sku_id=12000023043529031)
--- | M2 A2 Stainless Steel Torx Six-Lobe Ultra Thin Head bolts 4mm | 24 | --- | [AliExpress](https://aliexpress.com/item/1005002461101939.html?spm=a2g2w.orderdetail.0.0.14244aa6K1bxTG&sku_id=12000025423430581)
--- | M2 grade 12.9 Insert Torx Screw 5mm [optional] (for CNC MCU cover) | 4 | --- | [AliExpress](https://aliexpress.com/item/1005005241011259.html?spm=a2g2w.orderdetail.0.0.615a4aa6uGGyDx&sku_id=12000032329870357)
--- | Jst Connector 1.25mm Dual Head Wire Cable 2 Pin Female Plug [optional] | 2 | --- | [AliExpress](https://aliexpress.com/item/1005006000774395.html?spm=a2g2w.orderdetail.0.0.196a4aa6zCJJ7L&sku_id=12000035250620566)

## Firmware
You can use any firmware compatible with the Corne keyboard.
[ZMK Config](https://github.com/themaxbang/mriya-zmk-config) for the MRIYA

## Inspiration
- [Corne](https://github.com/foostan/crkbd)
- [Jian](https://github.com/KGOH/Jian-Info)
- [Chocofi](https://github.com/pashutk/chocofi) / [Fifi](https://github.com/raychengy/fifi_split_keeb)
- [Dao Choc BLE](https://github.com/yumagulovrn/dao-choc-ble)
