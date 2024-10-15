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