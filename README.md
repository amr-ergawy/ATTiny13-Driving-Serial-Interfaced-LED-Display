# ATTiny13-Driving-Serial-Interfaced-LED-Display

This is an ATTiny13 based hosting board and software driver for the serial-interfaced LTM-8522 LED display.

I developed this project to try two interesting things:

1. Developing a board that can host a serially interfaced LED display module. I.e. providing the module with necessary power and data wiring, to the ATTiny13.
2. Developing a software driver for the serially interfaced LED display that can fit in the less than 1K bytes flash memory of the ATTiny13. This means the driver shall allow room in the flash memory for a test program or another application.

A testing program that continously counts, displaying on the LED display, is included.

A detailed hardware diagram is included in this repository as a PDF file.

As ToDo:
- I need to review the hardware interface of the test button to handle noise.
- I need to separate the test program and the driver into two separate files.

For more info and demo video, see the project web site:
https://sites.google.com/site/aergawyprojects/microcontroller-projects/attiny13-driving-serial-interfaced-led-display
