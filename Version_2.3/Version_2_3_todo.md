Version 2.3 To Do:

1) Create I2C connection for Sensirion Air Flow Sensor by adding Molex Plugable Terminal PN 5023520400.
2) Create connection for Analog Output Add-On board.
3) Replace 5V Regulator Power Inductor (L2) with Bourns PN SRP1265A-470M. {DONE}
	Existing Footprint:
	178 id
	530 od
	500 ht
	216 pad ht
	Use DR127 Footprint from Library.
4) Find alternate compatible crystal for Ethernet Phy. ABM3-25.000MHZ-J2Y-T (also used for Micrel) 
	or alternatively use the direct replacement from Digikey ECS-250-12-30-GN-TR? {DONE}
5) Update Crystal Footprint and device (Y7) with generic 5x3.2mm 2-SMD {DONE}  
5) Change Relay Output terminal blocks to 12 position version with C, N.O. and N.C. terminals.
6) Add capability for add-on Relay HOA board.
7) Update Relay part number to G5LE due to JS1 EOL.