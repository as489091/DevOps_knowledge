# DevOps_knowledge
cd # change directory 
ls -lrt# shows long list
ls -lrth# shows long list with time
pwd#present working dir
whoami
ssh username@hostname
df
free
du
systemctl start
systemctl pause
systemctl stop
netstat 
netstat -tunpl
ss -tunpl
vi
touch
cat
rm
cp
ps 
ps -ef | grep java
kill -9 pid
git add
git commit
git push
git clone repourl
zip -r ankita.zip directory 
zip ankita.zip filename
unzip ankita.zip
unzip -q ankita.zip (no detail will come )
tar -czvf ankita.tar.gz directory
c - create z-zip v-verbose f-file
tar xzvp ankita.taz.gz
du -sh
du -sh /tmp
du -sh /tmp/*
du -sh /tmp/* | sort -rh | head -n10
du -sh /tmp/* | sort | head -n10
cp sourcefilepath destination_file
cp -r source_directory destination_dir
mv sourcefile destinationfile
mv -r sourcefile destination 
mv -r sourcedirectoryparth dedtinationdir
scp filename 
username@hostname:destination_directory_path

scp -r source_dir username@hostname:destination_directory_path

sed -i ‘s/oldword/newword/g’ filename
ls -lrth | awk ‘{print $7}’
awk ‘{print $1}’ filename
ps -ef ‘{print $1, $4}’ file
find
locate
less
more
head
tail
nano
vim
gedit
wc
strings
chmod
chgrp
umask
isattr
chattr
uniq
comm
diff
uname
nproc
yum install nginx
yum remove -y nginx
yum history list
yum list nginx*
yum history undo 5
sleep 10
uptime
reboot
grep ankita filename
grep -i ankita filename
grep ‘^ankita’ -i filename
grep ‘^[^#].*yes$’ filename #do not print line starting with #,print line which end with yes
scp file username@host:/tmp
scp -r directory username@host/tmp
ssh -keygen (generate pub and pri 🔑)
ssh -copy-id username@host (it will copy server a public key and paste it to sever b of .ssh of aurhorized.ssh file)

cat ankita 2>file_name  #will route error to ankita it will not show in log
cat ankita 1> file_name #it will show output in file_name it will not show the error
cat ankita >file_name 2>&1 #it will send error and output in same file



