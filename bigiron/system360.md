# IBM System/360

## What it is
A "family" of computers introduced by IBM in 1964.  Prior to the System/360, IBM made different computers for different market segments
and they were frequently incompatible with one another.

The System/360 line contained different models that could meet the needs and budget of the entire breadth of IBM's customer base.  A
key advantage to the System/360 line was the software developed was "upwardly compatible" with bigger models in the line.  In other
words, if you upgraded to a bigger model, you could bring all your software with you generally unmodified.

The S/360 was immensly popular and dominated the mainframe market.  IBM mainframes to this day are an evolution of the original S/360 and 
could still run software developed for the first models in the late 60s.

## Emulating the S/360
[Hercules, an emulator for IBM mainframes and other computers](http://www.hercules-390.org/)   
[z390 Portable Mainframe Assembler and Emulator Project](http://www.z390.org/)

## Model information
| Model | Shipped | Memory (KB) | LCS | Microcode format | ALU (bit) | Data bus (bit) | Registers                           | Designed by | Manufactured At         | Notes                                                                                                     |
|-------|---------|-------------|-----|------------------|-----------|----------------|-------------------------------------|-------------|-------------------------|-----------------------------------------------------------------------------------------------------------|
| 30    | 1965    | 8-64        | No  | CCROS            | 8         | 8              | main memory                         | Endicott    | Endicott & overseas     |                                                                                                           |
| 40    | 1965    | 16-256      | No  | TROS             | 8         | 16             | "fast core" 2X speed of main memory | Hursley     | Poughkeepsie & overseas |                                                                                                           |
| 50    | 1965    | 64-512      | Yes | BCROS            | 32        | 32             | "fast core" 4X speed of main memory |             |                         |                                                                                                           |
| 65    | 1965    | 128-1024    | Yes | 100-bit          | 60 + 8    | 64             | flip-flops 4X speed of main memory  |             |                         | Dual-CPU option                                                                                           |
| 67    | 1966    | 128-1024    | Yes | 100-bit          | 60 + 8    | 64             | flip-flops 4X speed of main memory  |             |                         | Supports DAT                                                                                              |
| 75    | 1966    | 256-1024    | Yes | hardwired        | 60 + 8    | 64             | flip-flops 4X speed of main memory  |             |                         |                                                                                                           |
| 22    | 1971    | 24-32       | No  | 50-bit           | 8         | 8              | main memory                         |             |                         | Re-manufactured 30                                                                                        |
| 20    | 1966    | 4-32        | ?   |                  |           |                | 16-bit                              | Germany     |                         | partially incompatible instruction set                                                                    |
| 91    | 1967    | 1024-4096   |     | hardwired        |           |                |                                     |             |                         | superpipelining                                                                                           |
| 95    | 1968    |             |     | hardwired        |           |                |                                     |             |                         | 91 with "thin-film" memory, twice as fast - NASA only customer                                            |
| 195   | 1971    |             |     | hardwired        |           |                |                                     |             |                         | pipelining, 32KB IC cache, floating-point multiply on multiple bits at once  (3X performance of Model 85) |
| 44    | 1966    | 512-2048    |     |                  |           |                |                                     |             |                         | Specialized for scientific computing                                                                      |
| 25    | 1968    | 16-48       |     |                  |           |                |                                     |             |                         |                                                                                                           |
| 85    | 1969    | 512-4096    |     |                  |           |                |                                     |             |                         |                                                                                                           |

