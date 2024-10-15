# Printing Variables
## In the given challenge, when I read printing echo command came in my mind first but using variable was new for me 
  hacker@variables~printing-variables:~$ echo $FLAG
  pwn.college{s0dBUQ02frzfNn5RDKz1LrACcI9.ddTN1QDLwgzN0czW}
## I got flag for this question
# Setting Variables
## We can assign values using ‘=’ like any other coding languages but without spaces around  and $ is used with variable to access the variable and not assign the variable
  hacker@variables~setting-variables:~$ PWN=COLLEGE
  You've set the PWN variable properly! As promised, here is the flag:
  pwn.college{sdoHz6miPNn46cmJd0JfQ0wr7bJ.dlTN1QDLwgzN0czW}
  ##I assigned successfully and received the flag
# Multi-word Variables
## This is very similar to previous questions ie assigning values to variable but instead of 1 variable using 2 variables  and treating as 1 token
  hacker@variables~multi-word-variables:~$ PWN=COLLEGE YEAH
  bash: YEAH: command not found
  
  It looks like you did not put quotes around the multi-word value in your 
  variable assignment! This caused the shell to treat 'YEAH' as a command. Quote 
  your multi-word values!
  hacker@variables~multi-word-variables:~$ PWN="COLLEGE YEAH"
  You've set the PWN variable properly! As promised, here is the flag:
  pwn.college{UzwXHsZHXjlkauvr79r-kEtyxYb.dBjN1QDLwgzN0czW}
## I received the flag in this question
# Exporting Variables
## New command used in this question is -sh which according to this source https://www.ibm.com/docs/hr/aix/7.1?topic=s-sh-command invokes the default shell.
  This command they used here to show that this variable assigned is specific to a shell
  hacker@variables~exporting-variables:~$ export PWN='COLLEGE'
  You've set the PWN variable to the proper value!
  You've set the COLLEGE variable to the proper value!
  hacker@variables~exporting-variables:~$ /challenge/run
  CORRECT!
  You have exported PWN=COLLEGE and set, but not exported, COLLEGE=PWN. Great 
  job! Here is your flag:
  pwn.college{Uy2RCozE5djH3hGzqhxsJfTAaDA.dJjN1QDLwgzN0czW}
  You've set the PWN variable to the proper value!
  You've set the COLLEGE variable to the proper value!

# Printing Exported Variable 
  *.tmp=00;90:*.ucf-dist=00;90:*.ucf-new=00;90:*.ucf-old=00;90:
  GIT_ASKPASS=/nix/store/3v4hdb2gmpj7jv2z848ikakhzl9rjgwh-code-server/libexec/code-  server/lib/vscode/extensions/git/dist/askpass.sh
  FLAG=pwn.college{gaiv5nqxlopDeAaoYQQCOTFkdW4.dhTN1QDLwgzN0czW}
  VSCODE_GIT_ASKPASS_EXTRA_ARGS=
  LESSCLOSE=/usr/bin/lesspipe %s %s
  TERM=xterm-256color
  LESSOPEN=| /usr/bin/lesspipe %s
  VSCODE_GIT_IPC_HANDLE=/tmp/vscode-git-fcf2488e0e.sock
  SHLVL=2
  LC_CTYPE=C.UTF-8
  VSCODE_GIT_ASKPASS_MAIN=/nix/store/3v4hdb2gmpj7jv2z848ikakhzl9rjgwh-code-server/libexec/code-server/lib/vscode/extensions/git/dist/askpass-main.js