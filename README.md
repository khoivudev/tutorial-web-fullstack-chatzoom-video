# Plan of Action

- Initialize NodeJs Project !
- Initialize our first view!
- Create a room id !
- Add the ability to view our own video !
- Add ability to allow others to stream their video
- Add styling
- Add the ability to create messages
- Add mute button
- Add stop video button

# Technology

- Jquerry
- Bootstrap
- NodeJs
- Express Server
- Socket IO
- PeerJs
- uuid()

## Development

- Set peer PORT(script.js) == PORT(server.js)

```js
npm install
npm start
```

## Deployment

- Set peer PORT in script.js = 443
- Set peer PORT in server.js = process.env.
  Add Procfile:

```js
web: node server.js
```
