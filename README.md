# Cat Themed ESP32 Controller
The ESP32 utilizes ESP-NOW communication to talk give inputs to other ESP32's (The code is not compatible with bluetooth, but you can edit it to be compatible!)
The lid, joystick module, and the controller body are made to be screwed together by M2 8mm screws.

How to connect everything (please do it in this order!! or else you'll have to do soldering in really awkward positions)
1. Note down which color wires you are using for each ESP32 pin (helps you remember where to solder each wire onto the joystick)
2. Solder one end of the colored wires to the pins of the ESP32. The pins I used were GPIO 35 (Joystick x), 34 (Joystick y), and 15 (Switch), 3.3v, and GND
3. Screw in the ESP32 into the controller body so that the pins stand up. Make sure the USB port sticks out to the open side
4. Feed the wires through the wide hole on the lid of the controller
5. Solder the wires to the joystick module
6. Screw the lid onto the controller body
7. Screw the joystick module onto the lid
8. Upload the joystick code to the ESP32, remember to replace the MAC address with the MAC address of the ESP32 you want to transmit input to!

You will need to put the .STL's face down in whatever slicer you use for the 3D printer


Have fun!
