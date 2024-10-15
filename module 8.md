# Listing Processes
    hacker@processes~listing-processes:~$ ps -ef
    UID          PID    PPID  C STIME TTY          TIME CMD
    root           1       0  0 11:47 ?        00:00:00 /sbin/docker-init -- /nix/var/nix/profiles/default/bin/dojo-init /r
    root           7       1  0 11:47 ?        00:00:00 /run/dojo/bin/sleep 6h
    root          68       1  0 11:47 ?        00:00:00 /challenge/30312-run-22610
    root          72      68  0 11:47 ?        00:00:00 sleep 6h
    hacker        81       1  1 11:47 ?        00:00:00 /nix/store/bmmjbvb8hishfrg78ygjlynpq3ikpl39-nodejs-20.15.1/bin/node
    hacker       102      81  8 11:47 ?        00:00:05 /nix/store/bmmjbvb8hishfrg78ygjlynpq3ikpl39-nodejs-20.15.1/bin/node
    hacker       145     102  5 11:47 ?        00:00:02 /nix/store/bmmjbvb8hishfrg78ygjlynpq3ikpl39-nodejs-20.15.1/bin/node
    hacker       163     102  0 11:47 ?        00:00:00 /nix/store/bmmjbvb8hishfrg78ygjlynpq3ikpl39-nodejs-20.15.1/bin/node
    hacker       229     163  0 11:48 pts/1    00:00:00 /run/dojo/bin/bash --init-file /nix/store/3v4hdb2gmpj7jv2z848ikakhz
    hacker       422     229  0 11:48 pts/1    00:00:00 ps -ef
    hacker@processes~listing-processes:~$ ps -aux
    USER         PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
    root           1  0.0  0.0   1056   640 ?        Ss   11:47   0:00 /sbin/docker-init -- /nix/var/nix/profiles/default/b
    root           7  0.0  0.0   5052  2560 ?        S    11:47   0:00 /run/dojo/bin/sleep 6h
    root          68  0.0  0.0   4132  2560 ?        S    11:47   0:00 /challenge/30312-run-22610
    root          72  0.0  0.0   2744  1600 ?        S    11:47   0:00 sleep 6h
    hacker        81  1.0  0.0 1100404 62664 ?       Sl   11:47   0:00 /nix/store/bmmjbvb8hishfrg78ygjlynpq3ikpl39-nodejs-2
    hacker       102  7.0  0.0 1314776 86072 ?       Sl   11:47   0:05 /nix/store/bmmjbvb8hishfrg78ygjlynpq3ikpl39-nodejs-2
    hacker       145  4.5  0.0 1329132 91136 ?       Sl   11:47   0:03 /nix/store/bmmjbvb8hishfrg78ygjlynpq3ikpl39-nodejs-2
    hacker       163  0.7  0.0 1111840 55408 ?       Rl   11:47   0:00 /nix/store/bmmjbvb8hishfrg78ygjlynpq3ikpl39-nodejs-2
    hacker       229  0.0  0.0   5368  3840 pts/1    Ss   11:48   0:00 /run/dojo/bin/bash --init-file /nix/store/3v4hdb2gmp
    hacker       485  0.0  0.0   7868  3520 pts/1    R+   11:49   0:00 ps -aux
    hacker@processes~listing-processes:~$ /challenge/30312
    bash: /challenge/30312: No such file or directory
    hacker@processes~listing-processes:~$ /run/dojo/bin/sleep
    /run/dojo/bin/sleep: missing operand
    Try '/run/dojo/bin/sleep --help' for more information.
    hacker@processes~listing-processes:~$ /challenge/30312-run-22610
    Yahaha, you found me! Here is your flag:
    pwn.college{wqkXdLMOJ9NLi7JUfAwwJP635DX.dhzM4QDLwgzN0czW}M
