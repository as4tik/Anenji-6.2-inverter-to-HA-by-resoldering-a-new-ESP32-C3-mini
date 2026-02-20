# Anenji-6.2-inverter-to-HA-by-resoldering-a-new-ESP32-C3-mini
The inverter has a soldered communicaiton module. This repo contain a guide how to connect to HA.
<img width="410" height="564" alt="image" src="https://github.com/user-attachments/assets/e9a764d2-b432-4f4a-8f2e-8866a537bd53" />


<img width="288" height="479" alt="image" src="https://github.com/user-attachments/assets/316775c1-70e6-4fb0-a2ad-dfd7e5baf22f" />

The original YAML is taken from Ivan's repo and cutted out all lines, related to the JK BMS, connected by the Bluetooth
https://gist.github.com/ivan-rio/19ac03f3ffb8bc3d5c4aa2b271275250

Thanks, Ivan for your great job. And please let me know, should I delete any content, related to your repo, if so.

The original ESP to be unsoldered and a new one to be connected to the same contacts the original was. Be careful! The original ESP is soldered by a high temperature solder wire tin, so it needs to be 375-400 degree to unsolder. Also I damaged a one of the contacts and had to search for a replacement. Please, do not repeat my mistake!

How to solder?
On a new ESP32 I used as Rx/Tx GPIO20 and GPIO21. 
So my wiring looks like that:
<img width="392" height="555" alt="image" src="https://github.com/user-attachments/assets/61841ea8-4ba0-41db-b256-97e816f345da" />

<img width="325" height="442" alt="image" src="https://github.com/user-attachments/assets/6a435509-2047-4b20-8b72-a4e417bbfe59" />


<img width="891" height="426" alt="image" src="https://github.com/user-attachments/assets/cba37324-ca51-4750-958c-949c806abecc" />


How to output the wires?

<img width="999" height="558" alt="image" src="https://github.com/user-attachments/assets/3ce3ade1-34a1-4f17-b503-4b6e6cd0834a" />


