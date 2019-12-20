## Adafruit PyPortal - CircuitPython Powered Internet Display PCB

<img src="assets/4116.jpg?raw=true" width="500px"><br/>
<img src="assets/4465.jpg?raw=true" width="500px"><br/>
<img src="assets/4444-1.jpg?raw=true" width="500px"><br/>


PCB files for the Adafruit PyPortal - CircuitPython Powered Internet Display and PyPortal Pynt. Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4116
* https://www.adafruit.com/product/4465
* https://www.adafruit.com/product/4444

### Description

**PyPortal**, our easy-to-use IoT device that allows you to create all the things for the “Internet of Things” in minutes. Make custom touch screen interface GUIs, all open-source, and Python-powered using tinyJSON / APIs to get news, stock, weather, cat photos, and more – all over Wi-Fi with the latest technologies. Create little pocket universes of joy that connect to something good. Rotate it 90 degrees, it’s a web-connected conference badge #badgelife.

The PyPortal uses an ATMEL (Microchip) ATSAMD51J20, and an Espressif ESP32 Wi-Fi coprocessor with TLS/SSL support built-in. PyPortal has a **3.2″ 320 x 240 color TFT** with resistive touch screen. PyPortal includes: speaker, light sensor, temperature sensor, NeoPixel, microSD card slot, 8MB flash, plug-in ports for I2C and 2 analog/digital pins, 3D files for custom enclosures / lanyard fastening. Open-source hardware, and Open-Source software, CircuitPython and Arduino. The device shows up as a USB drive and the code (Python) can be edited in any IDE, text editor, etc.

The PyPortal Pynt is the little sister to our popular PyPortal - zapped with a shink ray to take the design from a 3.2" diagonal down to 2.4" diagonal screen - but otherwise the same! **Compared to the PyPortal, the Pynt does not include a ADT7410 temperature sensor. Other than the ADT7410, the Pynt's display, processor, STEMMA conectors and WiFi have the exact same wiring as the original 3.2" PyPortal so all Arduino/CircuitPython code will run exactly the same - just smaller!**

The M4 and ESP32 are a great couple - and each bring their own strengths to this board. The SAMD51 M4 has native USB so it can show up like a disk drive, act as a MIDI or HID keyboard/mouse, and of course bootload and debug over a serial port. It also has DACs, ADC, PWM, and tons of GPIO. Meanwhile, the ESP32 has secure WiFi capabilities, and plenty of Flash and RAM to buffer sockets. By letting the ESP32 focus on the complex TLS/SSL computation and socket buffering, it frees up the SAMD51 to act as the user interface. You get a great programming experience thanks to the native USB with files available for drag-n-drop, and you don't have to spend a ton of processor time and memory to do SSL encryption/decryption and certificate management. It's the best of both worlds!

**Please note:** You may get a version with DigiKey + Analog Devices branding or in plain style. The hardware is identical.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. See license.txt for additional details.
