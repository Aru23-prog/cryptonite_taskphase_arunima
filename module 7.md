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
hacker@variables~printing-exported-variables:~$ env
SHELL=/run/dojo/bin/bash
COLORTERM=truecolor
TERM_PROGRAM_VERSION=1.89.1
HOSTNAME=variables~printing-exported-variables
VSCODE_PROXY_URI=https://pwn.college/workspace/code/proxy/{{port}}/
PWD=/home/hacker
DOJO_AUTH_TOKEN=a6c808c19c0579c6c5eca26050c76b008b88ce1493afa6da5cb4582b70fc6743
VSCODE_GIT_ASKPASS_NODE=/nix/store/bmmjbvb8hishfrg78ygjlynpq3ikpl39-nodejs-20.15.1/bin/node
HOME=/home/hacker
LANG=C.UTF-8
LS_COLORS=rs=0:di=01;34:ln=01;36:mh=00:pi=40;33:so=01;35:do=01;35:bd=40;33;01:cd=40;33;01:or=40;31;01:mi=00:su=37;41:sg=30;43:ca=00:tw=30;42:ow=34;42:st=37;44:ex=01;32:*.7z=01;31:*.ace=01;31:*.alz=01;31:*.apk=01;31:*.arc=01;31:*.arj=01;31:*.bz=01;31:*.bz2=01;31:*.cab=01;31:*.cpio=01;31:*.crate=01;31:*.deb=01;31:*.drpm=01;31:*.dwm=01;31:*.dz=01;31:*.ear=01;31:*.egg=01;31:*.esd=01;31:*.gz=01;31:*.jar=01;31:*.lha=01;31:*.lrz=01;31:*.lz=01;31:*.lz4=01;31:*.lzh=01;31:*.lzma=01;31:*.lzo=01;31:*.pyz=01;31:*.rar=01;31:*.rpm=01;31:*.rz=01;31:*.sar=01;31:*.swm=01;31:*.t7z=01;31:*.tar=01;31:*.taz=01;31:*.tbz=01;31:*.tbz2=01;31:*.tgz=01;31:*.tlz=01;31:*.txz=01;31:*.tz=01;31:*.tzo=01;31:*.tzst=01;31:*.udeb=01;31:*.war=01;31:*.whl=01;31:*.wim=01;31:*.xz=01;31:*.z=01;31:*.zip=01;31:*.zoo=01;31:*.zst=01;31:*.avif=01;35:*.jpg=01;35:*.jpeg=01;35:*.mjpg=01;35:*.mjpeg=01;35:*.gif=01;35:*.bmp=01;35:*.pbm=01;35:*.pgm=01;35:*.ppm=01;35:*.tga=01;35:*.xbm=01;35:*.xpm=01;35:*.tif=01;35:*.tiff=01;35:*.png=01;35:*.svg=01;35:*.svgz=01;35:*.mng=01;35:*.pcx=01;35:*.mov=01;35:*.mpg=01;35:*.mpeg=01;35:*.m2v=01;35:*.mkv=01;35:*.webm=01;35:*.webp=01;35:*.ogm=01;35:*.mp4=01;35:*.m4v=01;35:*.mp4v=01;35:*.vob=01;35:*.qt=01;35:*.nuv=01;35:*.wmv=01;35:*.asf=01;35:*.rm=01;35:*.rmvb=01;35:*.flc=01;35:*.avi=01;35:*.fli=01;35:*.flv=01;35:*.gl=01;35:*.dl=01;35:*.xcf=01;35:*.xwd=01;35:*.yuv=01;35:*.cgm=01;35:*.emf=01;35:*.ogv=01;35:*.ogx=01;35:*.aac=00;36:*.au=00;36:*.flac=00;36:*.m4a=00;36:*.mid=00;36:*.midi=00;36:*.mka=00;36:*.mp3=00;36:*.mpc=00;36:*.ogg=00;36:*.ra=00;36:*.wav=00;36:*.oga=00;36:*.opus=00;36:*.spx=00;36:*.xspf=00;36:*~=00;90:*#=00;90:*.bak=00;90:*.crdownload=00;90:*.dpkg-dist=00;90:*.dpkg-new=00;90:*.dpkg-old=00;90:*.dpkg-tmp=00;90:*.old=00;90:*.orig=00;90:*.part=00;90:*.rej=00;90:*.rpmnew=00;90:*.rpmorig=00;90:*.rpmsave=00;90:*.swp=00;90:*.tmp=00;90:*.ucf-dist=00;90:*.ucf-new=00;90:*.ucf-old=00;90:
GIT_ASKPASS=/nix/store/3v4hdb2gmpj7jv2z848ikakhzl9rjgwh-code-server/libexec/code-server/lib/vscode/extensions/git/dist/askpass.sh
FLAG=pwn.college{gaiv5nqxlopDeAaoYQQCOTFkdW4.dhTN1QDLwgzN0czW}
VSCODE_GIT_ASKPASS_EXTRA_ARGS=
LESSCLOSE=/usr/bin/lesspipe %s %s
TERM=xterm-256color
LESSOPEN=| /usr/bin/lesspipe %s
VSCODE_GIT_IPC_HANDLE=/tmp/vscode-git-fcf2488e0e.sock
SHLVL=2
LC_CTYPE=C.UTF-8
VSCODE_GIT_ASKPASS_MAIN=/nix/store/3v4hdb2gmpj7jv2z848ikakhzl9rjgwh-code-server/libexec/code-server/lib/vscode/extensions/git/dist/askpass-main.js
BROWSER=/nix/store/3v4hdb2gmpj7jv2z848ikakhzl9rjgwh-code-server/libexec/code-server/lib/vscode/bin/helpers/browser.sh
PATH=/nix/store/3v4hdb2gmpj7jv2z848ikakhzl9rjgwh-code-server/libexec/code-server/lib/vscode/bin/remote-cli:/run/challenge/bin:/run/workspace/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
NODE_EXEC_PATH=/nix/store/bmmjbvb8hishfrg78ygjlynpq3ikpl39-nodejs-20.15.1/bin/node
TERM_PROGRAM=vscode
VSCODE_IPC_HOOK_CLI=/tmp/vscode-ipc-aa97a37b-7857-4c64-8e8b-855bfe6291ef.sock
_=/run/workspace/bin/env
# Storing Command Output
