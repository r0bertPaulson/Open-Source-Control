# Open-Source-Control
Collection of Open Source IoT Designs

-Unitary Controller Version 1.0-
This device will be suitable for control of automated and networked building equipment at the unitary level. For example, you could control a single airconditioner unit with this device. This design has be superseded by Version 2.0

-Unitary Controller Version 2.0-
6 input, 5 relay output controller board using OSD3358-512M-ICB (C-SiP). Changed to C-SiP due to advantages of a fully encapsulated EMMC and main oscillator in an industrial temperature rated package.

Project Status:
1) Version 1.0 will not be built or tested and has been superseded by Version 2.0.
2) Prototype Version 2.0 has been built. Revisions will be incorperated into 2.1 (future)
3) Version 2.0 in testing. EEPROM programmed to BBB. Device boots Debian images correctly. Main communication interfaces 
(USB, Serial, Ethernet) seem to work correctly.
4) There is an error in the I2C bus connected to the RTC caused by renaming to I2C1 which caused the SCL trace to become disconnected. Flaw cannot be reworked as it is under the SiP package. To be fixed in 2.1
5) Isolated RS-485 + and - pins/silkscreen are backwards. Pins to be swaped in 2.1
