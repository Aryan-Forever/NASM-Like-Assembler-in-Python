# NASM-Like-Assembler-in-Python
Python Based One-Pass And Two-Pass Assembler That Converts Assembly Code To Machine Code

This Assembler accepts an Assembly File and Performs Following Conversions via given set of Commands/Instructions :

*ONE PASS -
  python assembler.py -s new.asm	 	-Symbol Table
  python assembler.py -l new.asm		-Literal Table
  python assembler.py -i new.asm		-Intermediate Table
  
*TWO PASS -  
  python assembler.py -lst new.asm	-LST File
