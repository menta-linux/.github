Menta Linux is a planned GNU/Linux distribution being built on Debian Stable (or just a repository), with MATE at its heart. Its goal is a consistent desktop with familiar workflows, native utilities, and system tools designed to work together.

## Development Status Matrix

| Emoji | Status | Emoji | Status | 
|--:|:--|--:|:--|
| ✅ | Done | 📋 | Planned |
| ❌ | Not planned/possible | ❓ | Not verified |
| 🚧 | In progress | 🧪 | Experimenting |
| ➖ | Not started yet | 🚮 | Abandoned |
| 📬 | PR submitted | 👍 | Awaiting merge |
| 🔀 | Merged | | |

| Name | Description | Progress | Packaging | Wayland |
|:--|:--|:--:|:--:|:--:|
| [MATE Clocks](https://github.com/KeremSoke/mate-clocks) | World clocks, alarms, stopwatch and timer | 🚧 | ➖ | ❓ |
| MATE Weather | A basic weather app | 📋 | 📋 | 📋 |
| [MATE Clipboard](https://github.com/KeremSoke/mate-clipboard) | Clipboard history with search, encryption and panel integration | ✅ | [🚧](https://github.com/menta-linux/pkg-mate-clipman) | ✅¹ |
| [MATE ScreenRuler](https://github.com/KeremSoke/mate-screenruler) | Configurable on-screen pixel ruler | ✅ | ➖ | 🧪² |
| [MATE Fingerprint Login](https://github.com/KeremSoke/mate-fprint) | Fingerprint enrollment and login configuration | ✅ | ➖ | 🧪 |
| [MATE Graphics Tablet](https://github.com/KeremSoke/mate-wacom) | Tablet and pen settings, including display mapping | ✅ | [✅](https://github.com/menta-linux/pkg-mate-wacom) | ❌ |
| [MATE Night Light](https://github.com/KeremSoke/mate-redshift) | Screen temperature settings that uses [rojo](https://github.com/KeremSoke/rojo), scheduling and previews. | ✅ | [🚧](https://github.com/menta-linux/pkg-mate-redshift) | ✅³ |
| MATE Color Management | A complete color management settings dialog that uses [rojo](https://github.com/KeremSoke/rojo) | 📋 | 📋 | 📋 |
| [Rojo](https://github.com/KeremSoke/rojo) | Night light, gamma, and color manager daemon | 🚧 | ➖ | 🧪³ |
| Menta Welcome | A welcome screen to introduce everything implemented | 📋 | 📋 | 📋 |
| [Menta Software Manager](https://github.com/KeremSoke/menta-install) | Browse and install Debian packages, Flatpaks and local packages | ✅ | 🚧 | ❓ |
| [Menta Software Sources](https://github.com/KeremSoke/menta-sources) | Manage Debian repositories, mirrors and signing keys | ✅ | 🚧 | ❓ |
| [Menta Update Manager](https://github.com/KeremSoke/menta-update) | Graphical software update management | ✅ | 🚧 | ❓ |
| [MATE Appmenu & HUD](https://gitlab.com/KeremSoke/mate-appmenu) | Global application menu and searchable menu actions | ✅ | [✅](https://github.com/menta-linux/pkg-mate-appmenu) | 🚧 |
| [MATE Media](https://github.com/KeremSoke/mate-media/tree/mpris-support) | Volume controls with integrated media playback controls | ✅📬👍 | ➖ | ✅ |
| [MATE Screensaver](https://github.com/KeremSoke/mate-screensaver) | Screen locking; media integration done | ✅📬 | ➖ | 🧪 |
| [Picom](https://github.com/KeremSoke/picom/tree/wobbly) | Desktop compositing with wobbly windows and magic lamp effects | ✅📬 | [✅](https://github.com/menta-linux/pkg-picom) | ❌ |
| [Desktop Effects Settings](https://github.com/KeremSoke/picom/tree/wobbly) | A nice settings dialog for my picom-wobbly| ✅ | ✅ | ❌ |
| [MATE HUD (legacy)](https://github.com/KeremSoke/mate-hud) | Earlier standalone application-menu search | 🚮⁴ | ❌ | ❌ |

1. Requires a compositor supporting the data-control protocol.
2. Core GTK interface is portable; positioning and pointer-related features need Wayland validation.
3. Requires `wlr-gamma-control`. Rojo includes a Wayland backend; validation and dev ongoing.
4. Superseded by the HUD integrated into MATE Appmenu.

## Why I'm doing all these?

I like Ubuntu MATE and MATE’s desktop workflow, however what I kept wanting was more attention to the experience as a whole: applications that follow the same desktop conventions, settings that belong in the control center, and everyday utilities that completes the desktop.

Keeping a traditional desktop also means continuing to develop and maintain it. There is plenty of room for better hardware settings, useful applications, media integration, and improvements to daily workflows while keeping the interface familiar.

Release upgrades have been another frustration. So far, every Ubuntu or Ubuntu MATE release upgrade I have attempted has eventually left me needing to reinstall. (This is a Ubuntu issue in general.) That experience made maintaining an installation over time an important part of what I want from a distribution.

Also I am not sure how wayland transition is going. I thought wayfire itself is pretty much a basic DE and mate-wayland-sessions feels more like a collection of panels and apps running on top of another DE. Therefore, I'll be using prioritizing and keep supporting X server support for this distribution or app collection, even though i tried to give wayland support for the most of the apps.

All these are why I started something like this that i'm sure no one will ever discover and use: to build and maintain the MATE desktop I daily use, and on my favorite OS: Debian Stable.

If I cannot create a distro, I'll be creating at least a repo for Debian Stable!
