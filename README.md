
# Socket.IO Chat

A simple chat demo for socket.io

Fork of https://github.com/Automattic/socket.io/tree/master/examples/chat with add multiroom support.

## How to use

```
$ clone from github
$ cd dir
$ npm install
$ node .
```

And point your browser to `http://localhost:3000`. Optionally, specify
a port by supplying the `PORT` env variable.

## Rooms support

```
http://localhost:3000/#channel=room_name
```

if #channel is not set, room set as location.href

## Features

- Multiple users can join a chat rooms by each entering a unique username
on website load.
- Users can type chat messages to the chat room.
- A notification is sent to all users when a user joins or leaves. User view message if message.channel equal own room.
