# cscope
cscope for windows/linux

##How to build in Ubuntu/Linux
1. `autoreconf -ivf` for regenerating Makefile
2. install dependancy
-   `apt-get install flex` for installing fast lex
-   `apt-get install byacc` for installing yacc
-   `apt-get install libncurses5-dev` for fixing curses.h missing
3. ./configure
4. make
5. make install
