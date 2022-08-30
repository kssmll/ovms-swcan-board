# SWCAN Expansion Board for OVMS
SWCAN Expansion Board for [OVMS (Open Vehicle Monitoring System)](https://www.openvehicles.com/).
The board is used for supporting 1-wire swcan bus in OVMS for GM vehicles. Tested with Chevrolet Volt. Can be suitable for Opel Ampera, Chevrolet Bolt, other GM cars.
![ovms](https://github.com/kssmll/ovms-swcan-board/blob/main/PCB1.jpg)

OVMS firmware must be compiled with the swcan module selected in the configuration. 
### Installation
Insert the board to the expansion slots. In some OVMS PCBs GEP7 is not routed to DSUB9_1. In this case you need to manually connect SWCAN J4 on the adapter board to DB9 pin1. Then the car's swcan bus must be connected to DB9 pin 1, not to CAN2.
![ovms](https://github.com/kssmll/ovms-swcan-board/blob/main/PCB2.jpg)
### Parts List
| Ref | Desc|
| --- | ----|
| U1 | MCP2515ISO |
| U2 | TH8056 SO14 |
L1|47uH|
|X1|16mhz|
|R1|10k|
|R2|10k|
|R3|10k|
|R4|10k|
|R5|NC|
|R6|NC|
|R7|1k|
|R8|6.49k|
|C1|0.1u|
|C2|22pf|
|C3|22pf|
|C4|100pf|
|C5|100pf|
|C6|0.1u|
|C7|10u|
|J1|14 pin, 2mm pitch, 2pcs|
|J2|NC|
|J3|NC|
|J4|SWCAN, connect only if GEP7 not routed to DSUB9_1 in the OVMS board.|
|J5|NC|
|J6|NC|
|J7|NC|

### Order PCB
You can order PCB manufacturing with already uploaded gerber at [PCBWay](https://www.pcbway.com/project/shareproject/SWCAN_adapter_for_OVMS_b002c070.html)
