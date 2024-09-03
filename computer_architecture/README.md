# Computer Architecture

## Content

- Disk Storage
- RAM
- Cache
- CPU

## Disk Storage

- It can be either HDD or SSD type
- This data storage is non-volatile, meaning that it maintains data without power
- Usually contains OS, applications and user files

## RAM

- Primary active data holder
- Variables, intermediate computations, runtime stack and more are stored here
- Volatile memory (it requires power to retain its contents)
- \> 5000 MB/s read/write speeds

## Cache

- Typically measured in MBs
- Acces times are faster than RAM (just a few nanoseconds for L1 cache)
- CPU first checks L1 cache for data
  - if not found it will check L2 and L3 cache
    - if not found it will check RAM
- We store frequently used data here to improve CPU performance

## CPU

- "Brain of the computer"
- Fetches, decodes and executes instructions
- Compilers translates "high" level code (C, Java, Pyhton, etc) into machine code for the CPU to execute it
- Can read from Disk, RAM and Cache
