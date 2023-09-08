# Memory

8.09.2023

___

### Types:
1) Register - most limited memory, embedded directly into cpu.
2) Caches - intermediate buffer between RAM & CPU
3) RAM - random-access memory
4) ROM - Read-only memory
5) SSD - Solid state drive
6) Flash
7) HDD - Hard Disc Drive

The lower we are in the list the bigger storage size they have.\
The higher we are in the list the faster data access is.

___

Primary Memory | Secondary Memory
---|---
Registers | SSD
Caches | Flash
RAM | HDD
ROM |

Computer can start & run without Secondary Memory, but can't without Primary Memory.

___

**Persistent memory** remains between reboots, does not need power to store data.\
**Violate memory** disappears between reboots, needs power to store data 

Persistent memory:
1) SDD 
2) HDD
3) ROM
4) Flash

Volatile memory:
1) Registers
2) Catches
3) RAM 
 
___

**L1 Cache** is inside CPU\
**L2 Cache** is outside CPU
```

                   +------|CPU|--------+
+---+  +--------+  |  +--------+       |
|RAM|--|L2 CACHE|--|--|L1 CACHE|-- CPU |
+---+  +--------+  |  +--------+       |
                   +-------------------+
```
___

**Latency** - time needed to start getting memory from somewhere.
___

**DRAM** - Dynamic RAM - looses data over time (even with electricity), need to be refreshed periodically.\  
**SRAM** - Static RAM - data stats as long as power is on, but it is more complicated and expensive, but is faster.\
We use SRAM in Registers and Caches, DRAM we use in RAM.
___

**BIOS** - Basic Input Output System\
**UEFI** - Unified Extensible Firmware Interface (BIOS but better)

___

