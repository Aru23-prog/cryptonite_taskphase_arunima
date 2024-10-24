# Adding Commands        
        hacker@path~setting-path:~$ echo $PATH
        /nix/store/3v4hdb2gmpj7jv2z848ikakhzl9rjgwh-code-server/libexec/code-server/lib/vscode/bin/remote-cli:/run/challenge/bin:/run/workspace/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
        hacker@path~setting-path:~$ PATH= /challenge/run
        Invoking 'win'....
        /challenge/run: line 4: win: No such file or directory
        It looks like that did not work... Did you set PATH correctly?
        hacker@path~setting-path:~$ PATH="/challenge/more_commands/" /challenge/run
        Invoking 'win'....
        Congratulations! You properly set the flag and 'win' has launched!
        pwn.college{Q0xBUMl8DxrkKFBE0oOQHIjlkdD.dVzNyUDLwgzN0czW}
## I followed the instruction        