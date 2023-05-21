# Linux

## how to read `ls` command long list format
the command format lists file permissions, number of links, owner name, owner of group, file size, time of last modification, and the file or directory name.
`>ls -l
 > drwxr-xr-x  3 chizhi  staff    96 Feb 11 21:45 LLVM
 > -rw-r--r--  1 chizhi  staff  3047 Feb 11 20:45 README.md`  
`ls -lh` file is displayed as human-readable format

## Physical cores vs. Logical cores and HyperThreading
A physical core is the physical core on the CPU. The logical processor (logical core or CPU) is how many of those cores are divided using hyperthreading to allow multiple instructions (threads) to be processed on each core simultaneously

