# Introduction

## What is Assembly Language ?
    

   ##### Each personal computer has a microprocessor that manages the  computer's arithmetical, logical and control activities.
   ##### Each family of processor has its own set of instructions for handling various operations such as getting input from keyboard, displaying information on screen and performing various other jobs. These set of instructions are called 'machine language instructions'.
   ##### A processor understands only machine language instructions, which are strings of 1's and 0's. However, machine language is too obscure and complex for using in software development. So, the low-level assembly language is designed for a specific family of processors that represents various instructions in symbolic code and a more understandable form.
   
   
## Advantages of Assembly Language
  
   Having an understanding of assembly language makes one aware of - 
   
   1. How programs interface with OS,processor, and BIOS.
   2. How data is represented in memory and other external devices.
   3. How the processor accesses and executes instruction.
   4. How instructions access and process data
   5. How a program accesses external devices.
   
   Other advantages of using assembly language are - 
   
   1. It requires less memory and execution time.
   2. It allows hardware-specific complex jobs in easier way.
   3. It suitable for time-critical job.
   4. It is most suitable for writing interrupt service routines and other memory resdient programs.
   
   
 ## Basic Features of PC Hardware
    
   
   1. The main internal hardware of a PC consists of processor, memory, and registers.
    2. Registers are processor components that hold data and address.
    3. To execute a program, the system copies it from the external device into the internal memory.
    4. The processor executes the program instructions.
    5. The fundamental unit of computer storage is a bit, it could be ON (1) or OFF (0).
    6. A group of nine related bits make a bytes, out of which eight bits are used for data and the last one is used for parity.
    7. According to the rule of parity, the number of bits are ON (1) in each byte should always be odd.
    8. So, the parity bit is used to make the number of bits in a byte odd.
    9. If the parity is even, the system assumes that there had been a parity error (through rare), which might have been caused due to hardware fault or electrical disturbance.
    
   The processor supports the following data sizes - 
      
   1. Word       : a 2-byte data item
       2. DoubleWord : a 4-byte (32 - bit) data item
       3. QuadWord   : an 8-byte (64 - bit) data item
       4. Paragraph  : a 16-byte (128 - bit) data item
       5. Kilobyte   : 1024 bytes.
       6. Megabyte   : 1,048,576 bytes.
    
