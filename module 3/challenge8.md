# hidden files
    hacker@commands~hidden-files:~$ ls -a
.              .bash_history  .cache   .lesshst  COLLEGE  a        instructions  pwn        stdout    x
..             .bash_logout   .config  .local    Desktop  catflag  myflag        script.sh  the-flag  x.sh
.ICEauthority  .bashrc        .dbus    .profile  PWN      college  not-the-flag  stderr     win
hacker@commands~hidden-files:~$ ls -a /
.   .dockerenv           bin   challenge  etc   lib    lib64   media  nix  proc  run   srv  tmp  var
..  .flag-6264103931791  boot  dev        home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@commands~hidden-files:~$ cat .flag-6264103931791
cat: .flag-6264103931791: No such file or directory
hacker@commands~hidden-files:~$ cat /.flag-6264103931791
pwn.college{c-LtcCGCPPr4vvmW-S3twB88JWn.dBTN4QDLwgzN0czW}
## -a show all th hidden files in directory.Then cat the hidden flag file.        
    
