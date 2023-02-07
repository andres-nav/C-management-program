The Compile.sh must be executable, run to do so: $ chmod +x Compile.sh

Command to compile and run with valgrind: $ ./Compile.sh valgrind 
Command to compile and run: $ ./Compile.sh

Command to compile: $ ./Compile.sh debug
Alternative command to compile: $ gcc -Wall -g -o P1 P1.c Forms.c Tools.c Heads.c Boxofficer.c Chief.c Admin.c
Alternative command to run with valgrind: $ valgrind -s --leak-check=full --show-leak-kinds=all --track-origins=yes ./P1
Alternative command to run: $ ./P1
