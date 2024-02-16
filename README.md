Copy the content folder to `%HOMEPATH%/.platformio/`:

```
C
|--Users
   |--<Username>
      |--.platformio
         |--boards
            |-bpi-centi-s3.json
            |-esp32-s3-devkitc1-n16r8.json
            |-feenove-esp32-s3-n8r8.json
```

PIO cli commands:

```
pio project init -b bpi-centi-s3 --ide vscode
```

```
pio project init -b esp32-s3-devkitc1-n16r8 --ide vscode
```

```
pio project init -b feenove-esp32-s3-n8r8 --ide vscode
```
