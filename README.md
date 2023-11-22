# Famicom expansion port controllers support
This repo contains patches to add Famicom Expansion port controllers compatibility.

https://github.com/darthcloud/famicom-exp-patches

These patches are for headered iNES ROM.

Support for internal controllers is maintained in most case.

## Games that loose internal controllers support
* Battletoads
* Snake Rattle n Roll
* Terminator 2

The original poll function is quite optimized already and the bank in which the poll function is located do not have obvious empty space to allow relocation/split of the poll function.

## Alternation version w/ FC exp support
Some version of those games do support controller on the Famicom expansion port:

* Link no Bouken - The Legend of Zelda 2 (Japan) (FDS)
* Paperboy (Japan) (FC)
* Pinball (Japan) (FDS)
* Pinball (Europe) (NES)
* RoboCop 2 (Japan) (FC)
* Star Force (Japan) (FC)
* Terminator 2 (Japan) (FC)
* Yume Koujou - Doki Doki Panic (Japan) (FDS)

