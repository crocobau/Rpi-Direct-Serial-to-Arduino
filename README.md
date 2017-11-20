# Rpi-Direct-Serial-to-Arduino
This si about how to connect Raspberry Pi with Arduino using a simple USB cable
Rpi is running a tcp server on port 80 on localhost
Any client requesting URL of Rpi will trigger a serial comunication to Arduino
Arduino is running a specific sketch which ignore http headers.

Achievement is that any client can connect and send commands to Arduino using any browser.
Please keep in mind that there is a simple the USB cable between Rpi and Arduino.
