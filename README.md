# DadaStaffTools 1.0

> Comandi staff per aprire inventari ed enderchest dei player.

![Minecraft](https://img.shields.io/badge/Minecraft-1.20%2B-green?style=for-the-badge)
![Paper](https://img.shields.io/badge/Paper%20%2F%20Spigot-Compatible-blue?style=for-the-badge)
![Version](https://img.shields.io/badge/Version-1.0-purple?style=for-the-badge)

## Overview

**DadaStaffTools 1.0** is a custom Minecraft plugin for Paper/Spigot servers.

Comandi staff per aprire inventari ed enderchest dei player.

| Field | Value |
| --- | --- |
| Plugin | `DadaStaffTools` |
| Version | `1.0` |
| Category | Custom Server Tool |
| Main class | `it.dadasmp.stafftools.DadaStaffToolsPlugin` |

## Features

| Feature | Description |
| --- | --- |
| Clean package | Public jar name without server-specific labels. |
| Server ready | Designed for Paper/Spigot Minecraft servers. |
| Configurable | Uses Bukkit/Paper plugin configuration where supported. |
| Commands | Includes in-game commands documented below. |
| Permissions | Includes permission nodes documented below. |

## Commands

| Command | Description | Usage | Permission | Aliases |
| --- | --- | --- | --- | --- |
| `/invsee` | Apre l'inventario di un player online. | `/invsee <player>` | None | `- openinv` |
| `/endersee` | Apre l'enderchest di un player online. | `/endersee <player>` | None | `- ecsee` |
| `/stafftools` | Mostra le informazioni del plugin. | `/stafftools` | None | `- dstaff` |

## Permissions

| Permission | Default | Description |
| --- | --- | --- |
| `dadastafftools.invsee` | `op` | Permette di usare /invsee <player>. |
| `dadastafftools.endersee` | `op` | Permette di usare /endersee <player>. |
| `dadastafftools.bypass.self` | `op` | Permette di aprire il proprio inventario o enderchest con i comandi staff. |
| `dadastafftools.admin` | `op` | Permette di usare /stafftools. |

## Installation

1. Download the jar from the `release` folder.
2. Put it inside your server `plugins` folder.
3. Restart the server.
4. Configure the plugin if it creates a configuration folder.

Compiled jar:

`release/DadaStaffTools-1.0.jar`

## Support

For support, bug reports or setup help, join the Discord server:

https://discord.gg/yXrDpKCGAs

## License

All rights reserved. Redistribution, resale or modification is not allowed without written permission from DadaSMP.
