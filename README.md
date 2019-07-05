# connection-draining-test
Application Gateway connection draining test code

Below steps for websocket server/client implementation was refered from https://poiemaweb.com/nodejs-socketio

## 1. Clone this repository

    $ git clone https://github.com/hyundonk/connection-draining-test.git
    $ cd connection-draining-test

## 2. check websocket port in app.js file. This example uses port 8100.

## 3. install Socket.io
    $ npm init --yes
    $ npm install --save --save-exact socket.io express

## 4. Run app.js
    $ node app.js

