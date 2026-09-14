# DevOps_knowledge
cd
ls -lrt
ls -lrth
pwd
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



