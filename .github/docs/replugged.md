# Replugged

This guide describes how you can install [Replugged](https://github.com/replugged-org/replugged) on [Discord](https://discord.com/) Canary. This guide is for the Windows operating system.


# Windows

> **Note:** You cannot install **Replugged** and another client mod injected at the same time. If you have one installed, you must first uninstall it from your Discord Canary installation before proceeding to installation.


## Prerequisites

These are the prerequisites that you must meet in order for Replugged to function properly.

1. Download & install [git](https://git-scm.com/downloads).
2. Download & install [Node.js](https://nodejs.org/) *(LTS is recommended)*
3. Download & install [Discord Canary](https://discord.com/api/download/canary?platform=win) *(It's recommended to use Discord Canary.)*

## Installation

We assume here that you have "Git" and "Node" installed correctly and are using "Discord Canary". It is also worth noting that we strongly recommend that you run Discord Canary while performing steps 1 and 2 if you are working with Linux.

1. Completely “kill” your Discord Client. *(right-click in the System Tray -> “Quit DiscordCanary”)*
2. ``git clone https://github.com/replugged-org/replugged``
3. ``cs replugged``
4. ``npm i``
5. ``npm run plug``
6. Start Discord back up and [Replugged](https://github.com/replugged-org/replugged) should be injected!

## Uninstallation

If you want to remove Replugged again, you can do it this way.

1. Completely “kill” your Discord Client. *(right-click in the System Tray -> “Quit DiscordCanary”)*
2. Open a command prompt / terminal of your choice.
3. ``cd replugged``

4. ``npm run unplug``
5. Start Discord back up and [Replugged](https://github.com/replugged-org/replugged) should no longer be injected.


# Linux


# macOS




# Support