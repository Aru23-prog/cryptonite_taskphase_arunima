    hacker@processes~backgrounding-processes:~$ /challenge/run
    I'll only give you the flag if there's already another copy of me running *and 
    not suspended* in this terminal... Let's check!

        UID          PID STAT CMD
    root         312 S+   bash /challenge/run
    root         314 R+   ps -o user=UID,pid,stat,cmd

    I don't see a second me!

    To pass this level, you need to suspend me, resume the suspended process in the 
    background, and then launch a new version of me! You can background me with 
    Ctrl-Z (and resume me in the background with 'bg') or, if you're not ready to 
    do that for whatever reason, just hit Enter and I'll exit!
    ^Z
    [1]+  Stopped                 /challenge/run
    hacker@processes~backgrounding-processes:~$ bg
    [1]+ /challenge/run &



    Yay, I'm now running the background! Because of that, this text will probably 
    overlap weirdly with the shell prompt. Don't panic; just hit Enter a few times 
    to scroll this text out.
    hacker@processes~backgrounding-processes:~$ /challenge/run
    I'll only give you the flag if there's already another copy of me running *and 
    not suspended* in this terminal... Let's check!

    UID          PID STAT CMD
    root         312 S    bash /challenge/run
    root         456 S    sleep 6h
    root         561 S+   bash /challenge/run
    root         563 R+   ps -o user=UID,pid,stat,cmd

    Yay, I found another version of me running in the background! Here is the flag:
    pwn.college{UgcGBq0AbTQDXZ0yS3fRNor3cA_.ddDN4QDLwgzN0czW}