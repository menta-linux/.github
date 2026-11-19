Menta Linux is a planned GNU/Linux distribution being built on Debian Stable (or just a repository), with MATE at its heart. Its goal is a consistent desktop with familiar workflows, native utilities, and system tools designed to work together.

Please go see my **[MATE Wayland Transition Roadmap](https://github.com/KeremSoke/polo/discussions/6)**. After that I'll be finishing:

- [ ] **[MATE Clocks](https://github.com/KeremSoke/mate-clocks)** : World clocks, alarms, stopwatch and timer
- [ ] **MATE Weather** : A basic weather app
- [x] **[MATE Clipboard](https://github.com/KeremSoke/mate-clipboard)** : Clipboard history with search, encryption and panel integration
- [ ] **[MATE ScreenRuler](https://github.com/KeremSoke/mate-screenruler)** : Configurable on-screen pixel ruler
    - A complete vala rewrite is needed.
- [x] **[MATE Fingerprint Login](https://github.com/KeremSoke/mate-fprint)** : Fingerprint enrollment and login configuration
- [x] **[MATE Graphics Tablet](https://github.com/KeremSoke/mate-wacom)** : Tablet and pen settings, including display mapping
    - A wayland backend needed
- [x] **[MATE Night Light](https://github.com/KeremSoke/mate-redshift)** : Screen temperature settings that uses [rojo](https://github.com/KeremSoke/rojo), scheduling and previews
- [ ] **MATE Color Management** : A complete color management settings dialog that uses [rojo](https://github.com/KeremSoke/rojo)
- [X] **[Rojo](https://github.com/KeremSoke/rojo)** : Night light, gamma, and color manager daemon
- [ ] **Menta Welcome** : A welcome screen to introduce everything implemented
- [ ] **[Menta Software Manager](https://github.com/KeremSoke/menta-install)** : Browse and install Debian packages, Flatpaks and local packages
    - A complete rewrite in Vala needed
- [ ] **[Menta Software Sources](https://github.com/KeremSoke/menta-sources)** : Manage Debian repositories, mirrors and signing keys
    - A complete rewrite in Vala needed
- [ ] **[Menta Update Manager](https://github.com/KeremSoke/menta-update)** : Graphical software update management
    - A complete rewrite in Vala needed
- [ ] **Menta Language Selector** : A language selector for debian
- [x] **[MATE Appmenu & HUD](https://gitlab.com/KeremSoke/mate-appmenu)** : Global application menu and searchable menu actions
- [x] **[MATE Media](https://github.com/mate-desktop/mate-media)** : Volume controls with integrated media playback controls
- [ ] **[MATE Screensaver](https://github.com/KeremSoke/mate-screensaver)** : Screen locking; media integration done
    - Wayland under development
- [x] **[Picom](https://github.com/KeremSoke/picom/tree/wobbly)** : Desktop compositing with wobbly windows and magic lamp effects
- [x] **[Polo](https://github.com/KeremSoke/polo)** : A wayland compositor and display server for MATE
- [x] **[Polo Tweaks](https://github.com/KeremSoke/polo-tweaks)** : A nice settings dialog for Polo
- [ ] **[MATE HUD](https://github.com/KeremSoke/mate-appmenu)** : New standalone application-menu search
    - Need to separate the HUD from main project and add wayland support

After all these I'll be doing:

- [ ] **menta-desktop Metapackage**
- [X] **[Menta plymouth](https://github.com/KeremSoke/menta-plymouth)**
- [ ] Package creation and backporting

## Why I'm doing all these?

I like Ubuntu MATE and MATE’s desktop workflow, however what I kept wanting was more attention to the experience as a whole: applications that follow the same desktop conventions, settings that belong in the control center, and everyday utilities that completes the desktop.

Keeping a traditional desktop also means continuing to develop and maintain it. There is plenty of room for better hardware settings, useful applications, media integration, and improvements to daily workflows while keeping the interface familiar.

Release upgrades have been another frustration. So far, every Ubuntu or Ubuntu MATE release upgrade I have attempted has eventually left me needing to reinstall. (This is a Ubuntu issue in general.) That experience made maintaining an installation over time an important part of what I want from a distribution.

Also I am not sure how wayland transition is going. I thought wayfire itself is pretty much a basic DE and mate-wayland-sessions feels more like a collection of panels and apps running on top of another DE. Therefore, I'll be using prioritizing and keep supporting X server support for this distribution or app collection, even though i tried to give wayland support for the most of the apps.

All these are why I started something like this that i'm sure no one will ever discover and use: to build and maintain the MATE desktop I daily use, and on my favorite OS: Debian Stable.

If I cannot create a distro, I'll be creating at least a repo for Debian Stable!
