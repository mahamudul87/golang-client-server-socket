# golang-client-server-socket
Golang socket programming starter project for chat applicaiton
`go version 1.14.2`
`Socket type: TCP`
`Server listening port :3333`



## How to run
Need to run client and server code seperately.

Server: 
> go run server.go

client:
> go run client.go

## Code Editor
> Visual Studio Code
> Version: 1.45.1




## Application Options


when client started then automatically connect to server to the server port :3333
Maximum 10 clients can connect at a time.


after joining client has below options:

* help - lists all commands.
* list - lists all chat rooms.
* create ist - creates a chat room named ist.
* join ist - joins a chat room named ist.
* leave - leaves the current chat room.
* name ist - changes your name to ist.
* quit - quits the program.


so using above options client can create and join into the chat room.

```diff
! WARNING - You have to allow the listening port :3333
```
