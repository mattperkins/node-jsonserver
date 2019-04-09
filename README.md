# INSTALL 
## yarn

# RUN 
## yarn start

# DEV ENDPOINTS 
## localhost:3000

# DEPLOY 
## git clone https://github.com/mattperkins/node-jsonserver.git
## cd node-jsonserver
## npm install
## sudo npm install -g pm2
## install nginx

# UP
## DO cmdln
## NODE_ENV=production pm2 start --no-autorestart --name node-jsonserver npm -- start
## pm2 startup systemd // follow prompt

# DOWN
## pm2 unstartup systemd // stop auto startup
## ## NODE_ENV=production pm2 stop --no-autorestart --name node-jsonserver npm -- start


## API Data schema
GET POST PATCH DELETE : http://localhost:3000

Headers 
Key: Content-Type 
Value: application/json

Body: 
Raw data
{
  "username":"mikengo",
  "name":"Miken"
}