# joyadapter
Adapter for two 9 pin digital joysticks (C64, Atari, ...) to USB

# Contributors:

Grigory Goronzy
- initial breadboard realisation and initial firmware based on avrusb software

Christian Starkjohann, OBJECTIVE DEVELOPMENT Software GmbH 
- v-usb (former avrusb) Atmel USB software driver http://www.obdev.at/products/vusb/index-en.html

Andreas Paul
- printed circuit board design
- porting firmware from avrusb to v-usb
- firmware changes for matching free licence requirements (VID/PID, USB description)
- firmware changes for ATtiny4313 compatibility
- firmware compiled with avr-gcc 4.5.2

Philipp Lang
- complete reimplementation of software part
