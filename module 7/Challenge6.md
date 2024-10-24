# Storing Command Output
    hacker@variables~storing-command-output:~$ cat PWN
    COLLEGE
    hacker@variables~storing-command-output:~$ echo "$COLLEGE"

    hacker@variables~storing-command-output:~$ ^C
    hacker@variables~storing-command-output:~$ PWN=$(/challenge/run)
    Congratulations! You have read the flag into the PWN variable. Now print it out 
    and submit it!
    hacker@variables~storing-command-output:~$ echo "$PWN"
    pwn.college{EIJ3SgnwY6TiwSvlszj_DUJn1Fr.dVzN0UDLwgzN0czW}