# CP/M info and usage #

from CP/M emulation towards software development on a Z80 single board computer

content:
* CP/M Box - PCW Emulator
* SC130 - Z180 Motherboard
* (z80 board - welches?)
* Links
* Software Packages 
* Examples
  * BASIC
  * C
    * Aztech C
    * MESCC
  * PASCAL
    * Turbo Pascal



## CP/M Box - PCW Emulator ##
https://www.habisoft.com/pcw/en.htm

Features
Emulation von Amstrad PCs
PCW 8256 / Joyce - 256 kB RAM, Diskette mit 170 kB je Seite)
PCW 8512 / Joyce Plus - 512 kB RAM, zwei Laufwerke (auch mit Diskette 720 kB)
Einbinden eines Windows-Verzeichnis als Festplatte (M:)

Ordner PCW

Boot Disk CP/M Plus v1.4

Disk (in HARDDISK kopieren):
Turbo Pascal
Hitech C
Aztec C



## SC130 - Z180 Motherboard ##
https://smallcomputercentral.com/sc130-z180-motherboard/

Features
* Z180 processor clocked at 18.432 MHz.
* 512k byte RAM.
* 512k byte Flash (ROM), typically containing RomWBW.
* 2 Serial ports
* SPI port, primarily for SD card mass storage
* 40-pin vertical backplane socket, RC2014.
* 40-pin horizontal backplane socket, RC2014.


Datenübertragung, auf RomWBW RAMdisk A:	Tools: 
https://www.retrobrewcomputers.org/forum/index.php?t=msg&th=242&goto=4013&#msg_4013







## (z80 board - welches?) ##



## Links ##

Small Computer Central - https://smallcomputercentral.com/



## Software Packages ##

### TE - text editor ###
https://github.com/MiguelVis/te

### MESCC - Mike's Enhanced Small C Compiler ###
https://github.com/MiguelVis/mescc



### Turbo Pascal ###

### HiTech C ###

### Mix C ###




## Examples ##

focus on "hello world" and i/o routines


### BASIC ###




### C ###
 
#### Aztec C ####

<pre>
/* 
 Aztec C / 1.06
 
 > cc hello.c
 > as hello.asm
 > ln hello.o c.lib

 */

int main()
{
    printf("hello, world\n");
    return 0;
}
</pre>


#### MESCC ####

<pre>
#include "mescc.h"
#include "conio.h"

main()
{
    puts("Hello world!");
}
</pre>



### PASCAL ###

#### Turbo Pascal ####





