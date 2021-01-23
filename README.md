# Electronic-Chess-Board

This electronic chess board interacts with the Lichess API to play against online opponents.

## File descriptions

overview.pdf
* pictures of the project
* explanation of the chess board user interface
* control flow diagram
<br>  

circuit_schematic.pdf
* circuit schematic of the LED and button matrices
* made in KiCad
<br>  

chess_program.py
* runs on a PC
* controls communication between Lichess's servers and the MSP-EXP430FR6989 launchpad
<br>

main.c
* runs on the MSP-EXP430FR6989 launchpad
* communicates with chess_program.py via UART
  * sends button input to chess_program.py
  * turns on LEDs as requested by chess_program.py