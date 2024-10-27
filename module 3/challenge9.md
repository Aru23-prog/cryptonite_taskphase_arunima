# An epic filesystem Quest
hacker@commands~an-epic-filesystem-quest:~$ /
bash: /: Is a directory
hacker@commands~an-epic-filesystem-quest:~$ ls
COLLEGE  PWN  catflag  instructions  not-the-flag  script.sh  stdout    win  x.sh
Desktop  a    college  myflag        pwn           stderr     the-flag  x
hacker@commands~an-epic-filesystem-quest:~$ cat win
cat /flag
hacker@commands~an-epic-filesystem-quest:~$ cat /flag
cat: /flag: Permission denied
hacker@commands~an-epic-filesystem-quest:~$ cat the-flag
 | 
\|/ This is the first half:
 v 
pwn.college{w6t8GsCmOlRZu_JXHo7jfN61DNr.ddDM5QDLwgzN0czW}
                              ^
     that is the second half /|\
                              |

If you only see the second half above, you redirected in *truncate* mode (>) 
rather than *append* mode (>>), and so the write of the second half to stdout 
overwrote the initial write of the first half directly to the file. Try append 
mode!
## Basically in this challenge first listed all the directories then cat the directory which might contain the flag with error and try which worked.
