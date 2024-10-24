# Executable shell scripts    
    hacker@chaining~executable-shell-scripts:~$ echo "/challenge/solve" > script.sh
    hacker@chaining~executable-shell-scripts:~$ ls -l script.sh
    -rw-r--r-- 1 hacker hacker 17 Oct 24 16:54 script.sh
    hacker@chaining~executable-shell-scripts:~$ chmod ugo+x ~/script.sh
    hacker@chaining~executable-shell-scripts:~$ ./script.sh
    Congratulations on your shell script execution! Your flag:
    pwn.college{EVqxTlLPkZ2sO1xonNEKsLW3RS7.dRzNyUDLwgzN0czW}