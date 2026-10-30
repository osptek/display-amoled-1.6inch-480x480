<p align="left"><img alt="OSPTEK" src="../../images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 1.6″ AMOLED 显示屏 480×480（AM160Q480480LK4）</h1>

<p align="center"><b>AMOLED 模组 · MIPI · ST7802</b></p>

<p align="center"><a href="./README_EN.md">English</a> | 简体中文 · <a href="../../README.md">规格族索引</a></p>

<p align="center">
  <img alt="Interface: MIPI" src="https://img.shields.io/badge/Interface-MIPI-27AE60?style=flat-square" />
  <img alt="Driver: ST7802" src="https://img.shields.io/badge/Driver-ST7802-E7352C?style=flat-square" />
  <img alt="Touch: CST9220" src="https://img.shields.io/badge/Touch-CST9220-F39C12?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 1.6 寸 480×480 AMOLED 模组宣传图" src="./images/product.png" width="640" /></p>

## 目录

- [规格参数](#规格参数)
- [相关资料](#相关资料)
- [仓库结构](#仓库结构)
- [购买链接](#购买链接)
- [技术支持](#技术支持)

---

## 规格参数

| 项目 | 规格 |
| ---- | ---- |
| 尺寸 | 1.6 英寸 |
| 类型 | AMOLED |
| 分辨率 | 480×480 |
| 外形尺寸 | 55.00 x 55.00 mm |
| 有效显示区域 | 39.12 x 39.12 mm |
| 接口 | MIPI |
| 驱动 IC | ST7802 |
| 触摸驱动 | CST9220 |

> 完整外形尺寸、FPC 定义、供电与时序以产品规格书 / 驱动手册为准。

## 相关资料

| 分类 | 文件 |
| ---- | ---- |
| 规格文档 | [`ST7802_DataSheet_V0.3.pdf`](./datasheets/ST7802_DataSheet_V0.3.pdf) |
| 规格文档 | [`CST9220_Datasheet_V1.0.pdf`](./datasheets/CST9220_Datasheet_V1.0.pdf) |
| 规格文档 | [`AM160Q480480LK4.pdf`](./datasheets/AM160Q480480LK4.pdf) |
| CAD 图纸 | [`OK-14F024-04.pdf`](./cad/OK-14F024-04.pdf) |
| 转接板资料 | [`adapter-board-schematic.png`](./adapter/adapter-board-schematic.png) |
| 转接板资料 | [`PCB-1.6寸AMOLED屏转接板V2.0.pdf`](./adapter/PCB-1.6%E5%AF%B8AMOLED%E5%B1%8F%E8%BD%AC%E6%8E%A5%E6%9D%BFV2.0.pdf) |
| 其他资料 | [`Panel_Parameter_timing.png`](./misc/Panel_Parameter_timing.png) |

## 仓库结构

```text
display-amoled-1.6inch-480x480/ # 仓库根（导航见 ../../README.md，示例工程见根目录 examples/）
└── versions/
    └── AM160Q480480LK4/        # 本料号完整资料
        ├── README.md
        ├── README_EN.md
        ├── osptek.yml
        ├── images/
        ├── datasheets/       # 产品规格书 + 驱动/触摸 IC 数据手册
        ├── cad/              # 外形/盖板 CAD
        ├── adapter/          # 转接板资料 + 转接板图片
        └── misc/             # 其他资料
```

## 购买链接

见[仓库首页](../../README.md#购买链接)。

## 技术支持

见[仓库首页](../../README.md#技术支持)。

---

<p align="center"><sub>© 2026 OSPTEK 鱼鹰光电 · 本仓库资料采用 CC BY 4.0 许可</sub></p>
