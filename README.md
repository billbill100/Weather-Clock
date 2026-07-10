# Weather-Clock
Arduino ESP Weather Clock. Takes time and local weather data from the Internet and displays it on a 3.5" TFT screen

An ESP32 based weather clock, which connects via wi-fi, to regularly update the time and local weather.

The original project has open-source source code but requires bespoke (expensive) hardware.
I found a few issues that would stop many being able to build this weather clock. These have been overcome, allowing anybody to make the Weather Clock.

First issue was hardware. The code (open-source) is designed to run on bespoke hardware, which is both expensive to purchase and expensive to ship. This issue has been overcome by re-writing the code to work on cheap Aliexpress parts.

Second issue, is the code itself. It is very complex and unless the user is familiar with python, Visual Studio and Platform IO, they would struggle.
.
Solution here is to re-write and compile the code, so the user can easily flash it directly to the ESP32, without the need for the complexity detailed above.

The final issue is addingthe user credentials, which include your wifi details, location, language etc.
These were hard-coded within the original firmware.

This has been overcome by adding a new menu. This allows the user the user to easily add or change these details from their computer screen. Once added, they are saved internally and will remain after a power-cut. 

Languages now supported en, cz, pt,fr, de.

Latest firmware (de added) 0_0_4

 Github has no direct means of contact, my email address is
# bill bill github at gmail dot com
(remove spaces & change at to @ and dot to . )

# Important update for your Hemesphere: -
use the file littlefs_northern.bin if you are in the northern hemesphere 
or
use the file titled littlefs_southern.bin if you are in the southern hemesphire
else your moon will be upside down :o)

# New parameter added in 0_0_4 onwards
which allows thew windspeed to be shown in mph, if metric units are selected
Ideal for UK people, where mph is still used for speed and distance, with SI units for everything else.

A Pass Key has to be entered the first time the firmware is run. This is to prevent unauthorised copying and selling on sites like ebay and etsy.

The pass key is FREE and will never expire. Full details are in the user guide.

This project is based on the original open-source code and project details found here.
https://thingpulse.com/product/esp32-wifi-color-display-kit-grande/
 
