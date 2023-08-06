# simrig-bbox
Teensy-based multi-purpose simrig controller. Teensy 4.1 + Ethernet kit. Custom designed 3D printed enclosure. Controls external custom designed relay cable box.

# LED push button pins
 * 32 LED + 31 switch status (pullup resistor)
 * 30 LED + 29 switch status (pullup resistor)
 * 28 LED + 27 switch status (pullup resistor)
 * 26 LED + 25 switch status (pullup resistor)
 * 24 LED + 10 switch status (pullup resistor)

# Relay control pins

`LOW` means on, `HIGH` means off.

 * 2 (Fanatec DD1)
 * 3 (Bass shaker system)
 * 4 (Motion platform)
 * 5 (Surround system)

# Rotary encoder pins

Switch pin `12`, rotary pins: `8` and `9`.

Tested. Currently unused.

# Display

I2C wide.hk OLED display. Currently does not work. Probably H/W issue.

# Ethernet

Use `Native Ethernet` library. Tested. Currently unused.
