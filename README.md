# BabyArcade
## Intro
My 1yo son discovered his index finger and loves to press all kind of Buttons and explore what happens.
So i decided to build a toy for him the basic idea was to have some buttons in a box and add some lights and sound for feedback.
I decided to go for standard 30mm Arcadebuttons with included lights. For sound i'm planing on using a DFPlayer module - i used it in a test and i like the simplicity.
To extend the posibilitys of the toy i'm planing to add an nfc reader (RC522) so i can implement similar funktionality to a Toniebox.

Counting the IO pins:
5 Buttons
5 LEDs
2 UART for DFPlayer
5 SPI for RC522

since i dont need any wifi or ble, my idea was to use an Raspberry Pico with Circuit Python, but that may not be final sice my requirements dont realy need anything special.

## Open Questions
I'm not sure how i want to realise the power system. My Ideas reange form an external powerbant to a completly closed system including a battery charged via QI.

I have a love&hate relationship with Circuit Python. I quite like the fast developement without compiling and most of the librarys are well writen. On the other hand you dont have full controll over your Controller and most Circuit Python implementations are not feature complete. The first PoC was done using Circuitpython, but i allready know there is no lib for the RC522, i hope i can manage to port a micro python lib succesfully. 

## State of the Project
I started to build the case, lasered from 4mm Plywood. sanded and polished. 


