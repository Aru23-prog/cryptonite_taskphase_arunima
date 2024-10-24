# Adding Commands    
    hacker@path~adding-commands:~$ echo "cat /flag" > win
    hacker@path~adding-commands:~$ pwd
    /home/hacker
    hacker@path~adding-commands:~$ PATH=$PATH:/home/hacker
    hacker@path~adding-commands:~$ chmod ug+x /home/hacker/win
    hacker@path~adding-commands:~$ /challenge/run
    Invoking 'win'....
    pwn.college{UibA0KddHXflfhww36-9Ywsz0j9.dZzNyUDLwgzN0czW}