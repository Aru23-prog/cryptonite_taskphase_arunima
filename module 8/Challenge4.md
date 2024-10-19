# Suspending Processes
    hacker@processes~suspending-processes:~$ /challenge/run
    I'll only give you the flag if there's already another copy of me running in 
    this terminal... Let's check!

    UID          PID    PPID  C STIME TTY          TIME CMD
    root         269     222  0 17:56 pts/1    00:00:00 bash /challenge/run
    root         271     269  0 17:56 pts/1    00:00:00 ps -f

    I don't see a second me!

    To pass this level, you need to suspend me and launch me again! You can 
    background me with Ctrl-Z or, if you're not ready to do that for whatever 
    reason, just hit Enter and I'll exit!
    ^Z
    [1]+  Stopped                 /challenge/run
    hacker@processes~suspending-processes:~$ /challenge/run
    I'll only give you the flag if there's already another copy of me running in 
    this terminal... Let's check!

    UID          PID    PPID  C STIME TTY          TIME CMD
    root         269     222  0 17:56 pts/1    00:00:00 bash /challenge/run
    root         416     222  0 17:56 pts/1    00:00:00 bash /challenge/run
    root         418     416  0 17:56 pts/1    00:00:00 ps -f

    Yay, I found another version of me! Here is the flag:
    pwn.college{0OF5mU6HQfM-7oceO6YniTJRbPg.dVDN4QDLwgzN0czW}