# README

Sbrodolina is a Bioprinter I designed as a consequence of finding myself in possesion of a 3D printer and too much free time.
She is not the prettiest but I love her all the same.

![Printer](https://github.com/Leo-GG/Sbrodolina/blob/master/pics/full_view.jpg "Sbrodolina in its current status")
## Design

I designed the printer using aluminium profiles and lead screws on all axis. The idea was to get a robust design. And plenty of wheels and screws everywhere.
Since it is meant to extrude liquids rather than filament, it uses a pipette tip connected to a syringe pump. The syring pump was also 3D printed and has even more design flaws than the body of the printer.

## Control

The printer is controlled like any regular open source 3D printer: I used an Arduino board with a RAMPS shield to control all the motors and endstops. 
I used the MARLIN firmware on the Arduino side and for the time being I use Pronterface to control the printer manually.

