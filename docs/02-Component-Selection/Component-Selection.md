---
title: Component Selection 
---

## Examples



> There are only 2 components in my subsystem and in this website I will be sharing about those and rationale why those are choosen over other possible options.


### Components choosen for the subsystem

****

1. 1528-2335-ND Digikey resistive sensor

    ![](MFG_166_sml.jpg)

    * $3.95/each
    * [link to product](https://www.digikey.com/en/products/detail/adafruit-industries-llc/166/7393589?gclsrc=aw.ds&gad_source=1&gad_campaignid=20232005509&gbraid=0AAAAADrbLliL8TzXuQg7x9tLNvO4PqNgi&gclid=CjwKCAjw0sfHBhB6EiwAQtv5qagfMTuvM6EWfkF-lDEyOs6MVN03ChBavjL6tKcwhR8kXR566HCPExoCmlEQAvD_BwE)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Very Inexpensive                               | Shipping is too costly |
    | Works with all types of nanoboards                      | Needs special PCB layout.                                        |
    | Meets surface mount constraint of project |



2. 5475 Adafruit

    ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/003/217/472/MFG_5475_sml%28200x200%29.jpg)

    * $4.95/each
    * [link to product](https://www.digikey.com/en/products/detail/adafruit-industries-llc/5475/22162362?gclsrc=aw.ds&gad_source=1&gad_campaignid=20232005509&gbraid=0AAAAADrbLliA2QPoBJaKgRRDCe-E96ysN&gclid=CjwKCAjw0sfHBhB6EiwAQtv5qYGZCGvvPbDwf9DDm2bSefonA0HU3gFHJq1bK3vT8t_ols2fsJB0wxoCc_sQAvD_BwE)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Widely used                             | Nonlinearity in the results |
    | Better lifespan                      |                                      |
    | Easier interfacing of the components |



    3. 1738-SEN0293-ND DFrobot

    ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/100/948/661/SEN0293_sml.jpg)

    * $6.50/each
    * [link to product](https://www.digikey.com/en/products/detail/dfrobot/SEN0293/10136549?gclsrc=aw.ds&gad_source=1&gad_campaignid=20232005509&gbraid=0AAAAADrbLliA2QPoBJaKgRRDCe-E96ysN&gclid=CjwKCAjw0sfHBhB6EiwAQtv5qb1dP63M7VRu8O6ERff4Tu-m0pQPTGdx5_IjUZ6b_PNYJ37PUhoaVBoCrzEQAvD_BwE)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Wider ambient range                               | Less precise |
    | Good amount of time for the response                      |                                        |
    | thin form factor |

    **Rationale for choosing 1528-2335-ND :** This resistive sensor is very cheap and is compatible with any nanoboard and our board too. It provides straightforward measurement of resistanse changes. We need it for filtering amplification of the signal coming through resistive sensor and this componene texactly does that for low-cost price. If ordered today, its shipping is expected in 5 days

## Op amp
1. MCP6004-I/P-ND op-amp

    ![](images.jpeg)

    * $0.40/each or free
    * [Link to product](https://www.microchip.com/en-us/product/mcp6004)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Low-power                                             | Varying performance with the temperature change      |
    | quad rail-to-rail I/O CMOS                                 | Limited slew rate |
    | Low power consumption |

**Choice 2:** Option 2: MCP601-I/P IC OPAMP GP 1 CIRCUIT 8DIP


2. MCP601-I/P IC OPAMP GP 1 CIRCUIT 8DIP

    ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/300/341/924/150%7EC04-018%7EP%2C%20PA%7E8_sml%28200x200%29.jpg)

    * $0.40/each
    * [Link to product](https://www.digikey.com/en/products/detail/microchip-technology/MCP601-I-P/305930)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Fast response of 1Mhz                                             | high consumption of power      |
    | good rail-to-rail input/output                                 | Noise offset |
    | Easy for dynamic signals  |

**Choice 3:** Option 2: MCP603-I/P

3. MCP603-I/P

    ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/300/341/924/150%7EC04-018%7EP%2C%20PA%7E8_sml%28200x200%29.jpg)

    * $0.67/each
    * [Link to product](https://www.digikey.com/en/products/detail/microchip-technology/MCP603-I-P/305934?gclsrc=aw.ds&gad_source=1&gad_campaignid=20228387720&gbraid=0AAAAADrbLlh_36NL6tG2xM8sOANdgFkI4&gclid=CjwKCAjw0sfHBhB6EiwAQtv5qYySUVtsJZWfFdD2i3Bas2rJTBIOqGb7fxJG9O-PzXONhinhUFv1wRoCqyUQAvD_BwE)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Low-power consumption                                            | Not for dynamic applications      |
    | stable and reliable usage                                 | Slow signal change |
    | Low power consumption |



**Rationale for choosing MCP6004:** The opamp MCP6004 is given by Microchip and offers low power consumption and has good compatibility with the nano board I am using for the subsystem, which also belongs to Microchip. It is very low cost and there is no need for the level-shifting of the componenets if this componenet is choosen. It's shipping speed is not fast but it is given in our kit so we can easily access it.


## Voltage regulator
1. LM7805T Linear Voltage regulator

    ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/001/176/122/MFG_5536_TO-220-3L_sml%28200x200%29.jpg)

    * $0.40/each
    * [Link to product](https://www.digikey.com/en/products/detail/taejin/LM7805T/22237260)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | LVery cheap                                             | Temperature can change when it is at higher difference of voltage      |
    | Very good output current value of 1.5 A                                 | Limited slew rate |
    | Already provided to us |

**Choice 2:** Option 2: MCP601-I/P IC OPAMP GP 1 CIRCUIT 8DIP


2. LM1084IT-5.0/NOPB

    ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/100/625/374/296%7ET03B%7ENDE%7E3_sml.jpg)

    * 2.83/each
    * [Link to product](https://www.digikey.com/en/products/detail/texas-instruments/LM1084IT-5-0-NOPB/363556)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Smaller size and                                             | high consumption of power      |
    | good rail-to-rail input/output                                 | Noise offset |
    | Easy for dynamic signals  |

**Choice 3:** Option 2: MCP603-I/P

3. LM2596

    ![](https://i.ebayimg.com/images/g/m10AAOSwquxgONfC/s-l1600.webp)

    * $2.48/each
    * [Link to product](https://www.digikey.com/en/products/detail/microchip-technology/MCP603-I-P/305934?gclsrc=aw.ds&gad_source=1&gad_campaignid=20228387720&gbraid=0AAAAADrbLlh_36NL6tG2xM8sOANdgFkI4&gclid=CjwKCAjw0sfHBhB6EiwAQtv5qYySUVtsJZWfFdD2i3Bas2rJTBIOqGb7fxJG9O-PzXONhinhUFv1wRoCqyUQAvD_BwE)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Low-power consumption                                            | Not for dynamic applications      |
    | stable and reliable usage                                 | Slow signal change |
    | Low power consumption |



**Rationale for choosing MCP6004:** The voltage regulator provided to us is very good quality and is very efficient than other options provided. This voltage regulator is known by standing better operation. 


## Power supply
1. 9 V wall adapter barrel jack


    * $0.40/each
    * [Link to product](https://resources.ampheo.com/static/datasheets/cui-inc/dpd090050-p5p-tk.pdf)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Very googd proven eliability                                             | minimum voltage drop requirements      |
    | Very good output current value of 1.5 A                                 | Low current output limit |
    | Already provided to us |

**Choice 2:** Option 2: MCP601-I/P IC OPAMP GP 1 CIRCUIT 8DIP


**Rationale for choosing MCP6004:** The voltage supply is the easiest way to supply the componenets and the board and is best way.





---