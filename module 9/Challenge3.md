
    hacker@permissions~fun-with-groups-names:~$ id
    uid=1000(hacker) gid=1000(grp3591) groups=1000(grp3591)
    hacker@permissions~fun-with-groups-names:~$ ls -l
    total 32
    -rw-r--r-- 1 hacker grp3591    4 Oct  9 11:18 COLLEGE
    drwxr-xr-x 2 hacker grp3591 4096 Oct  2 14:54 Desktop
    -rw-r--r-- 1 hacker grp3591    8 Oct  9 14:03 PWN
    -rw-r--r-- 1 root   grp3591   58 Oct  9 10:54 a
    lrwxrwxrwx 1 hacker grp3591   18 Oct  9 15:55 catflag -> /challenge/catflag
    -rw-r--r-- 1 hacker grp3591    0 Oct  9 15:42 college
    -rw-r--r-- 1 hacker grp3591  829 Oct  9 13:49 instructions
    -rw-r--r-- 1 hacker grp3591    0 Oct  9 17:37 myflag
    lrwxrwxrwx 1 hacker grp3591    5 Oct  9 15:57 not-the-flag -> /flag
    -rw-r--r-- 1 root   grp3591   77 Oct  9 17:38 pwn
    -rw-r--r-- 1 hacker grp3591   38 Oct  9 13:36 stderr
    -rw-r--r-- 1 hacker grp3591    0 Oct  9 12:40 stdout
    -rw-r--r-- 1 hacker grp3591  435 Oct  9 12:43 the-flag
    -rw-r--r-- 1 hacker grp3591    0 Oct 19 05:09 x
    hacker@permissions~fun-with-groups-names:~$ cat /flag
    cat: /flag: Permission denied
    hacker@permissions~fun-with-groups-names:~$ chgrp hacker /flag
    chgrp: invalid group: ‘hacker’
    hacker@permissions~fun-with-groups-names:~$ chgrp grp3591 /flag
    hacker@permissions~fun-with-groups-names:~$ cat /flag
    pwn.college{wxkxwWuYyxGmGnwjOnk1OqRLoTV.dJzNyUDLwgzN0czW}