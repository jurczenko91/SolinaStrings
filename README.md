# SolinaStrings
A string machine synth on Arduino

<img src="https://github.com/jurczenko91/SolinaStrings/blob/main/ASM-1%20snapshot.png" width=700>
<br>

This is my version of the Arduino string machine. Original code was written by Jan Ostman, then modified by Dave Field.<br>
I made a few changes:
 *  removed MIDI channel selector and set channel to 4
 *  fixed a problem with pitch becomes a semitone higher at maximum modulation value
 *  Moved midi read to the loop section to prevent notes sticking
 *  Made VCA envelope output via MCP4725 DAC (for using external filters/VCA/whatever)
 *  Moved envelope, phaser and mod pots to pins A0-A2
<br>
Schematics and description are coming soon...
