# Wokwi CI - ESP32 Continuous Integration Example

The Wokwi CI ESP32 example shows how to use GitHub Actions to build and test your ESP32 projects. The example runs the ESP-IDF [Hello World example](https://github.com/espressif/esp-idf/blob/master/examples/get-started/hello_world/main/hello_world_main.c), and checks if the program finishes by restarting the CPU.

To run this example, you'll need to set the `WOKWI_CI_RELEASE_URL` to the private pre-release URL provided to you by Wokwi.
