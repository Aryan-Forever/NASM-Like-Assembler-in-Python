# NASM-Like-Assembler-in-Python
Python Based One-Pass And Two-Pass Assembler That Converts Assembly Code To Machine Code
## Installation
> ### First Install Tabulate for Python
      pip install tabulate
> ### How to compile assebler:
```bash
python assembler.py [-options] file_name 
This Assembler accepts an Assembly File and Performs Following Conversions via given set of Commands/Instructions :
  
  ### Options 
One Pass

> 1. -s : To print symbol table.
> 2. -i : To create immediate code.
> 3. -l : To print literal table.
> 4. -lst : To print lst of the source file.

*TWO PASS -  
1.python assembler.py -lst new.asm	-LST File
