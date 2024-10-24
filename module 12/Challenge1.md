# The PATH variable
    hacker@path~the-path-variable:~$ echo $PATH
    /nix/store/3v4hdb2gmpj7jv2z848ikakhzl9rjgwh-code-server/libexec/code-server/lib/vscode/bin/remote-cli:/run/challenge/bin:/run/workspace/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
    hacker@path~the-path-variable:~$ which rm
    /run/workspace/bin/rm
    hacker@path~the-path-variable:~$ PATH= /challenge/run
    Trying to remove /flag...
    /challenge/run: line 4: rm: No such file or directory
    The flag is still there! I might as well give it to you!
    pwn.college{4xBvUjjdgNYUKE5HqaBpX_3PEnl.dZzNwUDLwgzN0czW}
    hacker@path~the-path-variable:~$ rm PATH
    rm: cannot remove 'PATH': No such file or directory
    hacker@path~the-path-variable:~$ rm /challenge/run
    rm: remove write-protected regular file '/challenge/run'?