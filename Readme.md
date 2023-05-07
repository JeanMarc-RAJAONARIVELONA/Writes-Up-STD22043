# Devoir Sys1 sur bandit

## level 0

`cmd : ssh bandit0@bandit.labs.overthewire.org -p2220`

**mdp : bandit0**

## level 0 --> level 1 :

`cmd : cat readme`

**mdp : NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL**

## level 1 --> level 2 :

`cmd :cat ./-`

**mdp :rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi**

## level 2 --> level 3 :

`cmd :cat "spaces in this filename"`

**mdp :aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG**

## level 3 --> level 4 :

`cmd1 :cd inhere`

`cmd2 :ls -a`

`cmd3:cat .hidden`

**mdp :2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe**

## level 4 --> level 5 :

`cmd1 :cd inhere`

`cmd2 :cat ./-file07`

**mdp :lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR**

## level 5 --> level 6 :

`cmd1 :cd inhere`

`cmd2 :cat ./maybehere07/.file2`

**mdp :P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU**

## level 6 --> level 7 :

`cmd1 :find -size 33c -user bandit7 -group bandit6 -type f`

`cmd2 :cat /var/lib/dpkg/info/bandit7.password`

**mdp :z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S**

## level 7 --> level 8 :

`cmd1 :cat data.txt | grep millionth`

**mdp :TESKZC0XvTetK0S9xNwm25STk5iWrBvP**

## level 8 --> level 9 :

`cmd1 :cat data.txt | sort | uniq -u`

**mdp :EN632PlfYiZbn3PhVK3XOGSlNInNE00t**

## level 9 --> level 10 :

`cmd1 :strings data.txt | grep ===`

**mdp :G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s**

## level 10 --> level 11 :

`cmd1 :ls`

`cmd2 :cat data.txt | base64 -d`

**mdp :6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM**

## level 11 --> level 12 :

` cmd1 :ls`

` cmd2 :cat data.txt | tr '[A-Za-z]' '[N-ZA-Mn-za-m]'`

**mdp : JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv**

## level 12 --> level 13 :

`cmd1 : ls -al`

`cmd2 : mkdir /tmp/JeanMarc`

`cmd3 : cp data.txt /tmp/JeanMarc`

`cmd4 : cd /tmp/JeanMarc`

`cmd5 : file data.txt`

`cmd6 : ls -al`

`cmd7 : xxd -r data.txt data1`

`cmd8 : ls`

`cmd9 : file data1`

`cmd10 : mv data1 data2.gz`

`cmd11 : gzip -d data2.gz`

`cmd12 : file data2`

`cmd13 : ls`

`cmd14 : mv data2 data3.bz2`

`cmd15 : ls`

`cmd16 : file data3.bz2`

`cmd17 : bzip2 -d data3.bz2`

`cmd18 : ls`

`cmd19 : file data3`

`cmd20 : mv data3 data4.gz`

`cmd21 : data3 data4.gz`

`cmd22 : ls`

`cmd23 : gzip -d data4.gz`

`cmd24 : ls`

`cmd25 : file data4`

`cmd26 : tar -xvf data4`

`cmd27 : file data5.bin`

`cmd28 : tar -xvf data5.bin`

`cmd29 : file data6.bin`

`cmd30 : mv data6.bin data7.bz2`

`cmd31 : file data7.bz2`

`cmd32 : bzip2 -d data7.bz2`

`cmd33 : file data7`

`cmd34 : tar -xvf data7`

`cmd35 : file data8.bin`

`cmd38 : mv data8.bin data9.gz`

`cmd39 : gzip -d data9.gz`

`cmd40 : file data9`

`cmd41 : cat data9`

**mdp :wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw**

## level 13 --> level 14 :

`cmd1 :cat sshkey.private`

`cmd2 : ssh -i sshkey.private bandit14@localhost -p2220`

**mdp : il n'y a pas**

## level 14 --> level 15 :

`cmd1 :cd /etc/bandit_pass/`

`cmd2 : ls`

`cmd3 : cat bandit14`

`cmd4 : echo fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq | nc localhost 30000`

**mdp : **

## level 15 --> level 16 :

`cmd1 :ls`

`cmd2 : cat /etc/bandit_pass/bandit15`

`cmd3 : openssl s_client -connect localhost:30001`

**mdp : JQttfApK4SeyHwDlI9SXGR50qclOAil1**

## level 16 --> level 17 :

`cmd1 :nmap -A localhost -p 31000-32000`

`cmd2 : cat /etc/bandit_pass/bandit16`

`cmd3 : openssl s_client -connect localhost:31790`

`cmd4 : cd /tmp`

`cmd5 : nano ssh-17.private`

`cmd6 : ssh -i ssh-17.private bandit17@localhost`

`cmd7 : chmod 600 ssh-17.private`

`cmd8 : ssh -i ssh-17.private bandit17@localhost`

`cmd9 : cat /etc/bandit_pass/bandit17`

**mdp : VwOSWtCA7lRKkTfbr2IDh6awj9RNZM5e**

## level 17 --> level 18 :

`cmd1 :diff passwords.old passwords.new`

**mdp : hga5tuuCLF6fFzUpnagiMN8ssu9LFrdg**

## level 18 --> level 19 :

`cmd1 : ssh bandit18@bandit.labs.overthewire.org -p 2220 cat readme`

**mdp : awhqfNnAbc1naukrpqDYcF95h7HoMTrC**

## level 19 --> level 20 :

`cmd1 : ls`

`cmd2 : file bandit20-do`

`cmd3 : ./bandit20-do cat /etc/bandit_pass/bandit20`

**mdp : VxCazJaVykI6W36BkBU0mJTCM8rR95XT**

## level 20 --> level 21 :

`cmd1 : echo -n 'VxCazJaVykI6W36BkBU0mJTCM8rR95XT' | nc -l -p 1234 &`

`cmd2 : ./suconnect 1234`

**mdp : NvEJF7oVjkddltPSrdKEFOllh9V1IBcq**

## level 21 --> level 22 :

`cmd1 : ls -la /etc/cron.d`

`cmd2 : cat /etc/cron.d/cronjob_bandit22`

`cmd3 : cat /usr/bin/cronjob_bandit22.sh`

`cmd4 : @reboot bandit22 /usr/bin/cronjob_bandit22.sh &> /dev/null`

`cmd5 : cat /usr/bin/cronjob_bandit22.sh`

`cmd6 : chmod 644 /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv`

`cmd7 : cat /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv`

**mdp : WdDozAdTM2z9DiFEQ2mGlwngMfj4EZff**

## level 22 --> level 23 :

`cmd1 : ls -la /etc/cron.d`

`cmd2 : cat /etc/cron.d/cronjob_bandit23`

`cmd3 : cat /usr/bin/cronjob_bandit23.sh`

`cmd4 : echo I am user bandit23 | md5sum | cut -d ' ' -f 1`

`cmd5 : echo I am user bandit23 | md5sum | cut -d ' ' -f 1`

`cmd6 : cat /tmp/8ca319486bfbbc3663ea0fbe81326349`

**mdp : QYw0Y2aiA672PsMmh9puTQuhoz8SyR2G**

## level 23 --> level 24 :

`cmd1 : cd /etc/cron.d`

`cmd2 : ls -la`

`cmd3 : cat cronjob_bandit24`

`cmd4 : cat /usr/bin/cronjob_bandit24.sh`

`cmd5 : mkdir /tmp/jeanmarc123`

`cmd6 : cd /tmp/jeanmarc123`

`cmd7 : nano bandit24.sh`

`cmd8 : !/bin/bash`

`cmd9 : cat /etc/bandit_pass/bandit24 >> /tmp/jeanmarc123/level24`

`cmd10 : chmod 777 bandit24.sh`

`cmd11 : cp bandit24.sh/var/spool/bandit24/chmod 777 /tmp/jeanmarc123`

`cmd12 : cat level24`

`cmd12 : echo I am user bandit24 | md5sum | cut -d '' -f 1`

`cmd12 : cat /tmp.ee4ee1703b083edac9f8183e4ae70293`

`cmd12 : ssh bandit24@localhost`

**mdp : VAfGXJ1PBSsPSnvsjI8p759leLZ9GGar**
