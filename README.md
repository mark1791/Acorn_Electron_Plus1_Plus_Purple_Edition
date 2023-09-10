# Acorn Electron Plus1 Plus Purple Edition
Acorn Electron Plus 1 PCB and 3D CAD for the Plus1+ Purple edition which adds MMS Header and Atari Joystick Port

Design was evoled from my previous version to re-imagine the original Plus 1, to redraw the Acorn Schematic and the redrawn schematic by P.H Harvey. This can be found here [Acorn Plus One Reimagine](https://github.com/mark1791/Acorn_Plus_1_Reimagine)  This version has added a Digital Joystick port based off of the reversed engineered [Slogger Joystick card](https://github.com/mark1791/Acorn_Electron_Plus1_Plus_Purple_Edition/blob/main/Images/Slogger-PCB-Reverse-Engineer-Layout-mark1791-150823.pdf) I took pictures front and back then mergerd one over the top and re-drew it in KiCAD

The final schematic can be found here which includes the [Joystick port and MMS Header](https://github.com/mark1791/Acorn_Electron_Plus1_Plus_Purple_Edition/blob/main/Documents/001-Acorn-Electron-Plus1-V2-Joystick-schematic-mark1791-060923.pdf).

The PCB was printed in Purple Gold as why not, as looked nice, down side was i hadn't connected the right address lines up to the Joystick port, hence the bodge wire and also the picture i used as reference in the attached pdf the +5V and GND was wrong and wrong way round, latest KiCAD file attached has all these fixes in, so next batch of PCB's which will be my last for this project should be good.

The AP6 does fit onto the PCB, downside if you fit sockets for everything, the lid does not fit as insufficient clearance, should fit when chips soldered directly to PCB, also may need to reduce the ribs i added to help stiffen up the top when printed at the front as clearances are tight with the AP6, also there are no holes to bolt the AP6 directly to the PCB to support it. Put the headers for the joystick port directly underneath the holes for the AP6

One thing i would like to investigate if possible is a combined Plus 1 Rom with MMS Rom save having to use the ABR to loaded the MMS Rom data

## Final 6 Piece Plus 1+ Purple Edition in Flouresant Orange
![Screenshot](Images/IMG_0603.jpg)
Hatch Off
![Screenshot](Images/IMG_0604.jpg)
Left Upper End before bolting Up
![Screenshot](Images/IMG_0605.jpg)
Top Cover off showing right side with Cartridge Locators
![Screenshot](Images/IMG_0606.jpg)
Showing Left hand side with additional Joystick Interface and Header for a SD Card MMS connected to printer port.
![Screenshot](Images/IMG_0607.jpg)
CAD Design in FreeCAD, STL/STEP files provided as a 2 Piece Upper/Lower and a 6 Piece version that can be printed on a 3D printer, mine being a AnyCubic Vyper with bed size of 245 x 245 mm

## Two Piece Design Upper/Lower
![Screenshot](Images/CAD_Plus1_single_Upper.JPG)
![Screenshot](Images/CAD_Plus1_Single_Electron.JPG)
![Screenshot](Images/CAD_Plus1_Single_Lower.JPG)

## 6 Piece Design to fit Anycubic Vyper 245mm x 245mm

![Screenshot](Images/CAD_Plus1_Plus_Main_001.JPG)
![Screenshot](Images/CAD_Plus1_Plus_Main_002.JPG)
![Screenshot](Images/CAD_Plus1_Plus_Main_003.JPG)
![Screenshot](Images/CAD_Plus1_Plus_Main_004.JPG)

## 6 Piece Design final printed version

Exploded view of the 3 Main Pieces with SD Card SPI
![Screenshot](Images/Explo1.jpg)
Picture of Lower PCB in Lower Case
![Screenshot](Images/Explo2.jpg)
Top shot of underneath of Top cover showing M3 Bolts to attach the sides and M4 Brass Inerts melted into to bolt Top to Bottom
![Screenshot](Images/Explo3.jpg)
Picture of Lower PCB in Lower Case
![Screenshot](Images/Explo4.jpg)
Bog standard microSD Card SPI generic off of Ebay
![Screenshot](Images/Explo5.jpg)
Top shot with no cover
![Screenshot](Images/Explo6.jpg)
Top Shot
![Screenshot](Images/Explo7.jpg)
Underneath shot
![Screenshot](Images/Explo8.jpg)
With AP6 fitted
![Screenshot](Images/Explo9.jpg)
Showing AP6 fitted with additional sockets to fit as putting sockets on board doesn't allow direct fitting as too tight
![Screenshot](Images/Explo10.jpg)

## Picture of the Slogger Joystic Interface card used to reverse engineer the Joystick layout

![Screenshot](Images/Joystick1.jpg)
![Screenshot](Images/Joystick2.jpg)
