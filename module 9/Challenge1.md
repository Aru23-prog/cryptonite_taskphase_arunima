    hacker@permissions~changing-file-ownership:~$ ls -l / | grep flag
    -r--------    1 root root   58 Oct 19 10:45 flag
    hacker@permissions~changing-file-ownership:~$ chown hacker /flag
    hacker@permissions~changing-file-ownership:~$ ls -l / | grep flag
    -r--------    1 hacker root   58 Oct 19 10:45 flag
    hacker@permissions~changing-file-ownership:~$ flag
    bash: flag: command not found
    hacker@permissions~changing-file-ownership:~$ cat /flag
    pwn.college{0Ud0SmHEaX9bxTESBPtUWCOrgve.dFTM2QDLwgzN0czW}