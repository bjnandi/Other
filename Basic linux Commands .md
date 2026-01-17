1) ls
2) ls -a
3) ll
4) pwd
5) cd
6) touch, nano, vi
7) cat
8) clear
9) rm 
10) mkdir
11) wget
12) curl -O 
13) cp 
14) ".." back dir
15) man
16) who
17) which 
18) whoami
19) date
20) cal
21) history
22) mv
23) rmdir
24) gedit
25) exit
26) sudo apt-get install tzdata
27) sudo ufw app list
28) hostname -I
29) find . -name my-file
30) wc index.html (Word count [line, Word, file_size])
31) useradd test
32) passwd test
33) hostname
34) cat /etc/passwd | grep -i bjnandi
35) cat /etc/passwd | grep -i bj*
36) chown
37) chmode
38) df -h
39) lsblk

40) nc -v 103.228.120.126 443

/ root
~ tilde

df -hT
du -h -d 1 /home
sudo du -sh /var/lib/* | sort -hr | head -10
du -sh ./*
sudo find /var/lib/docker/containers/ -name "*.log" -exec du -h {} + | sort -hr | head -10

zip cloud-function.zip requirements.txt main.py
curl ifconfig.me
lsblk
mkfs -t ext4 /dev/xvdf
mount /dev/xvdf /test/    umount /dev/xvdf /test/
sudo nautilus  (root file see on ubuntu)
cp -r test text
cp test.txt test1.txt
cp text11 /home/bjnandi/Desktop/
passwd Biswajit
rm -r test
rm -rf cv
shtudown -h now

nc -zv localhost 3306

COPY .  /var/www/html/

 ssh -i LightsailDefaultKey-ap-south-1.pem ubuntu@35.154.21.241
 sudo !!
 
Disk 
-------------
df -H
lsblk 
sudo mount /dev/xvdf  test
sudo mkfs -t ext4 /dev/xvdf
sudo umount /dev/xvdf

scp -i ec2key.pem username@ec2ip:/remote/path/to/file /local/path/to/file

Remort login
--------------------------------
sudo apt install openssh-server
sudo service ssh status
ssh-keygen
cd /home/bjnandi/.ssh
ssh-copy-id  bjnandi@192.168.0.4
ssh bjnandi@192.168.0.4
exit

ProxyCommand ssh
alias k='sudo kubectl'
alias c='clear'

docker context use default
echo -n "admin123" | base64
echo -n "YWRtaW4xMjM=" | base64 --decode

Get the public key from the new key pair:
```
ssh-keygen -y -f new-key.pem
```

