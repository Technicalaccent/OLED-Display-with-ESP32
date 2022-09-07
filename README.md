Arduino Code for Interfacing OLED Display with ESP32
To make the interfacing easier we need to install two Arduino libraries Adafruit’s SSD1306 library and Adafruit GFX Library. To install them navigate to the Sketch > Include Library > Manage Libraries. Wait for the Library Manager to download the libraries index and update the list of installed libraries. Then search for the specific library and install it.

Testing the OLED Display
To test and make sure the display is working fine, first make the connections as per the connection diagram provided. Once it’s done, open the example program by navigating to File > Examples > Adafruit SSD1306 >ssd1306_128x64_i2c. Once the example file is opened change the address of the OLED to 0x3C. Then compile and upload the program to the ESP32.