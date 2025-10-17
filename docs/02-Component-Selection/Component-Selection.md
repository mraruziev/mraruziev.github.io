---
title: Component Selection Example
---

## Examples

### Style 1

> This is the example found in the assignment, uses more html


### Components choose for the subsystem

****

1. 1528-2335-ND Digikey resistive sensor

    ![](MFG_166_sml.jpg)

    * $1/each
    * [link to product](https://www.digikey.com/en/products/detail/adafruit-industries-llc/166/7393589?gclsrc=aw.ds&gad_source=1&gad_campaignid=20232005509&gbraid=0AAAAADrbLliL8TzXuQg7x9tLNvO4PqNgi&gclid=CjwKCAjw0sfHBhB6EiwAQtv5qagfMTuvM6EWfkF-lDEyOs6MVN03ChBavjL6tKcwhR8kXR566HCPExoCmlEQAvD_BwE)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Very Inexpensive                               | Requires solding the component |
    | Works with all types of nanoboards                      | Needs special PCB layout.                                        |
    | Meets surface mount constraint of project |

    **Rationale:** This op amp is very cheap and is compatible with any nanoboard and our board too. It provides straightforward measurement of resistanse changes. We need it for filtering amplification of the signal coming through resistive sensor and this componene texactly does that for low-cost price.

1. MCP6004-I/P-ND op-amp

    ![](images.jpeg)

    * $1/each
    * [Link to product](https://www.microchip.com/en-us/product/mcp6004)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Low-power                                             | More expensive      |
    | quad rail-to-rail I/O CMOS                                 | Slow shipping speed |
    | Direct interface with PSoC (no external circuitry required) range |

**Choice:** Option 2: OPA333 (TI) op amp

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.
