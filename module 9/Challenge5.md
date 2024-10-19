    hacker@permissions~executable-files:~$ ls -l /challenge/run
    -r--r--r-- 1 hacker hacker 32 Jul  4 06:37 /challenge/run
    hacker@permissions~executable-files:~$ /challenge/run
    bash: /challenge/run: Permission denied
    hacker@permissions~executable-files:~$ chmod u+x /challenge/run
    hacker@permissions~executable-files:~$ /challenge/run
    Successful execution! Here is your flag:
    pwn.college{IREnX-nX9eZzgff-w7zCGaDIvsG.dJTM2QDLwgzN0czW}