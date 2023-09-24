# LetsTalk Chat App

A realtime implementation of a chat application leveraging  [Node.js](https://nodejs.org/), [Express.js](https://expressjs.com/) and [Socket.io](https://socket.io/).





## Installation

The code for the chat app can be found at the public [GitHub](https://github.com/) repo [https://github.com/owanhunte/nodejs-chat-app](https://github.com/owanhunte/nodejs-chat-app). Either clone the repo to a local folder on your machine or download and extract the archive if you don't have [Git](https://git-scm.com/) installed.

Open a terminal window session, or the equivalent on your machine, and enter the following command to install all the Node modules needed to run the app:

```sh
npm install
```

## Run the app in development mode

After doing an `npm install` enter the following `npm run` command:

```sh
npm run dev
```

This will start the app and set it up to listen for incoming connections on port 3000. Open up your browser of choice and go to the url [http://localhost:3000/](http://localhost:3000/) to start using the app itself. The `npm run dev` command automatically runs the app using the `nodemon` script so any changes you make to the app's javascript, CSS or HTML code will automatically restart it.

## Customizing the listening port

To configure the port that the app listens on at startup, copy the file `.env.example`, located at the root of the project, to `.env` and set an appropriate value for the `PORT` environment variable listed in the file. This must be done before the app is started.
