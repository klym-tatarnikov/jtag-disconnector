# jtag-disconnector
Debug probe disconnector. <br/>
This adapater designed for power measurement, debug (deep-)sleep and low power modes on battery powered devices such as Bluetooth Low Energy, Zigbee, LoRa, etc.<br />
Normally for measuring power consumption of low power devices debug probe needs to be fully disconnected to exclude all parasitic current sources/sinks. <br />
Switching is carried out using 5V reed relays. Controlled by toggle switch or external trigger. <br />
PIN20 of JTAG connector can be used for powering device as well as to control relays. 


## Schematics
![Alt text](schematics/schematics.png?raw=true "Schematics")

## J-Link connection
![Alt text](img/front.jpg?raw=true "Front")

![Alt text](img/back.jpg?raw=true "Back")

## Segger J_Link EDU-Mini connection
![Alt text](img/edu_mini.jpg?raw=true "EDU Mini")
