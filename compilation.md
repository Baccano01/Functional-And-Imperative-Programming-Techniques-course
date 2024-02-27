To compile a haskell program enter on the terminal:

<code>ghc myprogram.hs</code>

The compilation will generate two files:
1. *myprogram.o* - which is the object file generated
2. *myprogram.hi* - the interface file, similar to .h file in C/C++, that contains information on data types, functions, etc. that were used in *myprogram.hs*
   and information that can't be stored in *myprogram.o*.

To execute enter on the terminal: <code>./myprogram</code>
