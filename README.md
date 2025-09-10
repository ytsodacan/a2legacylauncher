<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->
# Orion Drift Legacy Launcher

A small script to patch Orion Drift APKs to run offline.

Particularly useful when running old versions of Orion Drift that don't have servers anymore.

> [!NOTE]
> This project has NOT been extensively tested, please report bugs in [issues](https://github.com/ytsodacan/a2legacylauncher/issues)

## Dependencies
- Java 8+ in PATH

## Get started
- open the application
- if no application run main.py in backend
- its pretty simple after that
- select the apk, obb and engine.ini mode and slam that run button
- The maintain button must be clicked every time the game is opened because it deletes the Engine.ini

## How does it work?
Rebuilding the APK with debugging enabled gives permission to access the game files without root. <br>
From there we can place an Engine.ini which overrides the games file letting us bypass authentication and load straight into the map without connecting to any servers.

It's simple

made by [ytsodacan](https://github.com/ytsodacan) and [obelous](https://github.com/0belous)

# working on adding actual servers possibly???
