# Defcon-SAO

This project is to create a simple and Fun PCB that works for Defcon as a SAO. Made this because my dad was lazy and didn't want to do it, @ElJjefeDSecurIT.

This will inclued:
  - 0.1" 2x3 connector to connect with badges and other stuff
  - Resistors
  - Right angle or back lighting LEDs
  - cool pirate


Schematic:

![image](https://github.com/user-attachments/assets/e84a929e-b017-4076-8964-54997b612178)

For the schematics, I implemented 3 LEDs, one for each of the clear parts on the PCB where there will be no soldermask, copper, or silkscreen. The resistors are marked with x as the resistances will vary depending on the LEDs used. This means that for blue LEDs there will be lower ohm resistors and for Red LEDs there will be higher ohm resistors. To calculate the resitance of the resistors, I used ohms law, V=IR, using the voltage drop I wanted over the resistor for V and the desired forward current for each LED as I. For the LEDs in parralell I simply doubled the forward current for one LED and then calculated the resistance.

Board Layout:

![image](https://github.com/user-attachments/assets/e40293ac-76a4-47df-85af-6809fb8988d6)

The circuit is quite simple so routing wasn't too difficult. There are two copper pours, one on each side that are connected to ground, and Power traces that are 0.5 mm thick. The parts were set on the back of the PCB to provide a nice finish on the front while allowing the PCB to still glow from the back.

3d Model:


![image](https://github.com/user-attachments/assets/9af6ba39-46d6-4e2c-aa89-c2213067db0c)


![image](https://github.com/user-attachments/assets/e583210c-0667-4492-b7eb-61120adf39ca)



As you can see, the Pirate is fully visible from the front with no traces or parts to obstruct it.





Assembly:

I ordered 165 pirates for assembly to bring to Defcon. They were assembled by hand using a reflow oven, solder paste for the SMD components, and hand soldered through hole pins.


![20240801_133758](https://github.com/user-attachments/assets/19c3fc1b-7595-4982-bd73-baa7fc098dc8)
This board is assembled with solder paste and SMD components

![20240802_132457](https://github.com/user-attachments/assets/24db2c3d-f117-489d-8156-5dcfabfd014a)
Placing the board in the reflow oven


![20240805_122421](https://github.com/user-attachments/assets/df95818c-d73e-47fe-bcf7-1ad1004f0b0d)
Single fully soldered board

![20240805_163503](https://github.com/user-attachments/assets/d65f6fe7-dd9b-41a5-8d29-208f2a5fb9a0)
all 155 fully assembled and soldered boards, upwards of 800 SMD components and almost 1000 through hole pins.



Finalized Board:
![pirate](https://github.com/user-attachments/assets/67b2bfb4-c954-47fd-8d72-d814ea2c1095)
