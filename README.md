# Alpaca_Websockets_Trading_Bot

```
npm install -g wscat
```

```
wscat -c wss://alpaca.socket.polygon.io/stocks
```

```
{"action":"auth","params":"*******"}
```

```
{"action":"subscribe","params":"T.AAPL"}
```

Identify Requirements:

- Need to get data from websockets
- Need to act on said data with Alpaca API

Plan & Design:
Systematic approach will be taken with a top-down implementation of the functions.

Build/Code:

- [ ] Build to be done concurrently with the Code of choice being Python.
- [ ] Get WebSocket Data.
- [ ] Interpet said Data.

Test/Debug/Document:
Testing will be done by comapring and asserting if the expected values come out.

Deploy:
Once application passes testing it can be deployed.
As of 11/17/2021 it has been deployed.
