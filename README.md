<div align="center">

<img src="https://raw.githubusercontent.com/penguinyzsh/janus/main/app/src/main/res/mipmap-xxxhdpi/ic_launcher_round.webp" width="160" height="160" style="display: block; margin: 0 auto;" alt="icon" />

# Janus

### Xiaomi Rear Screen Enhancement LSPosed Module

[\![Android](https://img.shields.io/badge/Android-15+-green?logo=android)](https://developer.android.com)
[\![LSPosed](https://img.shields.io/badge/Xposed-API%2082-blue?logo=lsposed)](https://github.com/LSPosed/LSPosed)
[\![License](https://img.shields.io/badge/License-GPL--3.0-orange?logo=gnu)](https://github.com/penguinyzsh/janus/blob/main/LICENSE)

</div>

## Features

- **Music Whitelist Unlock** — Remove rear screen music app whitelist restrictions
- **Rear Screen DPI Adjustment** — Customize rear screen display density
- **Rear Screen Keep Alive** — Prevent auto-sleep with foreground service
- **Live Wallpaper Anti-Interrupt** — Keep live wallpaper playing through cover overlay
- **Screen Casting Settings** — Rotation control, keep rear screen on during casting
- **Telemetry Blocking** — Block usage data reporting
- **Quick Switch** — Quick settings tile for one-tap casting to rear screen
- **Hide Launcher Icon** — Hide app icon, access via LSPosed manager only

## Prerequisites

1. Unlocked Bootloader + Root access
2. [LSPosed](https://github.com/LSPosed/LSPosed/releases) framework installed
3. Enable Janus in LSPosed, select scope `com.xiaomi.subscreencenter`
4. Restart scope or reboot

## Scope

| App Name | Package Name |
|:---------|:-------------|
| Rear Display | com.xiaomi.subscreencenter |

## Links

- **Source Code**: [github.com/penguinyzsh/janus](https://github.com/penguinyzsh/janus)
- **Issues**: [github.com/penguinyzsh/janus/issues](https://github.com/penguinyzsh/janus/issues)

## License

[GPL-3.0](https://github.com/penguinyzsh/janus/blob/main/LICENSE)
