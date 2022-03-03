# atsamd_arduino
This repo contains hardware definitions to add the pc5001a PCB to the Arduino IDE. The following set up steps assumes the user is running Ubuntu. Steps for other operating systems are similar although the menu entries in the IDE may differ slightly from those called out in the set up steps.
## Install Dependencies
* Open the Arduino IDE, navigate to Tools->Board->Board Manager and install **Arduino SAMD Boards**
* Install support for Adafruit SAMD processors in the Arduino IDE described on [the Adafruit website](https://learn.adafruit.com/adafruit-feather-m0-adalogger/setup)
## Set up PC5001A PCB
* With the Arduino IDE open, navigate to File->Preferences and add https://raw.githubusercontent.com/sabantoag/atsamd_arduino/main/boards/package_pc5001a_index.json as an additional board
* After adding the URL, navigate to Tools->Board->Board Manager and install **Sabanto Ag Boards**
