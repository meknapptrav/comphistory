# What they were
When IBM introduced the [IBM PC](pc-platform.md#the-pc) in 1981, many people knew that it would succeed on the IBM name alone.  As much of the machine was built
using off-the-shelf parts, it was fairly easy to create a "Workalike" machine that was very similar and could run MS-DOS.  These vendors
would frequently try to differentiate themselves by offering features that were better than what IBM offered.

Differences in the hardware meant, however, that these machines were not 100% IBM compatible and required Microsoft to create special
versions of MS-DOS that would run only on that piece of hardware.  Microsoft suggested that application software use the MS-DOS API exclusively for interacting with the hardware.  An example application that did this was the word processor WordStar, which is ported to MS-DOS from CP/M.  This meant that WordStar could run on any MS-DOS machine without modification.  There was a performance penalty for this, however.  The application would make a DOS call, which would likely then make a BIOS call, which was slow and inefficient.

Therefore, application software would frequently bypass both standard MS-DOS calls and the BIOS, and would write directly to the hardware.  This meant that this software would need to be patched to run on the different hardware.  (e.g. A modified Lotus 1-2-3 was available for the Tandy 2000).  While this was considered normal practice in the industry at the time, consumers wanted to be able to buy the retail version of software and run it on their machine - not have to purchase a special, expensive version from the hardware vendor.

This meant these machines ultimately failed, and the importance of "100% IBM Compatible" was recognized.


# Notable models

## Tandy 2000
A much higher end machine than the PC: faster, more memory, higher capacity storage.  Tandy touted Lotus's claim that this was the best machine to run 123 on.   
[Wikipedia article](https://en.wikipedia.org/wiki/Tandy_2000)   
[Infoworld review](https://books.google.com/books?id=wi4EAAAAMBAJ&lpg=PA74&pg=PA71#v=onepage&q&f=false)

## HP 150
This is a very neat all-in-one type design with 3.5" disks and a nice high-resolution 9" display with touchscreen technology!  It interfaced peripherals via the HP-IB (IEEE-488) bus.    
[Byte magazine review](https://archive.org/stream/byte-magazine-1984-11/1984_11_BYTE_09-12_New_Chips#page/n259/mode/2up)    
[Wikipedia artcile](https://en.wikipedia.org/wiki/HP-150)    

## DEC Rainbow
This is an interesting 3-in-one computer.  (One could even say 4-in-one)
 - It could act as a VT101 terminal to connect directly to DEC's VAX minicomputers
 - It could run the "CPM 86/80" OS which could detect and run both CP/M and CP/M-86 software, using the correct processor for the executable (Z80 and 8088, respectively)
 - It could run MS-DOS on it's 8088 processor  
 
Basic stats:
 - Intel 8088 @ 4.815 MHz
 - Zilog Z80 @ 4.012 MHz
 - OS: C/PM-80, C/PM-86, MS-DOS, USCD p-System
 - Storage: proprietary RX50 SS Quad-density 5.25" floppies (400K) & hard drive option (ST-506 standard)
 - Graphics: text in 80×24 or 132×24 modes.  Proprietary graphics add-on based on NEC 7220   
 
[Wikipedia article](https://en.wikipedia.org/wiki/Rainbow_100)

