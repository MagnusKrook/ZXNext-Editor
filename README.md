# ZXNext-Editor
A text editor for the ZX Spectrum Next, built in NextBASIC.

## Description
This is a simple text editor for editing configuration files other short files.
Despite being built in BASIC it is quite fast, running in 28 kHz mode and utilizing some of the unique commands and functions available in NextBASIC.

## Limitations
The editor has the following limits on the size of the files it can open and save:
* Max file size: 16 kB.
* Max paragraph size: 256 characters.
* Max number of paragraphs: 100.

## Installation
The program consists of two parts; Editor.bas which is the main program and EditorProc.bas which consists of a number of procdures called from the main program, and which is put into a separate memory bank when the main program is executed.

## Development tools
The program has been authored in Visual Studio Code with Remy Sharp's NextBASIC plugin and the ZX Spectrum Next emulator #CSpect by Mike Dailly.
