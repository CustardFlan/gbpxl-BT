# gbpxl-BT
Game Boy Printer Emulator, direct print to generic Bluetooth Thermal printers using a ESP32


The basics:
a ESP32 Board (i used a MH-ET Live Minikit for this project)
The pins for the Game Boy cable are declared on gameboy_printer.cpp file inside gbp folder
a Bluetooth Thermal printer capable of understanding ESC/POS commands (Neither PeriPage or Paperang are supported, because these printers use a CRC32 and a secret key to communicate)

Please configure your printer name/MAC address/PIN Code for pairing (sually is 1234 or 0000) inside the gbpxl-bt.ino file


Open the gbpxl-bt.ino with your Arduino IDE, verify and upload....
...

Success!
