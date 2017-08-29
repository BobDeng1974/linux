


make[1]: Entering directory `/home/jfeng/Project/comps/os/linux/apue/apue.3e/threads'
gcc -ansi -I../include -Wall -DLINUX -D_GNU_SOURCE  badexit2.c -o badexit2  -L../lib -lapue -pthread -lrt -lbsd
/usr/bin/ld: cannot find -lbsd
collect2: error: ld returned 1 exit status
make[1]: *** [badexit2] Error 1
make[1]: Leaving directory `/home/jfeng/Project/comps/os/linux/apue/apue.3e/threads'
make: *** [all] Error 1

sudo apt-get install libbsd-dev

