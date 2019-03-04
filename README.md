## Webbie-Talkie

Web Application which allows multiple users to communicate live through a video call. 
# Features

- [ ] Full duplex visual & vocal communication
- [ ] Text Chat Service
- [ ] Screen sharing possible
- [ ] Provision to record the call
- [ ] Provision to mute video/audio
- [ ] Uses UDP protocol
- [ ] No handshake needed to start call



Add your OpenTok credentials to the `options` hash in  `app.js`:
```javascript
const options = {
credentials: {
  apiKey: "YOUR_API_KEY",
  sessionId: "YOUR_SESSION_ID",
  token: "YOUR_TOKEN"
},
...
```

To run:
```javascript
$ npm install
$ npm run build
$ node server.js
```

