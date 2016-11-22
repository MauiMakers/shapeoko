# Shapeoko

I think we have a [Shapeoko 1](http://www.shapeoko.com/shapeoko1.html).  The board is a [grblshield v5](https://www.synthetos.com/project/grblshield/) from [synthetos.com](https://www.synthetos.com/).

## Setup

1. You'll need an Arduino USB driver to communicate with the board.  It depends on your operating system, so the easiest way to get the correct driver is to [install the Arduino software](https://www.arduino.cc/en/Main/Software).
1. Download [Zapmaker](https://github.com/zapmaker/GrblHoming/releases) for your operating system.  Note the OSX version is the one ending in `7z`.
  1. Assuming you're on OSX, you'll need p7zip to decompress the OSX release: `brew install p7zip`
  1. and then unarchive it: `7z x ~/Downloads/GrblController-3.6.1.7z`
  1. and then open the `.dmg` and drag the GrblController to /Applications as usual.
1. Power on the CNC machine
1. Wait a minute for it to boot
1. Plug in the USB cable
1. Open GrblController
1. Choose /dev/cu.usbmodemXXXX from the dropdown; 9600 baud
1. Click Open

## G-Code 

The files it uses are called "G-Code" and typically end with an `.nc` extension.  [G-Code-Examples](https://github.com/grbl/grbl/wiki/G-Code-Examples)

