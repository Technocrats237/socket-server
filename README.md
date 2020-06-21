# Socket Server

This repository contains the websocket application. This server updates the charts in realtime. The browser client essential publishes (and listens) to events to and from this application. It is a simple server built in NodeJS using ExpressJS. 

## Dependencies
All the requirements are spelled-out in the package.js file.

## Run
1. Install node dependencies

`$ npm install (or yarn)`

2. Run the application

`$ node socket.js`

## Possible issue
You may need to update the ip address of the dashboard/templates/pages/index.html page in the scripts section to point to this server.
