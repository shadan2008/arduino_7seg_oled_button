# arduino_7seg_oled_button
Arduino project : Button counter that displays numbers on both SSD1306 OLED and the seven-segment display at the same time, built with if-else logic and U8glib.
press a button and both 7-segment and OLED show the same number!
built with Arduino UNO, common anode 7-segment display, SSD1306 OLED. and push button.

## components required->
- Arduino UNO
- 1 x 7-segment display
- 1 x 220ohm resistor for 7-segment display
- 1 x SSD1306 128x64 OLED (I2C) 0.96 inch
- 1 x push button
- 1 x 10k ohm resistor for push button
- Breadboard + jumper wires (male to male)

##  Wiring
- 7-seg a-g -> D2-D8
- Button -> D10 + GND (INPUT_PULLUP)
- OLED SDA -> A4, SCL -> A5, VCC -> 5V, GND -> GND

## how it works
- uses simple 'if-else' logic
- 'delay(200)' for debouncing
- U8glib for OLED bitmaps
- counts 1-> 2 -> loops (will expand to 1-9)

## Tools and websites Used
- **Arduino IDE** for coding and uploading
- **U8glib Library** by Oliver Kraus
- **image2cpp** to convert any image into the pixels bitmap array
- **Circuit Diagram Tools** if you want to use you can use 'Tinker Cad', 'WoKwi'
- **PHOTOPEA** to make the pixel image and convert it into PNG image form
- **GitHub** to host this project

## Acknowledgments
Thanks to Arduino community and YouTube tutorials for wiring help.
