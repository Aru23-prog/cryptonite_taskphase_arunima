## Grepping stored results
    [HYPE] ONWARDS TO GREATNESS!

    [INFO] This challenge will perform a bunch of checks.
    [INFO] If you pass these checks, you will receive the /challenge/.data.txt file.

    [TEST] You should have redirected my stdout to a file called /tmp/data.txt. Checking...

    [HINT] File descriptors are inherited from the parent, unless the FD_CLOEXEC is set by the parent on the file descriptor.
    [HINT] For security reasons, some programs, such as python, do this by default in certain cases. Be careful if you are
    [HINT] creating and trying to pass in FDs in python.

    [PASS] The file at the other end of my stdout looks okay!
    [PASS] Success! You have satisfied all execution requirements.
    hacker@piping~grepping-stored-results:~$ grep pwn.college{ /tmp/data.txt
    pwn.college{kC6baij3mZJnmnAxS03nKgYCg2r.dhTM4QDLwgzN0czW}
