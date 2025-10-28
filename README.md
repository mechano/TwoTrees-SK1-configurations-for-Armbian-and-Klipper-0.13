Config directory for TwoTrees SK1 3D printer.
Linux and Klipper knowledge is required.

I use Armbian Linux based on Ubuntu Noble, and Klipper 0.13.x

The Armbian for TwoTrees is the same for Makerbase SKIPR Mini from Maxim Medvedev. Refer to it for installation infos.

https://github.com/redrathnure/armbian-mkspi

After install and configure Armbian, use Kiauh to install Klipper and some components like Shell command executions.

https://github.com/dw-0/kiauh

To apply my config search files for user path, and change per the user you have created. I use as default /home/mks
To use the graph creation scripts you'll need numpy and matplotlib python's libraries, refer to error messages you'll receive when generation fails.

The display is not supported. So I used the CYD-Klipper display project for Klipper.

https://github.com/suchmememanyskill/CYD-Klipper

You have to compile and flash both MCU and THR updated firmware refer to this video for info on how-to because it needs to solder an header to the THR's USB port.

https://www.youtube.com/watch?v=FsllmCiCr3Y

Enjoy my macros and interesting mods, like the START_PRINT that avoids TPU jamming, belt tension and input shaping graphs, and so on.
There're also some optimization to extruder voltage to avoid heating of the extruder's motor.

Correct the Z size to 256, I've 250mm due to the use of Oldham couplers.
