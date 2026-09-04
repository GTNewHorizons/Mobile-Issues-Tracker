# Welcome to the GT:NH Mobile issue tracker!
## This repository serves as an issue tracker for the mobile-exclusive bugs. If you can reproduce the bug on the non-mobile version, please consider posting your issue [here](https://github.com/GTNewHorizons/GT-New-Horizons-Modpack/issues) instead. Thanks.

### You should report a mobile bug only if all of the following are true:
- You can only reproduce the bug on the mobile version of GT:NH
- You know how to extract logs from your instance to provide them in the ticket
- **You play in a supported configuration (see below)**

### Supported configuration(s)
- Operating system: Android 10+
- Launcher: [Amethyst](https://github.com/AngelAuraMC/Amethyst-Android)
- Modpack archive: either from our [official download page](https://www.gtnewhorizons.com/downloads/) or from our [dev build page](https://github.com/GTNewHorizons/GTNH-Daily-Builds/releases)
- Allocated memory: 2.5 GB if you play on a remote server, 4 GB if you play in single-player mode

### How to report a bug like a pro
- State your GT:NH version precisely: Neither "latest" nor "1.7.10" is a valid version. If you need to find it, see what's displayed on the main menu.
- State your Amethyst launcher version (the version you downloaded).
- Provide your logs: As much as it pleases us to think we are wizards, we currently have no divination powers to guess the issue from your bug description.
- State every change you made to your modpack config files (e.g., pollution off). **Beware: some configurations are mandatory for the mobile version to run properly. Do not report a bug if it's related to one of those configurations being changed; see the next category below**.
- State your issue clearly, with reproduction steps if possible: most of our work is trying to reproduce the issue, so easy reproduction steps mean a high chance of fixing the bug.
- If applicable, attach screenshots representing the issue. That usually helps us narrow the bug down.

### What configurations are intended to be specific to the GT:NH Mobile edition?
- `config/lwjgl3ify.cfg`: `B:sharedContext=false` and `B:linuxCreateAppDesktopEntry=false`
- `config/Betterloadingscreen/betterloadingscreen.cfg`: `B:threadedRendering=false`

### Missing mods from the GT:NH Mobile edition
- CraftPresence: rich presence integration is intended to be only with the desktop application of Discord
