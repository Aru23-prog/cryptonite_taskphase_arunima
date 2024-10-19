
    hacker@permissions~the-suid-bit:~$ ls -l /challenge
    total 16
    -rwsr-xr-x 1 root root 1450 Aug 18 06:57 DESCRIPTION.md
    drwsr-xr-x 2 root root 4096 Jul 19 20:31 bin
    -rwxr-xr-x 1 root root  155 Jul 12 10:30 getroot
    -rwsr-xr-x 1 root root   43 Feb  8  2024 run
    hacker@permissions~the-suid-bit:~$ chmod u+s /challenge/getroot
    hacker@permissions~the-suid-bit:~$ ls -l /challenge/getroot
    -rwsr-xr-x 1 root root 155 Jul 12 10:30 /challenge/getroot
    hacker@permissions~the-suid-bit:~$ /challenge/getroot
    SUCCESS! You have set the suid bit on this program, and it is running as root! 
    Here is your shell...
    root@permissions~the-suid-bit:~# /challenge/getroot
    SUCCESS! You have set the suid bit on this program, and it is running as root! 
    Here is your shell...
    root@permissions~the-suid-bit:~# cat /flag
    pwn.college{80OqpFTXPNEqm9_NHEGPCasX1yp.dNTM2QDLwgzN0czW}