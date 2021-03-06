## DroneCore.Power - Firmware update
This section describes how to update firmware in main MCU of DroneCore.Power board.

- at first download and unzip [Airvolute_firmware_updater.zip](...add link ...) on Windows host PC.
- connect Alink usb-serial converter from host PC to CONFIG connector of the .Power board
- leave power supply to DroneCore.Power turned off
- open application and choose corresponding COM port (COM port number can be checked in Device Manager)
- other settings leave default with "Use Default Settings" checkbox checked
<img src="uploads/b7e1c30a5e587568e82a56bd64755b37/firmware_update1.jpg"  width="550"> 

- click on the "Connect" button
<img src="uploads/96aae8a9b4fca9eb45aef9f6e763bb0b/firmware_update2.jpg"  width="550"> 

- if application successfully connects to Alink, choose processor option as "STM", and click on "Ping" button.

<img src="uploads/80d29c9340df8c80dfd26ce6bad2d0a2/firmware_update3.jpg"  width="550"> 

- now application is waiting for device connection
- connect power supply to DroneCore.Power board and application should automatically recognize AV_PB6S40A Device type

<img src="uploads/dca2a0dd67d065e25cbe7dd60c3b5fd4/firmware_update4.jpg"  width="550">  

- now if device is checked and recognized click on "Browse File" button and search for firmware binary in your filesystem 
- than click on "Write File"
- wait while writing is in progress

<img src="uploads/471ef9d7a948d4a81b6804db0e8a7084/firmware_update5.jpg"  width="550"> 

- after writing is complete click on "Disconnect" button to close COM port

<img src="uploads/77cfbd09f02551934bfac584ceff3e3a/firmware_update6.jpg"  width="550">
 
- now firmware is updated and device is running
