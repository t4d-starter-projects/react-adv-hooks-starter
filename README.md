# React Advanced Hooks Starter

This is the starter project for the React Advanced Hooks course in the Mastering React Series provided by [WintellectNOW](https://www.wintellectnow.com/).

## Setup

To start the Node.js application, change into the `server-app` folder, and run the following commands.

```bash
npm install

npm start
```

To run the React application, open a new terminal window, change into the `client-app` folder, and run the following commands.

```bash
npm install

npm start
```

To view the React application, open a web browser and browse to `http://localhost:5000`. The Node.js server app will reverse proxy to the React application running on port 3000. Open the web application multiple browsers to see the chatting.

> Note: Do not load `http://localhost:3000` directly into the web browser. The chat application will not work because it cannot access the Socket.io web socket chat server on port 5000.
