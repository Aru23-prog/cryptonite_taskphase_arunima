# Killing Processes
    hacker@processes~killing-processes:~$ ps -ef
    UID          PID    PPID  C STIME TTY          TIME CMD
    root           1       0  0 12:20 ?        00:00:00 /sbin/docker-init -- /nix/var/nix/profiles/default/bin/dojo-init /r
    root           7       1  0 12:20 ?        00:00:00 /run/dojo/bin/sleep 6h
    root          71       1  0 12:20 ?        00:00:00 su -c /challenge/.launcher hacker
    hacker        73      71  0 12:20 ?        00:00:00 /challenge/dont_run
    hacker        74      73  0 12:20 ?        00:00:00 sleep 6h
    hacker        83       1  0 12:20 ?        00:00:00 /nix/store/bmmjbvb8hishfrg78ygjlynpq3ikpl39-nodejs-20.15.1/bin/node
    hacker       104      83  1 12:20 ?        00:00:06 /nix/store/bmmjbvb8hishfrg78ygjlynpq3ikpl39-nodejs-20.15.1/bin/node
    hacker       145     104  2 12:20 ?        00:00:12 /nix/store/bmmjbvb8hishfrg78ygjlynpq3ikpl39-nodejs-20.15.1/bin/node
    hacker       157     104  0 12:20 ?        00:00:01 /nix/store/bmmjbvb8hishfrg78ygjlynpq3ikpl39-nodejs-20.15.1/bin/node
    hacker       223     157  0 12:21 pts/1    00:00:00 /run/dojo/bin/bash --init-file /nix/store/3v4hdb2gmpj7jv2z848ikakhz
    hacker      1840     223  0 12:28 pts/1    00:00:00 ps -ef
    hacker@processes~killing-processes:~$ kill 73
    hacker@processes~killing-processes:~$ /challenge/run
    Great job! Here is your payment:
    pwn.college{AWoDvDWOvef9WjVaE9kYiLK7-Bu.dJDN4QDLwgzN0czW}