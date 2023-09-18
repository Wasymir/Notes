# Processor

15.09.2023

___

## How processor works (simplified)

1) Get an instruction from memory
2) Analyze what the instruction is
3) Use the appropriate subparts of CPU to execute it
4) Save the result
5) Move on to the next operation

## RISC vs CISC

> **Instruction set** - a list of all the machine code instructions set a CPU can perform.\
> **CISC** - complex instruction set computing\
> **RISC** - reduced instruction set computing.

CISC | RISC
---|---
powerful instructions, a lot of them | few (relatively) basic instructions
less energy efficient | more energy efficient
single instruction will take longer to execute | executing single instruction will take less time

## Metrics

> **Clock Speed (max, avg, min)** - number of cycles a CPU does per second [GHz].\
> **Number of Cores** - number of largely separate processors on the same piece of silicon sharing caches.\
> **MIPS** - millions of instructions per second.\
> **FLOPS** - Floating-point operators per second. ![big floppa](https://i.kym-cdn.com/photos/images/newsfeed/001/865/723/8f3.jpg)\
> **World Length (address size)** - max amount of memory, processor can address

## Other Devices that Can Affect Processing Efficiency

> **GPU** - a lot (potentially 1000s) simple cores that can do the same instruction on different data at the same time.
> **NIC** - network interface card
