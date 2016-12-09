## ArduinoNFC v3.2
ArduinoNFC is a DIY security solution that uses RFID technology with the help of an Arduino. It is named NFC because it uses NFC tags in combination with RFID readers interfaced to the Arduino.

The system uses an Arduino UNO interfaced with a RFID reader that reads a tag. The EEPROM of the arduino is used to store the authorised tag values. Everytime a user brings his/her tag in front of the reader the system compares the read value with the ones stored in the database(EEPROM). The Electromagnetic Lock is controlled using a relay board, so every time the system finds a match it triggers a output pin to HIGH which inturn triggers the relay, unlocking the door. The electromagnetic lock can withstand 600lbs of force.

**NOTE: ** This system was combined with a raspberry pi running a face recognition script to increase the level of security.

*The eagle schematic and board files for the relay board design have been included.*
