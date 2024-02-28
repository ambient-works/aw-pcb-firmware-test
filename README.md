# RGB Led Test on Espressif ESP32-C6 Dev board

Note: RGB Led on dev board is on PIN 8, change to correct pin for the PCB (line 8, '#define PIN 8'.

1.  Install Arduino IDE https://www.arduino.cc/en/software
2.  Go to Settings
3.  At the bottom of the settings window, add this line: https://espressif.github.io/arduino-esp32/package_esp32_dev_index.json
4.  Go to tools > Board > Boards manager
5.  Search for 'Arduino ESP32 Boards'
6.  Press on install
7.  Load Simple LED Control Example
8.  Install Libraries, for example Adafruit Neopixel 
9.  Select board (any of the c6 should be fine, I have been testing with the SparkFun ESP32-C6) and your serial port.
10. Upload code
11. Press reset button (on unplug / replug)
12. Enjoy the light show!

![](rgb_led_demo.gif)



