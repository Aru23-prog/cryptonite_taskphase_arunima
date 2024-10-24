# Process Exit Codes
    hacker@processes~process-exit-codes:~$ echo $?
    0
    hacker@processes~process-exit-codes:~$ /challenge/get-code
    Exiting with an error code!
    hacker@processes~process-exit-codes:~$ echo $?
    22
    hacker@processes~process-exit-codes:~$ /challenge/submit-code 22
    CORRECT! Here is your flag:
    pwn.college{gkCC61CKiZoxj5UWAU7oygeLqso.dljN4UDLwgzN0czW}