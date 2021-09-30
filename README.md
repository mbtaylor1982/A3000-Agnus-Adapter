# A3000-Agnus-Adapter

## Intoduction
With the 8372B Agnus being a rare and expensive beast this adator was designed to allow the use of the relativly common 390544 (8375) 2MB Agnus from the A500+ and A600 in the A3000. 

![A3000AgnusAdaptor](A3000AgnusAdaptor.png)


## PAL or NTSC
Unlike the 8372B which can be changed between NTSC and PAL with a jumper, the 8375 (390544) can not. 

When selecting an Agnus chip to use with this adaptor there are two choices:

1. 390544-01 PAL 2MB Agnus used in Eurpean A500+ and A600
2. 390544-02 NTSC 2MB Agnus Used in North American A500+ and A600

**Please note there may be variants of these chips with a VBB marking and these require C2 to be fitted, othermwise this can be left unpopulated.**

## Components

| Component                                   | Location  | Qty | Link |
| ------------------------------------------- | --------- | --- | ---- |
| Ceramic Capacitor, 0.1uF, 0805              | C1, C2    |  2  |  [Mouser](https://www.mouser.com/ProductDetail/710-885012207098)    |
| 74AHC1G08 Single 2-Input AND Gate, SOT-23-5 | IC4       | 1   |  [Mouser](https://www.mouser.com/ProductDetail/595-SN74AHC1G08DBVR)    |


## Thanks
Thankyou to all the people who have helped with this project.

- Tristan Zondag for testing the adaptor (1st person to get it fully working)
- [Matt Harlum Liv2](https://github.com/LIV2) RAS signal combining inspired by the [A500-2Meg-Chip-ram](https://github.com/LIV2/A500-2Meg-Chip-ram) project.
- [John Chucky Hertell](https://github.com/ChuckyGang) & Peter Mulholland, initial conversations about the idea of using an A500+ Agnus. 
