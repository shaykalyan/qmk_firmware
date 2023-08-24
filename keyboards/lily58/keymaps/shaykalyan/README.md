# Compile steps for future Shay

## How this folder was created
* Followed steps for building firmware here: https://docs.qmk.fm/#/newbs_building_firmware
* Created keymap with `qmk new-keymap -kb lily58 -km shaykalyan`

## How to update keymap and recompile

1. Manage keymap etc. using [QMK Configurator](https://config.qmk.fm/), i.e., import `lily58-rev1-shaykalyan.json`, modify, and export back to the JSON file here.
2. Convert JSON to keymap.c using `qmk json2c keyboards/lily58/keymaps/shaykalyan/lily58-rev1-shaykalyan.json -o keyboards/lily58/keymaps/shaykalyan/keymap.c`.
3. Compile firmware using `qmk compile -kb lily58 -km shaykalyan`
