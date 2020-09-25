# Syntax

1. An assembly program can be divided into three sections - 
   . The data section
   . The bss section
   . The text section


## The data section

1. The data section is used for declaring initialized data or constants.
2. This data does not change at runtime.
3. You can declare various constant values, file names, or buffer size, etc., in this section.

  The syntax for declaring data section is - 
  
  `section.data`


## The bss section

1. The bss section is used for declaring variables.

   The syntax for declaring bss section is - 
   `section.bss`

## The text section

1. The text section is used for keeping the actual code.
2. This section must begin with the declaration global _start, which tells the kernel where the program execution begins.

    The syntax for declaring text section is - 
  
    ```section.text
          global _start
       _start:```

## Comments

1. Assembly language comment begins with a semicolon(;).
2. It may contain any printable character including blank.
3. It can appear on a line by itself, like -

   `; This program displays a  message on screen`
 
   or, on the same line along with an instruction, like - 

   `add eax, ebx ; adds ebx to eax`



## Assembly Language Statements


1. Assembly language programs consist of three types of statements -

. Executable instructions or instructions
      
 1. The executable instructions or simply instructions tell the processor what to do.
 2. Each instruction consists of an operation code (opcode).
 3. Each executable instruction generates one machine language instruction.
   
. Assembler directives or pseudo-ops

 1. The assembler directives or pseudo-ops tell the assembler about the various aspects of the assembly process.
 2. These are non-executable and do not generate machine language instrucions.
 

. Macros
 
 1. Macros are basically a text substitution mechanism.

## Syntax of Assembly Language Statements

1. Assembly language statements are entered one statement per line.
2. Each statement follows the following format -

`[label] mnemonic [operands] [;comment]`

3. The fields in the square brackets are optional.
4. A basic instruction has two parts, the first one is the name of the instruction ( or the mnemonic), which is to be executed, and second are the operands or the parameters of the commands.



  





 
