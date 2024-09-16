# Weather-Clock
Arduino ESP Weather Clock. Takes time and local weather data from the Internet and displays it on a 3.5" TFT screen

An ESP32 based weather clock, which connects via wi-fi, to regularly update the time and local weather.

The original project has open-source firmware but requires bespoke (expensive) hardware.
However, I found a few issues that would stop many being able to build this weather clock. These have been overcome, allowing anybody to make the weather station.

First issue was hardware. The firmware (open-source) is designed to run on bespoke hardware, which is both expensive to purchase and expensive to ship. This issue has been overcome by re-writing the code to work on cheap Aliexpress parts.

The second, is the firmware itself. It is very complex and unless the user is familiar with python, Visual Studio and Platform IO, they would not be able to load the firmware.
Solution here is to re-write and compile the code, so the user can easily flash it directly to the ESP32. 
In order for the user to set their WIFI, time-zone, daylight saving, location, language etc, a new menu has been written, allowing the user to easily add or change these details. Once added, they are saved internally and will remain after a power-cut. 
