<div align="center">

<img src="https://raw.githubusercontent.com/penguinyzsh/janus/main/app/src/main/res/mipmap-xxxhdpi/ic_launcher_round.webp" width="160" height="160" style="display: block; margin: 0 auto;" alt="icon" />

# Janus

### Xiaomi Rear Screen Enhancement LSPosed Module

**English** | [简体中文](https://github.com/penguinyzsh/janus/blob/main/README_CN.md)

[\![Android](https://img.shields.io/badge/Android-15+-green?logo=android)](https://developer.android.com)
[\![LSPosed](https://img.shields.io/badge/Xposed-API%2082-blue?logo=lsposed)](https://github.com/LSPosed/LSPosed)
[\![Kotlin](https://img.shields.io/badge/Kotlin-2.3.20-purple?logo=kotlin)](https://kotlinlang.org)
[\![License](https://img.shields.io/badge/License-GPL--3.0-orange?logo=gnu)](https://github.com/penguinyzsh/janus/blob/main/LICENSE)

</div>

## Introduction

Janus is an LSPosed module for Xiaomi foldable phones, designed to enhance the rear screen experience. By hooking `com.xiaomi.subscreencenter`, it bypasses various system restrictions on the rear screen.

## Features

- **Music Whitelist Unlock** — Remove rear screen music app whitelist restrictions, manage whitelist per app
- **Rear Screen DPI Adjustment** — Customize rear screen display density for better small-screen experience
- **Rear Screen Keep Alive** — Foreground service periodically sends key events to prevent auto-sleep
- **Live Wallpaper Anti-Interrupt** — Keep live wallpaper playing through cover overlay
- **Screen Casting Settings** — Screen casting rotation control, keep rear screen on during casting
- **Telemetry Blocking** — Intercept `DailyTrackReceiver` to block data reporting
- **Quick Switch** — Quick settings tile for one-tap casting to rear screen
- **Hide Launcher Icon** — Hide app icon from launcher, access via LSPosed manager only

## Prerequisites

1. Device must have an unlocked Bootloader and Root access
2. Install [LSPosed](https://github.com/LSPosed/LSPosed/releases) framework
3. Enable Janus module in LSPosed, select scope `com.xiaomi.subscreencenter`
4. Open Janus app and configure features as needed
5. Restart the scope or reboot the device for hooks to take effect

> **Note**: Keep alive, DPI adjustment, task migration and other features require Root access.

## Scope

| App Name          | Package Name                    |
|:------------------|:--------------------------------|
| Rear Display | com.xiaomi.subscreencenter      |

## Acknowledgements

> Janus uses content from the following open-source projects. Thanks to the developers of these projects.

- [MIUIX by YuKongA](https://github.com/compose-miuix-ui/miuix) — Xiaomi-style Compose UI component library
- [LSPosed by LSPosed](https://github.com/LSPosed/LSPosed) — Modern Xposed framework

## Links

- **Source Code**: [github.com/penguinyzsh/janus](https://github.com/penguinyzsh/janus)
- **Issues**: [github.com/penguinyzsh/janus/issues](https://github.com/penguinyzsh/janus/issues)

## License

This project is licensed under the [GPL-3.0](https://github.com/penguinyzsh/janus/blob/main/LICENSE) license.
