# Tileset Extruder Plugin

Plugin that automatically extrudes & scales tilesets on save.

## Why?

The engine I work with does not support Nearest Neighbor scaling. While I could manually extrude my tilesets using [a different script I created](https://github.com/Ransomwave/aseprite-extrude-script), it became very frustrating to have to do this every time I saved a tileset.

This plugin automates the process, so you can just save your tileset and it will be extruded and scaled automatically.

## Installation

1. Clone this repository or [download it as a zip](https://github.com/Ransomwave/aseprite-tileset-extruder/archive/refs/heads/main.zip)
   ```ps1
   git clone https://github.com/Ransomwave/aseprite-tileset-extruder.git
   ```
2. Compress the plugin as a zip file
   ```ps1
   Compress-Archive -Path . -DestinationPath .\tileset-extruder.aseprite-extension -Force
   ```
3. In Aseprite, go to `Edit > Preferences > Extensions` and click `Add Extension...`
4. Select your `tileset-extruder.aseprite-extension` file.
5. Restart Aseprite.
