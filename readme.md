## Description
The aim of this repo. is to simplify vJoy development. It also addresses version issues that sourceforge has.
How did I obtain the latest version then? It's present in the vJoy installation folder 'vJoy\x64' (comes with the demo feeder)

## Prerequisites
1. visual studio community(any version) with *.NET desktop development*
2. basic knowledge of how to write code in C#
<br>
**note: how does all of this work exactly? you write code in .NET to interact with the vJoy drivers (feed data etc.) and then you can spawn this feeder as a child process in other languages to extend functionality. Example: you can use input from arduino as the vJoy joystick input.**

## SDK 'installation'
copy **vjoyInterface.dll** to **C:\Windows\System32** this will ensure that your .NET application is able to interact with the vJoy driver
## how to setup dev. environment?
 