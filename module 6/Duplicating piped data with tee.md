## Duplicating piped data with tee
    hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn | tee pwn |/challenge/college
    Processing...


    The input to 'college' does not contain the correct secret code! This code 
    should be provided by the 'pwn' command. HINT: use 'tee' to intercept the 
    output of 'pwn' and figure out what the code needs to be.
    hacker@piping~duplicating-piped-data-with-tee:~$ 
    hacker@piping~duplicating-piped-data-with-tee:~$ 
    hacker@piping~duplicating-piped-data-with-tee:~$ cat pwn
    Usage: /challenge/pwn --secret [SECRET_ARG]

    SECRET_ARG should be "8Kqnszm4"
    hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn --secret "8Kqnszm4" | /challenge/college
    Processing...
    Correct! Passing secret value to /challenge/college...
    Great job! Here is your flag:
    pwn.college{8Kqnszm4XIYGT3Hojjcy-o5xIs3.dFjM5QDLwgzN0czW}
    hacker@piping~duplicating-piped-data-with-tee:~$ 
