# Sbrodolina

Sbrodolina is a Bioprinter I designed as a consequence of finding myself in possesion of a 3D printer and too much free time.
I started this project with little knowledge about 3D printing, with the intention to educate myself, have fun taking up the challenge of designing a printer from scratch and eventually rejoice seeing it spill some liquids.
She is not the prettiest but I love her all the same.

![Printer](https://github.com/Leo-GG/Sbrodolina/blob/master/pics/full_view.jpg "Sbrodolina in its current status")

![Front view](https://github.com/Leo-GG/Sbrodolina/blob/master/pics/front_view.jpg "Sbrodolina in its current status")

## Current status (27/05/2019)

* All axis are assembled, tested all motors and endstops using Pronterface.
* First "extrusion" tests coming in two weeks! Haven't decided on which material to use yet.
* Few temporary solutions need to be reworked:
  * Endstops are currently held by cable ties. This hurts my eyes every time I see it
  * The syringe pump should be mounted somewhere on the printer
  * Same for the power supply and the Arduino, it is quite messy as it is now
  * The design of the syringe holder on the pump is plainly horrible. I intend to amend this

## Design

I designed the printer using aluminium profiles and lead screws on all axis. The idea was to get a robust design. And plenty of wheels and screws everywhere.
Since it is meant to extrude liquids rather than filament, it uses a pipette tip connected to a syringe pump. The syring pump was also 3D printed and has even more design flaws than the body of the printer.

## Control

The printer is controlled like any regular open source 3D printer: I used an Arduino board with a RAMPS shield to control all the motors and endstops. 
I used the MARLIN firmware on the Arduino side and for the time being I use Pronterface to control the printer manually.

