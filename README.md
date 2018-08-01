# LiveChat REST API proxy with Express
This projects implements a simple proxy for LiveChat REST API

It makes use of [Express.js](http://expressjs.com/), a minimal and flexible Node.js framework that includes a myriad of HTTP utility methods for quickly creating robust APIs. We also use the [Body Parser](https://github.com/expressjs/body-parser) package, which is Node.js middleware that allows us to process any POST requests we receive.

### With curl
curl "https://livechat-rest-api.glitch.me/agents" -H "Authorization: Bearer <your_access_token>" -H X-API-Version:2

Keep this project open and view 'Logs' to see the console output.