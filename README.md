# ASM-Piano-Simulation


## About
- A Piano Simulation using assembly level language programming language.
- Each note of the piano is associated with a fixed frequency and upon taking input from the user, the note is played for a specific amount of time(1- 2 seconds). 
- Each image that is visible is independently created using Paint and saved as Bitmap file.

## Tools used
The Tools used for this project are:
- TASM - Turbo Assembler
- DosBox
- Notepad ++ Editor
- Paint

## How to Run
1. Install DOSBox
2. Install TASM and make a directory named TASM in C drive
3. Save the piano.asm in that folder
4. Save the images in the media folder in the same directory as the 'piano.asm' file
5. Run the following commands
````
TASM piano.asm
TLINK piano
piano.exe
````

## Outputs
<kbd>![Alt text](/media/keyboard.bmp "Piano")</kbd>

<kbd>![Alt text](/media/keyR.bmp "PianoKey")</kbd>
