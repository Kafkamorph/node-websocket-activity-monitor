node-websocket-activity-monitor
===============================

A new copy of https://github.com/makoto/node-websocket-activity-monitor. Edit to use socket.io.

## Prerequisite

* node.js
* iostat. you can get it from sysstat package.

## How to use

    node server/activity-monitor.js
    open localhost:3000/iostat-client.html # in websocket supported browser

## How to change to other sysstat command
    change both server and client side. Change the messaging passing - format() function. Change the client side webSocket.on('message') function to reflect the change.
## How to support NON Websocket supported browsers
    >42< (under construction)

## Speical Thanks
Thank you Sir Makoto for this living demo!
