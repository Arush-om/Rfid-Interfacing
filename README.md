# Rfid-Interfacing

![Screenshot (1241)](https://github.com/Arush-om/Rfid-Interfacing/assets/134673721/bdc41500-86c8-4dad-86c3-bd2389947b19)

If you have hard-time 3d printing stuff and other materials which i have provided in this project please refer the professionals for the help, [JLCPCB](https://jlcpcb.com?from=ayu ) is one of the best company from shenzhen china they provide, PCB manufacturing, PCBA and 3D printing services to people in need, they provide good quality products in all sectors

[JLCPCB](https://jlcpcb.com?from=ayu)


Please use the following link to register an account in [JLCPCB](https://jlcpcb.com?from=ayu )

https://jlcpcb.com?from=ayu 


Pcb Manufacturing

----------

2 layers

4 layers

6 layers

jlcpcb.com/RNA

PCBA Services

[JLCPCB](https://jlcpcb.com?from=ayu ) have 350k+ Components In-stock. You don’t have to worry about parts sourcing, this helps you to save time and hassle, also keeps your costs down.

Moreover, you can pre-order parts and hold the inventory at [JLCPCB](https://jlcpcb.com?from=ayu ), giving you peace-of-mind that you won't run into any last minute part shortages. jlcpcb.com?from=ayu 


3d printing

-------------------

SLA -- MJF --SLM -- FDM -- & SLS. easy order and fast shipping makes [JLCPCB](https://jlcpcb.com?from=ayu ) better companion among other manufactures try out [JLCPCB](https://jlcpcb.com?from=ayu ) 3D Printing servies

[JLCPCB](https://jlcpcb.com?from=ayu ) 3D Printing starts at $1 &Get $54 Coupons for new users

Otto is an interactive robot that anyone can make!, Otto walks, dances, makes sounds and avoids obstacles. Otto was inspired by another robot instructable BoB the BiPed and programmed using code from another open source biped robot called Zow

All The 3D Printable Files Are Included In The Repository Other Variants Can Be Found HERE & Official OTTO STORE

![Screenshot (1244)](https://github.com/Arush-om/Rfid-Interfacing/assets/134673721/c0d4d66e-e9dd-4f64-9df1-a504d6d46200)
![Screenshot (1242)](https://github.com/Arush-om/Rfid-Interfacing/assets/134673721/f85c1725-500c-4256-84de-c1717098ab54)

RC522 RFID Reader with Arduino and use MIFARE Classic 1K RFID Card and Key Fob. The RC522 Module is based on NXP’s MFRC522 RFID Reader / Writer IC operating at 13.56 MHz

RFID is short for Radio Frequency Identification. As the name suggests, RFID uses electromagnetic waves in radio frequency to transfer data. A simple RFID System consists of just two components: an RFID Transponder and an RFID Transceiver.

The RFID Transponder is usually a Card, Tag, Key Fob or a Sticker while the RFID Transceiver is a reader / writer device capable of reading and writing data from / to an RFID transponder.

The RFID uses arduino aong with wires connected with spi pins and the connecting with MISO & MOSI pins


C522 – RFID Reader / Writer 13.56MHz with Cards Kit includes a 13.56MHz RF reader cum writer module that uses an RC522 IC and two S50 RFID cards. The MF RC522 is a highly integrated transmission module for contact-less communication at 13.56 MHz. RC522 supports ISO 14443A/MIFARE mode.

RC522 – RFID Reader features an outstanding modulation and demodulation algorithm to serve effortless RF communication at 13.56 MHz. The S50 RFID Cards will ease up the process helping you to learn and add the 13.56 MHz RF transition to your project.

The module uses SPI to communicate with microcontrollers. The open-hardware community already has a lot of projects exploiting the RC522 – RFID Communication, using Arduino.
![Screenshot (1246)](https://github.com/Arush-om/Rfid-Interfacing/assets/134673721/b0d186d1-d8b7-4ef0-9210-014320808c45)

![Screenshot (1245)](https://github.com/Arush-om/Rfid-Interfacing/assets/134673721/4da5183f-95eb-4a83-aec7-af878c3200ca)



This library read and write different types of Radio-Frequency IDentification (RFID) cards on your Arduino or NodeMCU using a RC522 based reader connected via the Serial Peripheral Interface (SPI) interface. Before we move to actual code lets know more about RF ID.


The MFRC522 IC supports a wide variety of RFID Tags like MIFARE 1K, MIFARE 4K, MIFARE Mini and other ISO / IEC 14443 protocol based cards and tags. It operates at 13.46 MHz frequency and the operating range is up to 50 mm. The MFRC522 IC supports three types of serial communication with the host (Microcontroller like Arduino).

They are:

SPI
UART
I2C

MFRC522 RFID Reader IC and RC522 RFID Reader Module, let us now proceed with Arduino RC522 RFID Card Reader Interface. As mentioned earlier, MFRC522 supports SPI, UART and I2C interfaces.

But SPI is the fastest of the three with data rates up to 10 Mbit/s. So, in this project we will see how to interface RC522 RFID Module with Arduino using SPI.

Coming to Arduino’s SPI, instead of using software SPI with bit-banging, we will use the hardware SPI. This means that SPI pins in Arduino are fixed (at least for MOSI, MISO and SCK).

![Screenshot (1247)](https://github.com/Arush-om/Rfid-Interfacing/assets/134673721/7a8bba21-101a-45a2-a190-2af40565c1f0)
![Screenshot (1248)](https://github.com/Arush-om/Rfid-Interfacing/assets/134673721/f6ef1f2c-b75f-4135-a21a-0796af3c0d9f)
![Screenshot (1251)](https://github.com/Arush-om/Rfid-Interfacing/assets/134673721/2403094e-5712-49d2-9a8f-c14a8450aa53)

Compile and upload the sketch to Arduino and open the serial monitor. The RC522 RFID Reader is waiting for an RFID Tag to be detected. So, take the card, which you got in the kit and place it in the proximity of the RFID Reader (close to the antenna).

You have to hold the card in that position for couple of seconds until all the data is printed. Do not take out the card too soon. You will get an error message “Timeout in communication” if you remove the card early. Once all the information is printed, you can take out the card.

Upload the sketch and open the Serial Monitor. As soon as you bring the tag closer to the module, you’ll probably get something like the figure given below. Do not move the tag until all the information is displayed.

In this example project , it displays all the useful information about the tag including tag’s Unique ID (UID), the memory size and the whole 1K memory.The 1K memory of the Tag is organized in 16 sectors (from 0 to 15)Each sector is further devided in to 4 blocks (block 0 to 3).Each block can store 16 bytes of data (from 0 to 15).The Block 3 of each sector is called Sector Trailer and contains information called Access Bits to grant read and write access to remaining blocks in a sector. That means only the bottom 3 blocks (block 0, 1 & 2) of each sector are actually available for data storage, meaning we have 48 bytes per 64 byte sector available for our own use.Also The Block 0 of sector 0 is known as Manufacturer Block/Manufacturer Data contains the IC manufacturer data, and the Unique IDentifier (UID)

![Screenshot (1254)](https://github.com/Arush-om/Rfid-Interfacing/assets/134673721/3576a04f-9a9e-4909-be46-b4e79e582442)
![U![Screenshot (1253)](https://github.com/Arush-om/Rfid-Interfacing/assets/134673721/26ac72de-43fc-4a74-9e8f-f983de80cd5b)

The connection of the RFID reader is given to the Arduino as follows:

3.3V is given to the 3.3v pin of Arduino
RST is given to the digital pin 9
GND is given to the ground pin of the arduino
IRQ is not connected
MSO is connected to digital pin 12
MOSI is connected to digital pin 11
SCK is connected to the digital pin 10
SDA is connected to the digital pin 9

Each RFID transponder has an identification number that may be a 7-byte long Unique Identity Number (UID) or 4-byte long Non-Unique Identity Number (NUID). The main component of an RFID card/tag/sticker is an RFID chip. The RFID chips can be read-only or programmable. The UID or NUID of a read-only card cannot be changed or modified, including other data stored on the chip. The programmable chips usually come with a preprogrammed chip ID code that can be overwritten with additional memory using an RFID transceiver.

NXP’s RC522 RFID reader is designed to read/write RFID transponders based on ISO/IEC 14443 protocol, including MIFARE and NTAG RFID cards/tags/stickers. The reader is referred to as Proximity Coupling Device (PCD), and the tags/stickers/cards are referred to as Proximity Integrated Circuit Card (PICD). The reader can communicate with a controller/computer using SPI, I2C, and UART protocols. It reads/writes tags over 13.56 MHz frequency with an operating range of 50 mm. The RC522 reader has an MFRC522 chip, a 27.12 MHz oscillator, RF antenna, and other components onboard. The operating voltage of the reader is 2.5~3.3V. However, the communication port on the reader is 5V tolerable. Therefore, it can be directly interfaced with 5V microcontrollers like Arduino

At present, there are several Arduino libraries available for RC522. The library used in this project is Arduino MFRC522 Library from miguelbalboa, available at Github. Download the library as a ZIP file. Navigate to Sketch->Include Library->Add .ZIP Library in Arduino IDE. Select the rfid-master.ZIP, and the library for RC522 is added to the Arduino environment.

Dumping RFID tag data to Serial Monitor

The Arduino library for RC522 itself comes with a lot of examples. One of the useful examples is DumpInfo. This example reads all the data on the RFID transponder chip and prints it to the Serial Monitor. Navigate to Files->Examples->MFRC522->DumpInfo.

VCC (3.3v):- Connect the VCC pin to the 3.3V pin of the Arduino. Connecting it to the 5v Arduino pin can destroy the RFID module.

RST:- This pin is for resetting the module.

GND:- This pin connects to the GND pin of Arduino.

IRQ:- This is blocking or interrupt pin that can alert the microcontroller when it comes around the RFID tag.

MISO/SCL/TX:- This pin is Master-In-Slave-Out. It acts as serial data output and connects to the Arduino RX pin.

MOSI:- Master-Out-Slave-In pin is SPI input to the RC522 module.

SCK:– Serial Clock is accepting clock pulses provided by Arduino.

SS / SDA / Rx:- When the SPI interface is enabled it acts like Signal input when the I2C interface is enabled it acts like Serial data and acts as Serial data input when the UART interface is enabled. This pin usually connects to the Arduino TX pin.

Upload the above sketch to Arduino UNO/Arduino MEGA after making the proper circuit connections. Open Serial Monitor and set the baud rate to 9600. On contacting a tag/card/key, the NUID of the respective tag/card/key is read and displayed on the Serial Monitor in decimal and hexadecimal formats. The Sketch also compares the tags/keys with a given NUID to demonstrate access control using RFID cards/keys.

The sketch begins with importing SPI and MFRC522 libraries for working with RC522 RFID readers via SPI protocol. The pin assignments for SDA and Reset are defined, and an object of MFRC522 is instantiated with those pins. A variable to store the MIFARE key is defined. A byte array ‘ nuidPICC[]’ is defined to store 4 bytes of RFID NUID. Variables are declared to store string representations of the NUID in decimal and hexadecimal formats. Similarly, a variable to store a string representation of the MIFARE key is defined.

![Screenshot (1256)](https://github.com/Arush-om/Rfid-Interfacing/assets/134673721/c6297de9-2a46-4659-a27f-16f3deafe31f)
![Screenshot (1255)](https://github.com/Arush-om/Rfid-Interfacing/assets/134673721/df2e9814-e161-4fa3-a189-6e732248d9a7)

In the setup() function, the baud rate for serial communication with Serial Monitor is set to 9600 bps using Serial.begin() method. The SPI protocol is initialized using the SPI.begin() method. The RFID module initializes the PCD_Init() method on the RFID object. The MIFARE key bytes are set to FF and stored in an upper-case string representation. The MIFARE key is published on the Serial Monitor.

![Screenshot (1258)](https://github.com/Arush-om/Rfid-Interfacing/assets/134673721/3b1423f8-2af9-43ae-8236-b033ddfaaa29)
![Screenshot (1257)](https://github.com/Arush-om/Rfid-Interfacing/assets/134673721/2e999563-1453-4ba5-bf8b-d3b193c61751)

In the loop() function, RFID card/key/tag is detected by calling PICC_IsNewCardPresent() method on the RFID object. Next, the card NUID/UID is read by calling the PICC_ReadCardSerial() method on the RFID object. The MIFARE card type is detected using the PICC_GetType(rfid.uid.sak) method and displayed on the Serial Monitor. Next, the individual bytes of the NUID is accessed using the rfid.uid.uidByte[] property. First, the bytes are serialized in decimal format and converted to a string object. The string containing a decimal representation of NUID is published on the Serial Monitor. Next, the bytes are serialized in hexadecimal format and converted to a string object. The string containing a hexadecimal representation of NUID is published on the Serial Monitor. The read bytes of NUID is stored in a character array. This character array is compared to a predefined NUID using user-defined compareNUID() function. The function returns a boolean value used to determine access control. The reader is stopped from reading the card by calling PICC_HaltA() method on the rfid object. Finally, the encryption is stopped by calling PCD_StopCrypto1() method on the RFID object.
