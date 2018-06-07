# IBM PC XT/370, PC AT/370, and the Micro/370 

## Summary
The success of the IBM System/360 and System/370 meant that there was a considerable library of existing business software that was
designed to run on that platform.  There was considerable interest in the ability to run that software on a microcomputer platform.
There were two seperate projects within IBM to reach this goal.  One resulted in the PC XT/370 and AT/370 and the other was to become the 
Micro/370 microprocessor.

## IBM PC XT/370
The XT/370 was introduced in October 1983.  It was designed by engineers in IBM's Endicott location.  It was built on a standard PC/XT
and used a comination of specialized hardware and new system software developed by IBM.  It could operate as a standard XT and run 
PC-DOS locally.  It could also act as an 3270 terminal (similiarto the 3270 PC).  And finally, and most distinctively, it could execute
System/370 code locally.

### Hardware
Three standard 8 bit ISA cards made up the hardware for running System/370 code.   
 - A processor card 370PC-P
    - The processor card housed three customized chips.  The new Motorola 68000 microprocessor was a micro-coded processor.  This means
  that the instruction set it exposes to the system is different than how it works internally.  The "micro-code" is the programming 
  that translates the external facing Instuction Set to the internal workings of the chip.  IBM wrote custom microcode that replaced the
  standard 68000 instruction set with most of the System/370 instruction set.  There were some instructions that they couldn't fit into a 
  single 68000, so a second 68000 was used and was programmed to emulate in software the remaining instructions.  Finally, the floating
  point instructions were executed by a similar microcoded Intel 8087.
 - A memory card 370PC-M
    - This card contained 512KiB of memory and had a special connection to the processor card.  It was dual-ported, and 384KB was exposed
    to the XT mainboard (bringing the total to 640KB).  Data could be moved from the XT memory to the XT/370 memory by moving it from the
    lower 256KB on the mainboard into the upper 384KB on the 370PC-M card.  The second 128KB bank of the 384KB was bank-switched and could
    allow the XT 8088 to address the full 512KB on the card.
 - A 3270 terminal emulator card PC3277-EM
    - perhaps the same card in the PC 3270?  Not sure.
    
### Software
The XT booted into PC-DOS and initally could run as a standard PC/XT.  Then, the user could run IBM's VM/PC Control Program, which was
a PC version of IBMs VM operating system.  This allowed the user to move data from the XT memory into the 370PC-M memory, use the 3270 emulator to connect to an actual System/370 host and download data and code into the 370PC-M memory, and then locally execute S/370 code.
VM/PC provided a 4MB virtual memory space using the XT hard drive for the disk page files.  It also created virtual disks which were
maintained locally as PC-DOS files.  The System/370 CMS IMPORT and EXPORT commands performed ASCII/EBCDIC conversion of data in these files.

## IBM PC AT/370
In 1984, IBM introduced the AT/370.  This used similar cards as the XT/370, but upgraded to take advantage of the 16-bit ISA bus, larger hard disks, and DMA transfers from the 3277 card to the AT/370 processor card.  The new cards were the PC/370-P2, PC/370-M2, and a 3278/79 Emulation Adapter that was also used in the later XT/370 models.  The hardware was almost 60% faster than the XT/370.  VM/PC was updated to Version 2 and allowed add-on memory to be used for paging, in addition to the hard disk.  IBM claimed performance improvements of up to 50%.

## Links/Sources
[The CPUSHACK Museum](http://www.cpushack.com/2013/03/22/cpu-of-the-day-ibm-micro-370/)   
[Wikipedia article](https://en.wikipedia.org/wiki/PC-based_IBM-compatible_mainframes)
