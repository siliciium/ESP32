# Arduino IDE 2.2.1

Go to `Preferences` and add package URL in `Additional map manager URLs`

Stable release link: https://espressif.github.io/arduino-esp32/package_esp32_index.json

![Capture0](https://github.com/siliciium/ESP32/assets/103604296/bd72dc9f-db65-444d-99f5-143ce49e1071)

Go to `Board manager` and install `esp32` package by `Espressif Systems`

![Capture0 5](https://github.com/siliciium/ESP32/assets/103604296/206ba0e6-b9b4-4a9a-b801-885994b51b9e)

Plug your ESP32 S2 with USB cable on your computer and put it into `DFU mode`
Ref: https://www.wemos.cc/en/latest/tutorials/s2/get_started_with_arduino_s2.html

![Capture2](https://github.com/siliciium/ESP32/assets/103604296/91f93f9f-90fc-4f4b-8f2a-761ef57a1694)

Now, `Devices Manager` on Windows must show `COM port` or on Linux using `dmesg` or `/var/log/syslog` must show `/dev/ttyACM0`.

Configure your board on Arduino and set `USB CDC On Boot` on `Enabled` to enable serial monitoring for the example codes

![esp32-arduino](https://github.com/siliciium/ESP32/assets/103604296/e6cb5fbc-84ee-4afa-9ed6-92d923baa073)

![Capture](https://github.com/siliciium/ESP32/assets/103604296/5233374f-ff1a-47d5-a377-b185957465d2)

Choose an example code 

![Capture4](https://github.com/siliciium/ESP32/assets/103604296/4b408fba-5858-45a0-a86e-ee18b098d95f)

Upload your sketch. Open `Serial Monitor` in Arduino and push the ESP32-S2 mini `physical RESET button`.
If the example code you chose implements serial, you should see the result in the serial monitor.


# Ref : 
https://docs.espressif.com/projects/arduino-esp32/en/latest/installing.html

https://github.com/espressif/arduino-esp32

