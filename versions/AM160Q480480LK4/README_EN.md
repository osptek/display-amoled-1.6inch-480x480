<p align="left"><img alt="OSPTEK" src="../../images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 1.6″ AMOLED Display 480×480 (AM160Q480480LK4)</h1>

<p align="center"><b>AMOLED module · MIPI · ST7802</b></p>

<p align="center"><a href="./README.md">简体中文</a> | English · <a href="../../README_EN.md">Family index</a></p>

<p align="center">
  <img alt="Interface: MIPI" src="https://img.shields.io/badge/Interface-MIPI-27AE60?style=flat-square" />
  <img alt="Driver: ST7802" src="https://img.shields.io/badge/Driver-ST7802-E7352C?style=flat-square" />
  <img alt="Touch: CST9220" src="https://img.shields.io/badge/Touch-CST9220-F39C12?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 1.6&quot; 480×480 AMOLED module product image" src="./images/product.png" width="640" /></p>

## Contents

- [Specifications](#specifications)
- [Resources](#resources)
- [Repository layout](#repository-layout)
- [Buy](#buy)
- [Support](#support)

---

## Specifications

| Item | Spec |
| ---- | ---- |
| Size | 1.6 inch |
| Type | AMOLED |
| Resolution | 480×480 |
| Outline | 55.00 x 55.00 mm |
| Active area | 39.12 x 39.12 mm |
| Interface | MIPI |
| Driver IC | ST7802 |
| Touch IC | CST9220 |

> Full outline, FPC definition, power, and timing follow the product datasheet / driver IC datasheet.

## Resources

| Category | File |
| ---- | ---- |
| Datasheet | [`ST7802_DataSheet_V0.3.pdf`](./datasheets/ST7802_DataSheet_V0.3.pdf) |
| Datasheet | [`CST9220_Datasheet_V1.0.pdf`](./datasheets/CST9220_Datasheet_V1.0.pdf) |
| Datasheet | [`AM160Q480480LK4.pdf`](./datasheets/AM160Q480480LK4.pdf) |
| CAD file | [`OK-14F024-04.pdf`](./cad/OK-14F024-04.pdf) |
| Adapter materials | [`adapter-board-schematic.png`](./adapter/adapter-board-schematic.png) |
| Adapter materials | [`PCB-1.6寸AMOLED屏转接板V2.0.pdf`](./adapter/PCB-1.6%E5%AF%B8AMOLED%E5%B1%8F%E8%BD%AC%E6%8E%A5%E6%9D%BFV2.0.pdf) |
| Other | [`Panel_Parameter_timing.png`](./misc/Panel_Parameter_timing.png) |

## Repository layout

```text
display-amoled-1.6inch-480x480/ # repo root (nav: ../../README_EN.md; sample projects under root examples/)
└── versions/
    └── AM160Q480480LK4/        # full materials for this part number
        ├── README.md
        ├── README_EN.md
        ├── osptek.yml
        ├── images/
        ├── datasheets/       # product datasheet + driver/touch IC datasheets
        ├── cad/              # outline/cover CAD
        ├── adapter/          # adapter board materials + photos
        └── misc/             # other materials
```

## Buy

See the [repo home page](../../README_EN.md#where-to-buy).

## Support

See the [repo home page](../../README_EN.md#support).

---

<p align="center"><sub>© 2026 OSPTEK · Materials in this repository are licensed under CC BY 4.0</sub></p>
