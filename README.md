# C-To-Delphi

## Description
This tool will convert most of your standard C code. .

It contains a split view, with C on the left and Delphi on the right.
The Delphi code gets updated in realtime when you edit the C code.
The editors are kept in sync, so you can easily find how a specific piece of code was converted.

* **Syntax checks** on the generated code can be done using DelphiAST
* You can even **run** the code using DWS by pressing F9

* You can drag/drop multiple C files to the application. It'll find the .h files that belong to it, and convert all to .pas files in the same folder.

## Features:
* If function main exists, a program will be generated. Otherwise a pascal unit with interface/implementation sections.
* Converts routines and arguments
* Converts for loops
* Converts case statements
* Converts structs
* Converts enums
* Converts 1 and 2 dimensional arrays
* Converts many other common routines to Delphi equivalents (strcpy,strcat,strlen,printf,argv,argc,etc)
* Converts classes
