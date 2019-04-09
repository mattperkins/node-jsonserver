# INSTALL 
## npm install 

# RUN 
## npm run start 
## npm run json:server

# ENDPOINTS 
## localhost:3000

# DEPLOY 
## git clone https://github.com/mattperkins/node-jsonserver.git
## cd node-jsonserver
## npm install
## sudo npm install -g pm2
## pm2 start npm
## startup systemd // follow prompt

## pm2 unstartup systemd // stop auto startup

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