clangAST-calltree
=================

little test project maybe usable as a tutorial for parsing an C++ AST with clang

the project currently parses itself. example output: http://www.icetruck.de/0/pics/clang9.png

comments will be added (at latest if i am asked to do so)


Building
--------
The included makefile can be used to compile the code. The variable, LLVMCONFIG, near the top
must be defined to point to the llvm-config utility, which is part of the clang distribution.

