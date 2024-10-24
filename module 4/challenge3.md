# Searching manuals
    hacker@man~reading-manuals:~$ man challenge

    CHALLENGE(1)                                     Challenge Commands                                     CHALLENGE(1)

    NAME
        /challenge/challenge - print the flag!

    SYNOPSIS
        challenge OPTION

    DESCRIPTION
        Output the flag when called with the right arguments.

        --fortune
                read a fortune

        --version
                output version information and exit

        --zuvucz NUM
                print the flag if NUM is 588

    AUTHOR
        Written by Zardus.

    REPORTING BUGS
        The repository for this dojo: <https://github.com/pwncollege/linux-luminarium/>

    SEE ALSO
        man(1) bash-builtins(7)

    pwn.college                                           May 2024                                          CHALLENGE(1)
    hacker@man~reading-manuals:~$ 
    hacker@man~reading-manuals:~$ /challenge/challenge
    Incorrect usage! Please read the challenge man page!
    hacker@man~reading-manuals:~$ /challenge/challenge
    Incorrect usage! Please read the challenge man page!
    hacker@man~reading-manuals:~$ /challenge
    bash: /challenge: Is a directory
    hacker@man~reading-manuals:~$ challenge
    bash: challenge: command not found
    hacker@man~reading-manuals:~$ /challenge/challenge 588
    Incorrect usage! Please read the challenge man page!
    hacker@man~reading-manuals:~$ /challenge/challenge --588
    Incorrect usage! Please read the challenge man page!
     
    hacker@man~reading-manuals:~$ 
## Did not understand how to get flag    
