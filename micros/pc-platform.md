## IBM Predecessors 
### September 1975
IBM 5100
- BASIC and/or APL programming , 16-64KB, tape storage, $8,975-$19,975 for engineers, statisticians, etc. 
- Processor: PALM
### January 1978
IBM 5110
- More general programs, tape and/or diskette, printer option 
- Processor: PALM
### February 1980 
IBM 5120
- two built-in 8-inch disk drives & 9" monitor  $9,340-$23,990 (Inventory/payroll/etc)
- Processor: PALM
### June 1980
IBM Displaywriter 
- Desktop text processing system $7,895
- Processor: Intel 8086
### July 1981 
IBM System/23 Datamaster 
- word processing and data processing combined unit $9,830 with printer word processing option $1,100-$2,200 more
- Processor: Intel 8085
- Included BASIC

## Other early influences
### 1980 
Shugart (later Seagate) introduces the ST-506 5MB HDD
- Disk controller evolved from SA1000, which was evolved from the floppy disk controller
- MFM encoding
- Later models:
    - 1981 ST-412 10MB
    - 1981 ST-225 20MB, half-height
- A later extension to the ST-412 used RLL encoding for a 50% increase in capacity and bit rate
- The ST-506 interface is copied by other manufacturers
- ESDI was an extension to ST-506 that moved some parts from the controller onto the drive iteself.  It used ST-506 cabling


## The PC
### August 12, 1981
IBM Introduces the IBM PC (5150) for $2,995
- Processor: Intel 8088 @ 4.77MHz
    - **This choice gives us the x86 platform**
- Internally 16-bit, including registers
- 8 bit data bus
- 20-bit address bus (1 MB addressable memory)
- ROM: 40KB includes:
    - 8KB BIOS = **IBM's "secret sauce" the only proprietary part of the otherwise open system**
    - 32KB **"IBM BASIC" licensed from Microsoft** (GW-BASIC)
- RAM: 16KB- 64KB (4x16KB banks[9 chips/bank including parity bit]) on motherboard, memory expansion cards were available
- No NVRAM, system configuration via DIP switches on motherboard
- Memory map establishes the 640KB limit to RAM - not seen as an issue at this point.  Above 640KB is ROM, video memory, etc.
- Support chips:
    - Intel 8284 clock generator
	  - Intel 8288 bus controller
	  - Intel 8254 Programmable Interval Time
	  - Intel 8255 Parallel I/O interface
	  - Intel 8259 Programmable Interrupt Controller (IRQ)
	  - Intel 8237 DMA Controller 
	  - Optional Intel 8087 Math co-processor
- Sound: Internal speaker
- Storage: 5.25" 160KB floppy disk, Single sided, double density.
    - **Set's 5.25" DD as the PC standard**
    - MFM encoding
    - 40 tracks
    - 512-byte sectors, 8 sectors/track (soft sectored)
    - Full-height drives made by Tandon
- I/O
    - 5 8-bit expansion slots 
        - **Becomes known as PC/XT bus or 8-bit ISA**
    - 5 pin DIN Cassette port 
        - Only worked with BASIC
    - 5 pin DIN Keyboard port
        - **Early standard for PC keyboards**
- Display options
    1. MDA (Monochrome Display adapter) & 5151 green screen monitor
        - Built around **Motorola MC6845** display controller chip
	      - Text mode only (80x25)
	      - 9x14 pixel character font
	      - supported underline, bold, inverse, and blinking characters
	      - Included parallel printer port (DB-25 Centronics)
            - **Becomes IEEE 1284**
    2. CGA (Color/Graphics adapter) & 5153 RGBi monitor
        - Built around same Motorola MC6845 display controller chip as MDA
	- 8x8 pixel character font
        - 16KB video memory
- IBM "Model F" keyboard, 83-key, left-hand side F1-F10, buckling spring "clicky keys"
- Extended ASCII character set - "Code page 437"
    - What most people think of "ASCII"  today
- Installing a hard disk ("Winchester drive") involved a power supply upgrade - not an official IBM offering
- Operating System: **Microsoft MS-DOS 1.0**
    - Essentially a "work-alike" of CP/M 8-bit operating system for 8080/Z80 processors
    - Big innovation from Microsoft is the FAT filesystem  (now called FAT12)

### May 1982
Microsoft releases PC-DOS 1.10 which includes support for
- Double sided disks, offering support for 320KB DSDD floppies
- Bug fixes and better error message
- DEBUG support for >64KB files
IBM Releases Rev B PC with the double sided diskette drives

### January 1983
Compaq releases the Compaq Portable
	• First true IBM PC compatible
	• Includes Compaq custom BIOS, produced in "Clean Room" method
	• OS is "Compaq DOS 1.13"  (essentially PC-DOS 1.1 licensed from Microsoft)  Later would license MS-DOS 2.x
Before this there were PC "Clones" that had incompatible proprietary BIOS and licensed, customized versions of MS-DOS.  Software written to work directly with the IBM hardware did not run on these machines - only software that relied totally on the PC/MS-DOS "API".
	
### March 8, 1983
IBM introduces the IBM PC/XT (5160).  Improvements over PC:
	• 128KB memory standard (up to 256KB on motherboard, 64KB soldered in)
	• 1 360KB DSDD 5.25" floppy
	• 10 MB Seagate ST-412 MFM hard drive
	• Serial card with 8250 UART (large DB-25 connector)
	• 130 watt power supply
	• 8 expansion slots
Microsoft releases PC-DOS 2.0.  A major re-write of DOS 1
	• Support for hard disks - MBR
	• Support for subdirectories
	• New 9-sector format, increasing disk format to 360KB
	• Unix-like "file handles" replace CP/M-like File Control Blocks (FCB)
	• Loadable device drivers to extend hardware support
	
### July 1983
Wang Laboratories announces the 30 pin SIMM memory module

### November 1, 1983
IBM introduces the IBM PCjr (4860).  
The PCjr was IBM's unsuccessful effort to enter the "Home Computer" market.  Innovations included:
	•  "PCjr graphics"  - two chips, the 6845 and the VGA (Video Gate Array) - not the later VGA  - 16 color extension of CGA technology 
	• Included RF modulator (separate option for CGA)
	• 3-voice sound (TI SN76489 Chip)
	• Only PC model with ROM Cartridge slots
	• "Sidecar" version of I/O Channel bus
	• "Light Pen" port - effectively becomes a mouse port later
	• Included joystick ports
	• First half-height 360KB floppies
Microsoft releases PC-DOS 2.10 with support for half-height floppies (required timing changes)
	
	
### May 1984
Phoenix Software Associates released the first Phoenix PC ROM-BIOS, licensing it to OEMS to create 100% compatible clones.  AMI and Award BIOS quickly follow.  System BIOS becomes a open commodity item.

### August 14, 1984
IBM introduces the IBM PC/AT (5170)
	• 6Mhz Intel 80286 microprocessor
		○ 16-bit data bus
		○ 24-bit address bus (16MB addressable memory)
		○ Optional 80287 math co-processor
	• "I/O Channel" bus - 16-bit AT Bus, backward compatible with 8-bit XT bus,  later to be known as ISA
	• Addition of 2nd 8259A increasing total IRQs to 15 (from 8)
	• Addition of 2nd 8237A increasing DMA channels to 7 (from 4)
	• 8250 UART upgraded to 16450 (for high speed serial connections, but still problematic)
	• Battery backed real-time clock added - Motorola MC146818, includes 50 bytes of CMOS memory to store BIOS parameters (NVRAM)
	• BIOS Setup program provided on disk
	• 84-key AT Keyboard (also considered Model F), left side F1-F10, adds Sys Req key, LEDs for Caps/Scroll/NumLk, and large "L" Enter key
	• Introduction of 1.2MB 5.25" Floppy (Double sided, high density, 80 tracks, 15 sectors/track (512 bytes)) - some incompatibilities with 360KB floppy drives
	• Seagate ST-412 MFM 20 MB drive **Sets the ST-506 MFM interface as standard**
	• Xebec 1210 MFM controller
20MB hard disk drive 
	• Worked with existing CGA & MDA cards
	• Case supports a physical lock
	• 192W power supply
This defines the standards:
	• ISA bus
	• AT form factor
Microsoft releases PC-DOS 3.0
	• Adds support for 1.2MB floppies
	• FAT16 filesystem
	• Extended Memory Specification (XMS) - specifies use of memory beyond 1MB on 276 class machines.  Not well defined nor used.
	
### October 1984
IBM announces the Enhanced Graphics Adapter (EGA) for use in the PC line

### November 1984
Tandy announces the Tandy 1000 line
	• PC compatible
	• Uses PCjr graphics and sound.  Become known as "Tandy graphics/sound"  or TGA
	• MS-DOS in ROM

### March 1985
Microsoft releases PC-DOS 3.1
	• Bug fixes to 3.0
	• Support for the IBM PC Network
	
### Also in 1985
Expanded Memory Specification (EMS) makes its debut at COMDEX.  It uses bank-switching to circumvent the 640KB barrier.  Lotus, Intel, Microsoft later refine standard and commit support in future products
Microsoft releases Windows 1.0.  Nobody cares.
	
### April 3, 1986
IBM releases the IBM PC Convertible (5140)
	• First IBM "laptop"
	• First IBM PC with 3.5" 720KB floppy drives
	• Intel 8088 @ 4.77MHz
	• Expandable to 640KB
	• Monochrome CGA-compatible LCD screen
Microsoft releases PC-DOS 3.2
	• Support for 3.5" 720KB floppies
	• Support form IBM Token Ring network

### Also in 1986
 - Western Digital develops "IDE" standard (Integrated Drive Electronics)
 - Drive controller is integrated into the drive (MFM drives had complex controller cards in ISA bus).  Hard drive controllers are now essentially bridges from the host bus to ATA
    - "PC/AT Atttachment"  (ATA) essentially extends the 16-bit ISA bus to the drive.  Defines connectors & signaling
    -  Host asks for a sector, IDE electronics take care of the physical requirements to retrieve it
 - Chips & Technologies releases the NEAT Chipset 82C206, incorporating all of the support chips from the AT motherboard into a 4-chip "chipset".  Chipsets become economical and popular with clone manufacturers
 - Compaq releases Compaq Deskpro 386 - first Intel 80386 based PC.
 - AST releases the Rampage/286 memory expansion board with its EEMS standard - a predecessor to LIM EMS 4.0 - allowing paging of conventional memory in addition to the standard EMS page frame.

### April 1987
IBM releases the Personal System/2 (PS/2) line of computers
	• Serial port upgraded to 16550 UART - fixing high speed woes
	• 1.44MB high density 3.5" floppies
	• 72-pin SIMMs for memory expansion rather than DRAMs in motherboard sockets
	• PS/2 keyboard port (6-pin mini-DIN) replaces larger PC 5-pin DIN
	• PS/2 mouse port (6-pin mini-DIN) replaces DE-9/DB-25  RS-232 "serial mouse"
	• VGA graphics & connector (still incorporates old Motorolla 6845 circuitry)
	• Micro Channel Architecture (MCA) - replaced ISA and featured:
		○ Bus mastering
		○ Bus arbitration
		○ Plug and play BIOS management
	• 101-key keyboard - IBM Model M
	• Some models use ATA/IDE hard drives.  (Other used ESDI which would fade away)
Standards set:
All of the above except the proprietary MCA, which IBM offered to license.  Few bought it, and stuck with ISA.
This represents the last time IBM influences the PC Standard in a significant way

PC-DOS 3.3 is released to support `1.44MB floppies and bug fixes.  Written by IBM, not Microsoft.  Very stable DOS and becomes a very standard DOS version

Also in 1987
Chips & Technologies  release a VGA-compatible chipset - 82C451
Microsoft ships Windows/386.  Compaq agrees to bundle it with the 386 machines
Compaq ships MS-DOS 3.31 which has support for hard disk partitions >32MB
L-I-M EMS 4.0 announced
Ad Lib card is shipped

		
1988
IBM ships IBM DOS 4.0
	• DOSSHELL
	• XMS 2.0, including new HIMEM.SYS memory manager supporting loading memory into 
		○ UMB - Upper memory blocks - unused memory in system area between 640KB and 1MB
		○ HMA - High Memory Area - A20 handler adds first 64KB of extended memory (beyond 1MB)
		○ XMS - Extended memory - memory beyond 1MB
		
1989
Sound Blaster card is shipped

1990 
DOS Protected  Mode Interface (DPMI) released

1992
VESA Local Bus created to bypass speed limitations of ISA
	
	
	
Good links:
https://en.wikipedia.org/wiki/Timeline_of_DOS_operating_systems

Backstory of the IBM PC
Byte magazine Volume 15, Number 9
	
