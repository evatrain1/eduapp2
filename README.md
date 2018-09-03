

README.md

Eduapp2 is used to educate technical people.

Installation:

create ubuntu account [if needed]

sudo useradd -m -s /bin/bash -G sudo ubuntu
sudo passwd ubuntu

login

[X-Windows variant below]
ssh -AY ubuntu@localhost
or
ssh ubuntu@some-aws-ip

clone the repo

git clone https://github.com/evatrain1/eduapp2

# create package.json
npm init

# install http server (locally) and creates index.html
npm install http-server

# add call server from start.bash
~/eduapp2/node_modules/.bin/http-server

call start.bash
cd eduapp1
./start.bash

That should bring up a server

curl localhost:8080/index.html


