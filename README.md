# Tiles

Tiles are a modular PCB board peripherals that offer good mechanical construction with optional high power. Great industrial, automation and robotics projects to suggest just a few. The tile format is also great when you are building deck like projects consisting of up to 3 planes of assembled PCBs.

This is very much WIP, we will add more documentation soon, to learn about what tiles are you could skim through some of the older [stream recordings](https://www.youtube.com/channel/UCQSPg8L4WFBGuj_MnvQQ7Qw/videos)

[Discuss Tiles on Discord](https://discord.gg/RCGcgbQNZK)

## Each Tile Features:
* 12 High performance IO
* 2 Mixed signal IO
* 1 GPIO
* 1 I2C interface
* 2 shared control signals reset and enable
* VDD IO Logic power, +5v, High power +/-V

![Tile Schematic](schematic.png)

__Please note__ that the male headers are 1.27mm pitch dual rows of 25 pins. The odd dimensions of the tile stem from a 50mm square, which has been trimmed (0.25mm) to allow enough clearance when combined with other tiles in situ.

![Tile Layout](Layout.png)

__Notes__ Components are added to the same side as the male header which is surface mounted, this means that the components are sandwiched between the tile itself and the tile carrier, in turn this means that all components outside the dotted aperture area need to be less than 6mm in height. Those inside the marked off aperture can be significantly taller.

#Example Tiles
TBA
