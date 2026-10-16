# Security Detective Challenge

## Question 1
Answer: I am logged in as hirafaisalkhan2007-arch. My home folder is /home/hirafaisalkhan2007-arch.
Commands: whoami, pwd

## Question 2
Answer: The server's name is ubuntu. It runs Ubuntu 26.04.1 LTS.
Commands: hostname, cat /etc/os-release

## Question 3
Answer: The server has 1.6Gi of RAM. It has 2.7G of free disk space.
Commands: free -h, df -h /

## Question 4
Answer: The users who can log in with /bin/bash are root and hirafaisalkhan2007-arch.
Commands: grep bash /etc/passwd

## Question 5
Answer: There are 239 processes running right now.
Commands: ps aux | wc -l

## Question 6
Answer: lab5user was created at [time from log] and deleted at [time from log].
Commands: sudo grep lab5user /var/log/auth.log
