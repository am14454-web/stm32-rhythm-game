# stm32-rhythm-game

A real-time embedded rhythm game built on an STM32F411 running FreeRTOS —
a Guitar Hero-style game with synchronized audio, LED note-scrolling,
and OLED score/judgment display.

## Status: In Progress 🚧
Currently in Phase 0 (toolchain setup).

## Planned Architecture
- FreeRTOS with 4 concurrent tasks (Input, Game Logic, Render, Audio)
- I2C OLED display, WS2812B addressable LED strip, DFPlayer Mini audio
- Custom timing engine with 4-tier judgment (Perfect/Great/Good/Miss)

## Hardware
- STM32F411 "Blackpill"
- Full BOM: [link or table, add later]