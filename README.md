# Golang socket based chat application
`go version 1.14.2`\
`Socket type: TCP`\
`Server listening port :3333`



## How to run
Need to run client and server code separately.

Server: 
> go run server.go

client:
> go run client.go

## Code Editor
`Visual Studio Code`\
`Version: 1.45.1`




## Application Options

Maximum 10 clients are allowed to connect at a time.


client has below options:

* help - lists all commands.
* list - lists all chat rooms.
* create {room name} - creates a chat room named {room name}.
* join {room name} - joins a chat room named {room name}.
* leave - leaves the current chat room.
* name {your name} - changes your name to {your name} into the chat room.
* quit - quits the program.


so using above options client can create and join into the chat room.

```diff
! WARNING - You have to allow the listening port :3333
```
