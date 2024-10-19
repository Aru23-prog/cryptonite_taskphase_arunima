
    hacker@permissions~groups-and-files:~$ ls -l
    total 32
    -rw-r--r-- 1 hacker hacker    4 Oct  9 11:18 COLLEGE
    drwxr-xr-x 2 hacker hacker 4096 Oct  2 14:54 Desktop
    -rw-r--r-- 1 hacker hacker    8 Oct  9 14:03 PWN
    -rw-r--r-- 1 root   hacker   58 Oct  9 10:54 a
    lrwxrwxrwx 1 hacker hacker   18 Oct  9 15:55 catflag -> /challenge/catflag
    -rw-r--r-- 1 hacker hacker    0 Oct  9 15:42 college
    -rw-r--r-- 1 hacker hacker  829 Oct  9 13:49 instructions
    -rw-r--r-- 1 hacker hacker    0 Oct  9 17:37 myflag
    lrwxrwxrwx 1 hacker hacker    5 Oct  9 15:57 not-the-flag -> /flag
    -rw-r--r-- 1 root   hacker   77 Oct  9 17:38 pwn
    -rw-r--r-- 1 hacker hacker   38 Oct  9 13:36 stderr
    -rw-r--r-- 1 hacker hacker    0 Oct  9 12:40 stdout
    -rw-r--r-- 1 hacker hacker  435 Oct  9 12:43 the-flag
    -rw-r--r-- 1 hacker hacker    0 Oct 19 05:09 x
    hacker@permissions~groups-and-files:~$ chgrp hacker /flag
    hacker@permissions~groups-and-files:~$ /flag
    bash: /flag: Permission denied
    hacker@permissions~groups-and-files:~$ cat /flag
    pwn.college{olu2QEcY_NVI9mdPBMjOAGs8ott.dFzNyUDLwgzN0czW}