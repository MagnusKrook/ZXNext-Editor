# ZXNext-Editor
A text editor for the [ZX Spectrum Next](https:specnext.com), built in NextBASIC.

## Description
This is a simple text editor for editing configuration files and other short text files.
Despite being built in BASIC it is quite fast, thanks to the Next 28 kHz mode and some of the unique commands and functions available in NextBASIC.

## Limitations
The editor has the following limitations on the size of the files it can open and save:
* Max file size: 16 kB.
* Max paragraph size: 256 characters.
* Max number of paragraphs: 100.

## Running the program
The program consists of two parts: The main program **Editor.bas** together with **EditorProc.bas** which is stored in a separate memory bank. Copy both these files to the SD card and type **LOAD "Editor.bas"** to start the editor.

The editor commands are accessed by entering extended mode and pressing the relevant key as presented in command menu at the bottom of the screen.

If a mouse is connected, it can be used to move the cursor and to trigger commands.

## Source code
The source code (**Editor.bas.txt** and **EditorProc.bas.text**) has been authored in Visual Studio Code with Remy Sharp's [NextBASIC plugin](https://marketplace.visualstudio.com/items?itemName=remysharp.nextbasic) and the ZX Spectrum Next emulator [CSpect](http://www.cspect.org/) by Mike Dailly.
