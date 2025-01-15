
# OKAI-ES200-CONTROL

Arduino sketch based around OKAI-Battery-Lib to output battery info to an i2c display

## Wiring Diagram

![Wiring Diagram](https://github.com/gavin-micks/OKAI-ES200-CONTROL/blob/main/imgs/WiringDiagram.png)


## FAQ

#### Can I use a different display?

Yes, you will likely have to change the display libraries used and modify some of the code, however it shouldn't be difficult.

#### Where did you source the components?

The components were sourced locally, however similar components can be found at the following links:

0.96in i2c OLED display module: https://www.aliexpress.com/item/1005004355547926.html

Arduino-nano-compatible Board: https://www.aliexpress.com/item/1005005135325335.html

LM2596HV DC-DC converter: https://www.aliexpress.com/item/1005006969299217.html 
-HV SKU recommended however theoretically non-HV SKU has a [maximum input voltage of 45V](https://www.ti.com/lit/ds/symlink/lm2596.pdf) even though under 40v recommended

Total cost should be under $10USD including wires and connectors. 

The case was 3D printed, and the files are availble, however an alternative could be an Altoids-style tin (metal insulated!).


## Acknowledgements

 - [OKAI-Battery-Lib](https://github.com/jsutcliff/OKAI-Battery-Lib)


