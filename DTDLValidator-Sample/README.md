# Introduction 
This project demonstrates use of the Azure Digital Twins DTDL parser

# Getting Started
The program is a command line application that can be used in normal or interactive mode.

In normal mode, specify:
* a file extension (-e, default json)
* a directory to search (-d, default '.')
* a recursive option that determines if the file search descends into subdirectories (-r, default true)

Interactive mode is entered with the -i option. Type help for information on interactive commands

# What the Code Demonstrates
* Basic use of the DTDL parser for validation of DTDL
* Basic use of the object model to access information about DTDL content (see the interactive moduel, in particular the list and show/showinfo commands)

# Build and Test
Build the project and run the application from the command line.

You can also create a self-contained single-file .exe (no other files or installations required):

Run
```bash
dotnet publish -r win-x64 -c Release /p:PublishSingleFile=true
```
in the root folder of the repo.

# ToDo
* Update the location of the NuGet file to the official location
* Better error handling in the interactive part