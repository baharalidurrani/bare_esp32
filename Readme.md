# ESP-IDF Hello World - Blink

*Make sure* your project directory is `bare_esp32` as mentioned in `CMakeLists.txt`.

*Make sure* `esp-idf` is installed on your system and the path is updated in `.vscode/c_cpp_properties.json`

*Make sure* environment variables are loaded in the current terminal using the `get_idf` alias or manual:
```sh
alias get_idf='. $HOME/esp/esp-idf-v5.1.1/export.sh'
```

*Make sure* `idf.port` is updated in `.vscode/settings.json`

## Scripts

### `idf.py menuconfig`
for configuring the hardware etc

### `idf.py fullclean`
for cleaning the build folder

### `idf.py build`
for creating a fresh build

### `idf.py flash monitor`
for flashing the build folder and monitoring logs from the target board
