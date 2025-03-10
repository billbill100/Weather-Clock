# Weather-Clock
Arduino ESP Weather Clock. Takes time and local weather data from the Internet and displays it on a 3.5" TFT screen

An ESP32 based weather clock, which connects via wi-fi, to regularly update the time and local weather.

The original project has open-source source code but requires bespoke (expensive) hardware.
I found a few issues that would stop many being able to build this weather clock. These have been overcome, allowing anybody to make the Weather Clock.

First issue was hardware. The code (open-source) is designed to run on bespoke hardware, which is both expensive to purchase and expensive to ship. This issue has been overcome by re-writing the code to work on cheap Aliexpress parts.

Second issue, is the code itself. It is very complex and unless the user is familiar with python, Visual Studio and Platform IO, they would struggle.
.
Solution here is to re-write and compile the code, so the user can easily flash it directly to the ESP32. 

In order for the user to set their WIFI, time-zone, daylight saving, location, language etc, a new menu has been written, allowing the user to easily add or change these details. Once added, they are saved internally and will remain after a power-cut. 

# Important update for those living in the Southern Hemesphere: -
use the file titled littlefs_southern.bin instead of littlefs.bin


This project is based on the original open-source code and project details found here.
https://thingpulse.com/product/esp32-wifi-color-display-kit-grande/
 
