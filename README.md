# CHATIFY 
- Designed and developed a feature-rich Chat Application that
enables users to interact with each other in real-time.
- This application allows seamless communication and fosters a
collaborative environment for users to exchange messages, share
emojis, and engage in conversations effortlessly.
- Developed a real-time chat application leveraging Socket.io for
seamless bidirectional communication between clients and the
server.

## Installation Guide

### Requirements
- [Nodejs](https://nodejs.org/en/download)
- [Mongodb](https://www.mongodb.com/docs/manual/administration/install-community/)
 
 - npm install react-router
 - and also install react-scripts
 - Both should be installed and make sure mongodb is running.

```shell
git clone https://github.com/koolkishan/chat-app-react-nodejs
cd chat-app-react-nodejs
```
Now rename env files from .env.example to .env
```shell
cd public
mv .env.example .env
cd ..
cd server
mv .env.example .env
cd ..
```

Now install the dependencies
```shell
cd server
yarn
cd ..
cd public
yarn
```
We are almost done, Now just start the development server.

For Frontend.
```shell
cd public
yarn start
```
For Backend.

Open another terminal in folder, Also make sure mongodb is running in background.
```shell
cd server
yarn start
```

Done! Now open localhost:3000 in your browser.
