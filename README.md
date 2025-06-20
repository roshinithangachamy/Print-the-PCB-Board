## Exp 10: Fabrication and Component Assembly of Printed Circuit Boards for Automatic Street Light Control

## AIM:
To fabricate a printed circuit board (PCB) for the automatic street light control system and to assemble & solder all the electronic components onto the board as per the circuit design, ensuring proper functionality of the system.
## EQUIPMENT REQUIRED:
● Hardware: Personal Computer (PC)

● Software: Mach3 Mill

● PCB Prototype machine

## PROCEDURE:
1. Turn ON the PC and power up the PCB MATE CNC machine.

2. Launch the Mach3 Mill software on the PC.

3. Secure the copper-clad board onto the PCB MATE machine’s work area using double-sided tape to prevent any movement during operation.

4. Set the spindle to manual mode for initial positioning.

5. Move the spindle to the desired starting location on the board where engraving, drilling, and cutting operations will be performed, and set the X, Y, and Z coordinates manually.

6. Switch the spindle to PC mode, then set the same X, Y, and Z values in the Mach3 software. Navigate to the Offset tab, select G54, and save the work offset values.

7. Load the auto-leveled engraving file into Mach3 by selecting File > Load.

8. Insert the appropriate tool bits (engraving, drilling, cutting) into the correct tool holders.

9. Click “Refer All Home” to zero all axes, then select “Cycle Start” to begin the process.

10. For auto-leveling, connect the magnet above the PCB board and attach the probe wire to the tool bit, ensuring the surface level is properly detected.

11. Press Cycle Start again to begin the engraving process; the machine will follow the auto-leveled G-Code and engrave the circuit pattern.

12. After engraving is complete, load the Drill file and press Cycle Start to perform all drilling operations.

13. Once drilling is done, load the Cut file and start the cutting operation to shape the PCB outline.

14. After the cutting process is completed, carefully remove the PCB from the machine.

15. Proceed with the masking process: Apply photoresist ink on the board and cover it with a printed OHP sheet.

16. Place the board in a UV exposure machine for approximately 1 minute and 25 seconds to develop the PCB layout.

17. Once the board is developed, assemble all the electronic components on the bare PCB according to the circuit design.

18. Solder all the components securely onto the board.

19. Finally, test the circuit by powering it ON and checking the output functionality.

## THEORY:
Mach3 Mill is a popular software used for controlling CNC (Computer Numerical Control) milling machines. It's commonly employed in various manufacturing processes, including PCB (Printed Circuit Board) fabrication. Here's an overview of Mach3 Mill software in the context of PCB engraving, drilling, and cutting:

## Purpose:
Mach3 Mill software serves as a control interface for CNC milling machines, enabling users to: Engrave: Create intricate designs, patterns, or labels on PCB surfaces. Drill: Precisely drill holes for component placement and interconnects on PCBs. Cut: Mill out PCB outlines, remove excess material, and separate individual boards from larger panels.

## Functionality:
G-code Interpretation:
Mach3 Mill interprets G-code instructions generated by CAD/CAM software and translates them into motion commands for the CNC machine's stepper motors or servo motors.

## Motion Control:
The software provides control over multiple axes (X, Y, and Z) of the CNC machine, allowing for precise movement and positioning of the milling tool.

## Toolpath Generation:
Mach3 Mill generates toolpaths based on the input G-code, specifying the exact movements and cutting parameters required for engraving, drilling, or cutting operations.

## Spindle Control:
It manages the rotation speed and direction of the spindle or milling tool, ensuring optimal cutting performance and tool life.

## Simulation:
Some versions of Mach3 Mill offer simulation capabilities, allowing users to preview toolpaths and visualize the machining process before actually running the CNC machine.

## Benefits:
## Precision:
Mach3 Mill enables highly precise control over the CNC machine's movements, resulting in accurate engraving, drilling, and cutting operations on PCBs.

## Versatility:
The software supports a wide range of machining tasks, making it suitable for various PCB fabrication processes, from prototyping to production. Customization: Users can customize cutting parameters, toolpaths, and other settings to optimize performance and achieve desired results for specific PCB designs.

## Integration:
Mach3 Mill integrates seamlessly with CAD/CAM software, allowing for efficient design-to-manufacturing workflows and easy generation of G-code for PCB machining.

## Compatibility:
Mach3 Mill is compatible with a wide range of CNC milling machines, including routers and engravers commonly used in PCB manufacturing. It runs on Windows-based computers and interfaces with CNC hardware through parallel port or USB connections.

## Implementation:
Implementing Mach3 Mill involves installing the software on a compatible computer, configuring it to communicate with the CNC machine, and setting up parameters for the specific machining tasks required for PCB fabrication. Operators typically undergo training to familiarize themselves with the software's features and operation.

## PCB PTH Assembling and Soldering:
Plated Through-Hole (PTH) PCB assembly involves inserting component leads through pre-drilled holes that are plated with a conductive material. These holes connect different layers of the PCB, allowing electrical signals to pass between them. PTH components typically include connectors, transformers, and large capacitors, which provide strong mechanical bonds and are ideal for high-stress applications. The assembly process begins with manual or automated insertion of components, followed by inspection to ensure correct placement and orientation. Soldering in PTH assembly is commonly done using wave soldering or hand soldering techniques. In wave soldering, the entire underside of the board is passed over a wave of molten solder, bonding all component leads to the PCB pads simultaneously. For low-volume or sensitive assemblies, manual soldering using a soldering iron is preferred for precision. Proper soldering ensures durable connections and prevents issues like cold joints or insufficient solder, which can affect circuit performance and reliability.
## EXPECTED OUTPUT:
### Fabrication board:
![446371988-65415028-4af7-48d4-b928-1813edf398ed](https://github.com/user-attachments/assets/a413027e-d8d9-47df-b4be-fe75b41d9057)

### Final Printed Circuit Board:
![446372019-dba3320e-9bcf-4b8c-bfaa-ea48f7cd1898](https://github.com/user-attachments/assets/91f984b7-3932-4f66-bb33-f97ce0b34d17)

## RESULT:
Thus, the printed circuit board for the automatic street light control system was successfully fabricated using CNC milling and UV masking techniques. All components were assembled and soldered onto the PCB, and the final circuit was tested to verify its correct operation.

