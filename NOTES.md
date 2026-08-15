# Project Setup Notes

In the `platformio.ini` we use the variable `src_dir` to specify the folder with the main entry source files for the project. To keep the convention of the native ESP32 IDF we named it `main`, and without this variable platformio looks for the default `src` folder.

