# connection-draining-test
Application Gateway connection draining test code

Below steps for websocket server/client implementation was refered from https://poiemaweb.com/nodejs-socketio

1. install Socket.io

$ mkdir socketio-chat && cd socketio-chat
$ npm init --yes
$ npm install --save --save-exact socket.io express

$ cat package.json
{
  "name": "socketio-chat",
  "version": "1.0.0",
  "description": "",
  "scripts": {
    "start": "node app"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "dependencies": {
    "express": "4.17.1",
    "socket.io": "2.2.0"
  }
}
