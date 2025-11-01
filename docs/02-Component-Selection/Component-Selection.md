---
title: Component Selection 
---

## Examples



> There are only 2 components in my subsystem and in this website I will be sharing about those and rationale why those are choosen over other possible options.

## **Block:** resistive sensor **Role:** Measures conductivity, resistivity of the water 

| Solution | Photo | Cost | Link | Pros | Cons |
| :---- | :---- | :---- | :---- | :---- | :---- |
| **Option 1:** 99.99% High Purity Zinc Sheet Zinc Metal Strip  | https://m.media-amazon.com/images/I/41+K9kPmmJL._SX342_SY445_QL70_FMwebp_.jpg | $9.99 | [Amazon page](https://a.co/d/eRWDBaw) | has good corrosion resistance in water and moderate electrical conductivity. Zinc coating is very easy to do | Possibility of chemical polarization in water, short lifespan at higher temperatures, inconsistent surface area |
| **Option 2:** Brass | https://m.media-amazon.com/images/I/61jDBblyKiL._SX522_.jpg | $8.99 | [Amazon link page](https://a.co/d/g7wbcfI) | cheap, decent corrosion resistance in water (admiralty brass), best mechanical properties  | Contains copper, which can leach into water, is less chemically stable, and can have inconsistent electrical contact |
| **Option 3:** Silver leaf sheets | https://m.media-amazon.com/images/I/7177HHGoueL._AC_SX679_.jpg | $8.39 | [Amazon page](https://a.co/d/fAGRZUo) | very high conductivity, antimicrobial, reasonable corrosion resistance | Mechanically soft, forms silver sulfide, which can affect readings over time |


## **Block:** Probe
**Role:** Measures conductivity, resistivity of the water directly

| Solution | Photo | Cost | Link | Pros | Cons |
| :---- | :---- | :---- | :---- | :---- | :---- |
| **Option 1:** 1528-2335-ND Digikey resistive sensor | ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/100/948/661/SEN0293_sml.jpg) | $3.95 | [Digikey product page](https://www.digikey.com/en/products/detail/adafruit-industries-llc/166/7393589?gclsrc=aw.ds&gad_source=1&gad_campaignid=20232005509&gbraid=0AAAAADrbLliL8TzXuQg7x9tLNvO4PqNgi&gclid=CjwKCAjw0sfHBhB6EiwAQtv5qagfMTuvM6EWfkF-lDEyOs6MVN03ChBavjL6tKcwhR8kXR566HCPExoCmlEQAvD_BwE) | The product itself is Inexpensive and works with any board It meets the surface mount requirements of the project | Shiping is costly, needs a special PCB layout |
| **Option 2:** 5475 Adafruit | ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/003/217/472/MFG_5475_sml%28200x200%29.jpg) | $4.95 | [Digikey product page](https://www.digikey.com/en/products/detail/adafruit-industries-llc/5475/22162362?gclsrc=aw.ds&gad_source=1&gad_campaignid=20232005509&gbraid=0AAAAADrbLliA2QPoBJaKgRRDCe-E96ysN&gclid=CjwKCAjw0sfHBhB6EiwAQtv5qYGZCGvvPbDwf9DDm2bSefonA0HU3gFHJq1bK3vT8t_ols2fsJB0wxoCc_sQAvD_BwE) | Widely used, better lifespan, easier interfacing for components | Possible nonlinearity in the results |
| **Option 3:** 1738-SEN0293-ND DFrobot | ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/100/948/661/SEN0293_sml.jpg) | $6.50 | [Digikey page](https://www.digikey.com/en/products/detail/dfrobot/SEN0293/10136549?gclsrc=aw.ds&gad_source=1&gad_campaignid=20232005509&gbraid=0AAAAADrbLliA2QPoBJaKgRRDCe-E96ysN&gclid=CjwKCAjw0sfHBhB6EiwAQtv5qb1dP63M7VRu8O6ERff4Tu-m0pQPTGdx5_IjUZ6b_PNYJ37PUhoaVBoCrzEQAvD_BwE) | Wider amount of page, good amount of time for response, thin form factor | Less precise in measurements |

**Block:** resistive sensor  
**Rationale:** This resistive sensor is very affordable and is compatible with any nanoboard, including our own. It provides a straightforward measurement of resistance changes. We need it for filtering and amplification of the signal coming through the resistive sensor, and this component exactly does that for a low price. If ordered today, its shipping is expected in 5 days.

## **Block**: Op amp 
**Role:** 

| Solution | Photo | Cost | Link | Pros | Cons |
| :---- | :---- | :---- | :---- | :---- | :---- |
| **Option 1:** MCP6004-I/P-ND op-amp | ![](https://mraruziev.github.io/02-Component-Selection/images.jpeg) | $0.40 or free | [Microchip website](https://www.microchip.com/en-us/product/mcp6004) | Low-power, quad rail-to-rail I/O CMOS, low power consumption | Varying performance with the temperature change, Limited slew rate |
| **Option 2:** MCP601-I/P IC OPAMP GP 1 CIRCUIT 8DIP | ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/300/341/924/150%7EC04-018%7EP%2C%20PA%7E8_sml%28200x200%29.jpg) | $0.62 | [Digikey product website](https://www.digikey.com/en/products/detail/microchip-technology/MCP601-I-P/305930) | Fast response of 1MHz, good rail-to-rail input/output, Easy for dynamic signals | high consumption of power, noise offset |
| **Option 3:** MCP603-I/P   | ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/300/341/924/150%7EC04-018%7EP%2C%20PA%7E8_sml%28200x200%29.jpg) | $0.67 |  | Low-power consumption, stable and reliable usage,  | Slow signal change, Not for dynamic applications |

**Choice:** MCP6004  
**Rationale:** The op-amp MCP6004, provided by Microchip, offers low power consumption and good compatibility with the nano board I am using for the subsystem, which also belongs to Microchip. It is very cost-effective, and there is no need for level-shifting of the components if this component is chosen. Its shipping speed is not fast, but it is included in our kit, so we can easily access it.

## **Block**: Voltage Regulator **Role:** Measures conductivity, resistivity of the water 

| Solution | Photo | Cost | Link | Pros | Cons |
| :---- | :---- | :---- | :---- | :---- | :---- |
| **Option 1:** LM7805T Linear Voltage Regulator | ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/001/176/122/MFG_5536_TO-220-3L_sml%28200x200%29.jpg) | $0.33 or free | [Digikey website](https://www.digikey.com/en/products/detail/taejin/LM7805T/22237260) | Very cheap, very good output value of current of 1.5 A, and it is already provided to us, so no shipping is needed | Temperature can change when it is at a higher difference of voltage, limited slew rate |
| **Option 2:** LM1084IT-5.0/NOPB | ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/100/625/374/296%7ET03B%7ENDE%7E3_sml.jpg) | $2.83 | [Digikey product page](https://www.digikey.com/en/products/detail/texas-instruments/LM1084IT-5-0-NOPB/363556) | Smaller size and good rail-to-rail input/output, Easy for dynamic signals | High consumption of power, noise offset |
| **Option 3:** LM2596   | ![](https://i.ebayimg.com/images/g/m10AAOSwquxgONfC/s-l1600.webp) | $2.48 | [Digikey product page](https://www.digikey.com/en/products/detail/microchip-technology/MCP603-I-P/305934?gclsrc=aw.ds&gad_source=1&gad_campaignid=20228387720&gbraid=0AAAAADrbLlh_36NL6tG2xM8sOANdgFkI4&gclid=CjwKCAjw0sfHBhB6EiwAQtv5qYySUVtsJZWfFdD2i3Bas2rJTBIOqGb7fxJG9O-PzXONhinhUFv1wRoCqyUQAvD_BwE) | Low-power consumption, reliable, and stable usage | Not for dynamic applications, slow signal change |

**Choice:** LM7805T  
**Rationale:** The voltage regulator provided to us is of very high quality and more efficient than the other options offered. This voltage regulator is known for providing better operation.

## **Block**: External power source (feeds the 5V source) **Role:** Measures conductivity, resistivity of the water 

| Solution | Photo | Cost | Link | Pros | Cons |
| :---- | :---- | :---- | :---- | :---- | :---- |
| **Option 1:** 9 V wall adapter SWI12-12-E-P5 | ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/002/375/864/MFG_SWI12-E_sml%28200x200%29.jpg) | $15.86 | [Digikey page](https://www.digikey.com/en/products/detail/cui-inc/SWI12-12-E-P5/5287244?gclsrc=aw.ds&gad_source=1&gad_campaignid=120565755&gbraid=0AAAAADrbLlhCXftiJluGgUch6rsfE1-Oc&gclid=Cj0KCQjwvJHIBhCgARIsAEQnWlB4qBOdHqSqQgSQOPAMrwMIgFKNVal9buI3OzWwKYeVxJLDq076t5gaAoJ2EALw_wcB) | Regulated 9 V output at 1.2 A, Universal AC input (90–264 VAC)	 | higher cost than most of other options, low current output, it is limited with low power capacity(12 W max),  no buil-in overcurrent protection output |
| **Option 2:** 2×18650 holder (7.4 V nominal) \+ buck to 5 V | ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/002/457/526/PRT-09925_sml.jpg) | $1.95 | [Digikey product page](https://www.digikey.com/en/products/detail/sparkfun-electronics/09925/6161750?gclsrc=aw.ds&gad_source=1&gad_campaignid=20243136172&gbraid=0AAAAADrbLlgSxdqAKiMGbhVU1YZ4yrhJC&gclid=CjwKCAjwjffHBhBuEiwAKMb8pMX1Q0fG5C3S9-WLJntinuMTixVbnmRQIk70FfwKcjoj_64dR--ZHRoCQQoQAvD_BwE) | Reusable cells with high power | Li-ion safety when charging is required |
| **Option 3:**  6×AA holder (9 V alkaline / \~7.2 V NiMH)  | ![](https://mm.digikey.com/Volume0/opasdata/d220001/derivates/1/003/219/285/BH26AASF_sml.jpg) | $2.37 | [Digikey product page](https://www.digikey.com/en/products/detail/mpd-memory-protection-devices-/BH26AASF/470766?gclsrc=aw.ds&gad_source=1&gad_campaignid=20243136172&gbraid=0AAAAADrbLlgSxdqAKiMGbhVU1YZ4yrhJC&gclid=CjwKCAjwjffHBhBuEiwAKMb8pKcbMlbAca3yG5dnokIfWVpUYWIoa5xC4cm2fcq-pG9dO21qW9ZxvhoChp0QAvD_BwE) | Cheap, field-portable | Voltage drops fast under load |

**Choice:** LM7805T  
**Rationale:** The voltage supply is the easiest way to supply the components and the board, and is the best way.

---