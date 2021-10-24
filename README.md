# Minecraft Modpack, for 1.17.1 Fabric

## Installation

0. Make sure you have Java in your `%PATH%` variable - try running `java -version`, if it shows you the version of installed Java, you're good. Otherwise, install latest [OpenJDK 16](https://adoptopenjdk.net/?variant=openjdk16&jvmVariant=hotspot)
1. Prepare a clean, unmodded Minecraft 1.17.1 instance with latest Fabric - either via your launcher, or by installing it with [official installer](https://fabricmc.net/use/)
2. Download [packwiz installer bootstrap](https://github.com/comp500/packwiz-installer-bootstrap/releases) and put it in your minecraft instance directory (open it from launcher if you can, by default it's `~/.minecraft` or `%appdata%/.minecraft`)
3. Open terminal and run this in minecraft instance directory (the same with packwiz installer bootstrap):
  ```java -jar packwiz-installer-bootstrap.jar https://raw.githubusercontent.com/SteelPh0enix/MCModpack1.17/master/pack.toml```
4. You should see a window with progress bar. The mods should download automatically, and after that you should be able to run Minecraft with all the mods installed.

## Modlist

look inside `mods` directory

mostly quality of life mods, some that increase performance and reduce memory usage. Most, if not all Optifine functions are available via other mods (includes shaders, zoom button and custom colors in resource pack support), but with better performance overall.

Should be safe to use with vanilla servers. Just few mods actually add items (Comforts, not sure about others)

Make sure to review mods config in Mod Menu.
