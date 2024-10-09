
    hacker@man~help-for-builtins:~$ help challenge
    challenge: challenge [--fortune] [--version] [--secret SECRET]
        This builtin command will read you the flag, given the right arguments!
        
        Options:
        --fortune         display a fortune
        --version         display the version
        --secret VALUE    prints the flag, if VALUE is correct

        You must be sure to provide the right value to --secret. That value
        is "QQJrtCG5".
    hacker@man~help-for-builtins:~$ /challenge --secret "QQJrtCG5"
    bash: /challenge: Is a directory
    hacker@man~help-for-builtins:~$ challenge --secret "QQJrtCG5"
    bash: /challenge--secret: No such file or directory
    hacker@man~help-for-builtins:~$ challenge --secret "QQJrtCG5"
    Correct! Here is your flag!
    pwn.college{QQJrtCG5D7BSXJ19nXLYg4tECLm.dRTM5QDLwgzN0czW}