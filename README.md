# SkyRfidJavaApp
***************
Description
Description: 
Java FX application that uses the Sky RFID USB reader to read and write ISO 15693 tags.
The application is built upon the 32-bit JVM platform for compatibility with the 
manufacturer's 32-bit dll. This dll must be in the windows\sysWOW64 folder on 64-bit computers.

Manufacturer's website: 
http://www.skyrfid.com/index.php?pr=Readers_HF_1356

A Java Native Access interface is used to access dll functions in place of the 
manufacturer's javacall class because this class lacks critical functions.


