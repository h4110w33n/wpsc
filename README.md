wpsc
====

Web Power Switch CLI

This project was to create a CLI for the Web Power Switch by Data Loggers.

http://www.digital-loggers.com/

The wpsc script can provide an interface for controlling the Web Power Switch and a *nix based system that has libcurl. 
This can let an administrator set schedules for cycling or toggling outlets, and with the addition of a simple watchdog 
script, it can even be used to do basic automation above and beyond the built in "Autoping" that is part of the device.

It is also noted that newer version of the Web Power Switch do have a round-a-bout way of scripting using the web ui. 
This is a huge step forward, but it does lack traditional terminal interface and a scripting system as powerful as 
bash (or similar). 

The Web Power Switch used in development ran software version Version 1.2.C (circa 2009), and your results may very if
a newer version of the software is running. Furthermore, the software was developed on Mac OS X 10.9 and tested on 
Ubuntu Server 12.04 LTS and Raspbian. 

Features Include:
Display all outlet status with JSON output
Display all outlet status with human "friendly" output
Toggle outlet
Turn On outlet (reagardless of previous state)
Turn Off outlet (reagardless of previous state)
Cycle outlet (duration set in Web UI)

The required flags and arguments are "-a" address, "-u" username, "-p" password.

Example Usage can be found by the using the "-h" flag. 
