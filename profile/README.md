Here are my MATE Debian Stable/Unstable packaging repositories. 

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
- [X] **[Menta Software Sources](https://github.com/KeremSoke/menta-sources)** : Manage Debian repositories, mirrors and signing keys
- [ ] **[Menta Update Manager](https://github.com/KeremSoke/menta-update)** : Graphical software update management
    - A complete rewrite in Vala needed
- [ ] **Menta Language Selector** : A language selector for debian
- [x] **[MATE Appmenu & HUD](https://gitlab.com/KeremSoke/mate-appmenu)** : Global application menu and searchable menu actions
- [x] **[MATE Media](https://github.com/mate-desktop/mate-media)** : Volume controls with integrated media playback controls
- [ ] **[MATE Screensaver](https://github.com/mate-desktop/mate-screensaver)**
    - Wayland under development
- [x] **[Picom](https://github.com/KeremSoke/picom/tree/wobbly)** : Desktop compositing with wobbly windows and magic lamp effects
- [x] **[Polo](https://github.com/KeremSoke/polo)** : A wayland compositor and display server for MATE
- [x] **[Polo Tweaks](https://github.com/KeremSoke/polo-tweaks)** : A nice settings dialog for Polo
- [ ] **[MATE HUD](https://github.com/KeremSoke/mate-appmenu)** : New standalone application-menu search
    - Need to separate the HUD from main project and add wayland support

After all these I'll be doing:

- [ ] **`menta-desktop` metapackage**
- [X] **[Menta plymouth](https://github.com/KeremSoke/menta-plymouth)**
- [ ] Package creation and backporting
