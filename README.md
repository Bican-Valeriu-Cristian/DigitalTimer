
# Digital Timer

The project involves a digital timer that counts up to one minute. Each counter's 4-bit output is fed into a binary-to-7-segment decoder, enabling number display on 7-segment displays. 
The circuit includes switches for starting/stopping the timer and resetting the count.

![WhatsApp Image 2024-07-15 at 16 40 44_299e31ab](https://github.com/user-attachments/assets/213ad60d-3f88-43cd-a523-6e26f5be1f9d)

## Contents

| File/folder | Description |
|-------------|-------------|
| `PCB.kicad_sch`       | Schematic |
| `PCB.kicad_pcb`       | PCB editor |
| `gerber`         | Altium Designer schematics, PCB layout, and supporting project files
| `README.md` | This README file. |
| `LICENSE`   | The license for the project. |

## Tools

First step:
The schematic for this project was created using KiCad software.
![image](https://github.com/user-attachments/assets/70af9907-743c-42b4-9098-a226bc5d1068)

Next was drawing the layout:

  -The PCB is a 8 cm x 8 cm 2-layer board.

  -It has a GND copper plane on both layers.

  -All signal traces are 0.254 mm, while the 5V power trace is double the size, at 0.508 mm.

  -Proper names were added for the various components, along with description text and a nice drawing.

  ![image](https://github.com/user-attachments/assets/8297ebc3-cc89-426a-9515-4b28f4dc6ea6)


The final steps were to order the parts, the PCB, and assemble the board.

  -The various components were ordered from TME
  
  -The PCB was ordered from Jlcpcb

  

## Bill of materials

-2x 7-segment displays

-2x 10nF ceramic capacitors

-1x 1uF electrolytic capacitor

-2x push switches

-2x header pins

-2x 4-bit tri-state registers

-2x 4-bit BCD decoders

-2x 4-bit counters

-2x quad AND gate chips

-1x quad NOR gate chip

-1x dual JK flip-flop chip

-Various resistors


## Final statistics

Total cost:
  Components: 100 RON
  PCB: 50 RON
Total hours of work:
  Designing schematic and testing: 3 hours
  Making layout: 3 hours
  Assembling PCB: 5 hours

## Extra photos

![WhatsApp Image 2024-07-15 at 16 51 08_b6c535b6](https://github.com/user-attachments/assets/0db0438a-ebec-4b45-b33e-eb69d2b60232)

![WhatsApp Image 2024-07-15 at 16 51 08_239efd22](https://github.com/user-attachments/assets/e20fdcaf-e616-45ec-b758-2ef99c2d87f1)


### Expected support for the project

<!---If you will reply to issues, please suggest how users should report problems or reach out. Github issues is preferable.--->

How often will you check and reply to issues or maintain and update the code? For example:
* Will reply to issues once per quarter, once a year, etc.
* No support whatsoever, code is as is


## License

For details on license, see LICENSE in this directory.
