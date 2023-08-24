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


brew services start postgresql@15
brew link postgresql@15 --force
brew services restart postgresql
pgrep -l postgres

LC_ALL="C" /usr/local/opt/postgresql@15/bin/postgres -D /usr/local/var/postgresql@15
```
