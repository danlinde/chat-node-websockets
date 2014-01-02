A Chat application with Node.js and Socket.io based on the [NetTuts tutorial](http://net.tutsplus.com/tutorials/javascript-ajax/using-node-js-and-websockets-to-build-a-chat-service/).

I used the *Jade* templating engine and *Express* web application framework for Node.

Socket.io is very similar to Websockets but was used here because it is compatible with more browsers.

__Installation:__
- Install dependencies:
	npm install express jade socket.io
- To start the chat service, run the following command:
	node server.js
- Then navigate your browser to `localhost:3000`