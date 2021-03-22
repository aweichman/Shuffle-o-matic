# Shuffle-o-matic

Full overview video:
https://www.youtube.com/watch?v=eMTXyl7tPEk

Thingiverse page (cad files):
https://www.thingiverse.com/thing:4547302

## Significant experience recommended if you want to take on this project, it isn't documented very well :)
I am working hard to rebuild and redocument the whole project.  Please stay tuned!

Hardware required
- 3D printer
- 3x Nema 17 stepper motors, <=40mm long
- 1.5m gt2 belt
- 5x gt2 20t idlers with standoffs
- 3x gt2 20t drive pulleys
- mgn9 servo
- 600rpm micro gearbox motor
- 2x MGN9 linear profile bearings, 135mm len
- 1x MGN9 linear profile bearing, 95mm len
- 6x 6700 bearing
- Raspberry Pi
- (optional) Raspberry Pi Camera V1.4
- (optional) 3x 3mm white led
- Adafruit Feather (more info below)
- Breadboard/pcb for laying out components
- Assorted M2 and M3 nuts and bolts

All part numbers in the pcb should be accurate, though again review and order at your own risk. Use KiCad to view/edit, it's free!

And probably a few other things I'm forgetting. Seriously if you want to make this, do so at your own risk. Review the cad model yourself and make sure you have everything accounted for! This is not a project for beginners!


Adafruit Feather Supported Boards:

The arduino project for the Adafruit requires a target with at least 5 analog inputs (A5 is used for the DC Motor Power pin).  The following lists the boards that I have found to be compatible with this requirement:
1. STM32F405 Express ($24.95)


The following is a list of parts that I have found to NOT work:
1. OLD HUZZAH without LiPo header
