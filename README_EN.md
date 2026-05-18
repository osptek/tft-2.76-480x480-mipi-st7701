# 2.76" 480×480 TFT MIPI module (ST7701) — documentation & samples

**简体中文：** [`README.md`](README.md)

---

> This repository provides **sample projects** for this module, together with datasheets, specifications, and interface / bring-up documentation for selection reference and integration.

## Product overview

| Item | Description |
|:--|:--|
| Module | 2.76-inch **TFT** panel, **480×480** resolution |
| Interface | **MIPI** |
| Driver IC | **ST7701** |
| Spec ID | **`2.76-tft-480x480-mipi-st7701`** is the common product designation in documentation |

---

## Repository layout

### Top-level

| Path | Contents |
|:--|:--|
| `docs/` | Datasheets, specifications, initialization documentation |
| `examples/` | **Sample projects** |

### `examples/` layout

| Location | Description (internal package folder) |
|:--|:--|
| `examples/` root | **ESP-IDF代码** (MIPI DSI + LVGL) |

### Sample project paths

| Description | Path |
|:--|:--|
| ST7701 MIPI DSI + LVGL | `examples/esp32p4-idf5_st7701-mipi-dsi/` |
