# renkv.koevorden
Homebridge gives requesterror
please help!




[2018-12-22 00:03:47] [HomeWizard] Running : homebridge-homewizard 0.0.59
Unhandled rejection RequestError: Error: connect ENETUNREACH 92.168.192.62:80
    at new RequestError (/home/pi/.nvm/versions/node/v8.9.1/lib/node_modules/homebridge-homewizard/node_modules/request-promise/lib/errors.js:11:15)
    at Request.RP$callback [as _callback] (/home/pi/.nvm/versions/node/v8.9.1/lib/node_modules/homebridge-homewizard/node_modules/request-promise/lib/rp.js:60:32)
    at self.callback (/home/pi/.nvm/versions/node/v8.9.1/lib/node_modules/homebridge-homewizard/node_modules/request/request.js:185:22)
    at emitOne (events.js:116:13)
    at Request.emit (events.js:211:7)
    at Request.onRequestError (/home/pi/.nvm/versions/node/v8.9.1/lib/node_modules/homebridge-homewizard/node_modules/request/request.js:881:8)
    at emitOne (events.js:116:13)
    at ClientRequest.emit (events.js:211:7)
    at Socket.socketErrorListener (_http_client.js:387:9)
    at emitOne (events.js:116:13)
    at Socket.emit (events.js:211:7)
    at emitErrorNT (internal/streams/destroy.js:64:8)
    at _combinedTickCallback (internal/process/next_tick.js:138:11)
    at process._tickCallback (internal/process/next_tick.js:180:9)
[2018-12-22 00:08:47] [HomeWizard] Refresh...

