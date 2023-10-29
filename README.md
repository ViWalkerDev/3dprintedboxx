# 3dprintedboxx
DIY-Boxx controller using fully 3D printed enclosure. Designed for printing on Ender 3 with no supports. An enclosure is provided for a button-boxx and a key-boxx (to be completed).

Button-Boxx Info:

![image](https://github.com/ViWalkerDev/3dprintedboxx/assets/112364190/6894efa9-a0f3-4773-bdb2-2bca43cbf3ce)


Files Provided:
- Filleted STEP file ready for printing.
- Unfilleted STEP file for easier remixing.

Print Orientation:
- Print all the parts with the largest flattest surface on the build plate (the top for the top pieces, and the bottom for the bottom pieces).

Supports: 
- Assuming correct print orientation and that your printer can handle a 45 degree overhang for the interface tabs, zero supports are required. 

Hardware required: 
- 10 x m3x25mm machine screws/bolts (designed for countersunk but button is also fine). 20mm bolts are also likely to work just as well, I just used 25mm because it's what I had lying around. 
- 10 x m3 threaded heatset inserts.
- Front IO connector of your choice (you will need to design and print the appropriate panel to interface with the enclosure).
- Buttons and Electronics (micro controller, key matrix solution/pcb etc).

Things you may want to remix:
- You can remix to require less joining hardware if you feel that the 10 bolts and inserts are excessive (you could probably get away with 5/6/8).
- The button boxx is modelled to accept 22 x Sanwa OBSF-24 and 1 x Sanwa OBSF-30 buttons and modelled for my own printer tolerances. You may need to change the size of the button holes and thickness of the front panel depending on your desired buttons and your printer tolerances.
- The interfacing tabs may be too tight or too loose depending on your printer tolerances. I would suggest a small test print to determine if you need to resize them, before committing to a full print.
- The enclosure should provide sufficient room for electronics but provides no dedicated mounting locations. If you want dedication mounting of your electrical hardware you will have to remix the step files accordingly.
- The left-handed pinky button location is modelled to accept a Sanwa OBSF-30, if you want to use a different button for this location (an OBSF-24) you will need to resize it. 

Key-Boxx Info:
TODO

Recommended Electronic:
TODO

Electronics Kits:
Depending on demand in the future I may sell barebones electronics kits so that all you need to do is print the enclosure and source your buttons. 
Kits would include a sufficient microcontroller and a matrix PCB for ease of wiring up buttons/keys. This is very unlikely, so for now, assume you also need to source your electronics.
