# project-starter-aws
```
# project-starter-aws
Endpoint & port
Endpoint
authapi.cmfeeofluzqg.ap-southeast-1.rds.amazonaws.com
Port
5432

psql --host <endpoint> --username <username>
psql --host authapi.cmfeeofluzqg.ap-southeast-1.rds.amazonaws.com --username postgres

CREATE DATABASE authapi; CREATE DATABASE authapi_test;

git init
git add .
git commit -m "initial commit"
git remote add origin <remote repository URL>
git remote add origin https://github.com/dimasmd/auth-api.git
git push origin master

git checkout -b feature-say-hello-world
git add .
git commit -m "add say hello world test case"
git push origin feature-say-hello-world 

brew services start postgresql@15
brew link postgresql@15 --force
brew services restart postgresql
pgrep -l postgres

LC_ALL="C" /usr/local/opt/postgresql@15/bin/postgres -D /usr/local/var/postgresql@15


Mengonfigurasi EC2 Instances dan Menjalankan Auth API

ssh -i "<key>.pem" ubuntu@alamat instance EC2 lengkap ip4 public

ssh -i "....................pem" ubuntu@".....................amazonaws.com
ssh -i ""....................pem" ubuntu@"....................ipaddress

pm2 start npm --name "auth-api" -- run "start"

JIka tidak bisa konek utk Windows : baca https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AccessingInstancesLinux.html


$path = ".\auth-api-app-server.pem"
# Reset to remove explicit permissions
icacls.exe $path /reset
# Give current user explicit read-permission
icacls.exe $path /GRANT:R "$($env:USERNAME):(R)"
# Disable inheritance and remove inherited permissions
icacls.exe $path /inheritance:r


curl -fsSL https://deb.nodesource.com/setup_14.x | sudo -E bash -
sudo apt-get install -y nodejs

git add .
git commit -m "add ci action"
git push origin master



```
