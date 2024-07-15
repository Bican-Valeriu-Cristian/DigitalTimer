
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

## Next steps

<!---Next steps for users to learn more about the technology, how to revise the project to do other interesting things, etc. Don't reiterate the online documentation here; link to it if necessary. --->

## Project expectations

Describe the state of the design. For example:

* The design has been manufactured and tested / not been manufactured
* Certifications or standards that the design has been tested for / not been tested for (if relevant)

### Expected support for the project

<!---If you will reply to issues, please suggest how users should report problems or reach out. Github issues is preferable.--->

How often will you check and reply to issues or maintain and update the code? For example:
* Will reply to issues once per quarter, once a year, etc.
* No support whatsoever, code is as is

## Contributing

<!--- Include the following text verbatim--->

This project welcomes contributions and suggestions. Most contributions require you to
agree to a Contributor License Agreement (CLA) declaring that you have the right to,
and actually do, grant us the rights to use your contribution. For details, visit
https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need
to provide a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the
instructions provided by the bot. You will only need to do this once across all repositories using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/)
or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## License

<!---Make sure you've added the [Creative Commons Attribution 4.0 International Public License](https://github.com/Azure/azure-sphere-hardware-designs/blob/master/LICENSE) to the folder.--->
<!---If you have software as well as hardware in this folder, then also add [MIT license](https://docs.opensource.microsoft.com/content/releasing/license.html) to this folder as LICENSE-CODE and change the below statement to "Code in this folder is licensed under the MIT license (see LICENSE-CODE).  Any other content is licensed under the Creative Commons Attribution 4.0 International Public License (see LICENSE) -->

For details on license, see LICENSE in this directory.
