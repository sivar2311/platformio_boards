Clone this repo to `$HOME/.platformio/boards`, reload PIO VS Code extension.
```
git clone https://github.com/sivar2311/platformio_boards.git ~/.platformio/boards
```

Or manually download and unzuo this repo, move the json files to `%HOMEPATH%/.platformio/boards`

(If there is no `boards` folder, just create one.)

```
C
|--Users
   |--<Username>
      |--.platformio
          |--boards
             |- bpi-centi-s3.json
             |- esp32-s3-devkitc1-n8r8.json
             |- esp32-s3-devkitc1-n16r8.json
             |- esp32-s3-fh4r2.json
             |- feenove-esp32-s3-n8r8.json
             |- ...
```

Example of PIO cli commands:

```
pio project init -b esp32-s3-devkitc1-n16r8 --ide vscode
```

# Reminder
All files of this repo has included in [pioarduino](https://github.com/pioarduino/pioarduino-vscode-ide) by default, it's an alternative fork of Platform IO. You can use pioarduino to have these boards without using this repo.