# Redirecting Script Output    
    hacker@chaining~redirecting-script-output:~$ echo "/challenge/pwn
    > /challenge/college" > x.sh
    hacker@chaining~redirecting-script-output:~$ cat x.sh
    /challenge/pwn
    /challenge/college
    hacker@chaining~redirecting-script-output:~$ bash x.sh | /challenge/solve
    Correct! Here is your flag:
    pwn.college{km8srXNTR7-LwYjGVp-zmlFFVjv.dhTM5QDLwgzN0czW}
