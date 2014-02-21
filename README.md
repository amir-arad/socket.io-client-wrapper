socket.io-client-wrapper
========================

a socket.io client socket wrapper that can be created before actually connecting the socket.

By separating the lifecycle of the socket object from the underlying socket connection, it is possible to pass the wrapper as if it was a live socket for services to register listeners, and only later connect a live socket underneath.

Handy for controlling socket connection time and yet supplying the socket as a global service in environments like Angular.


## Designed for use with

* [angular-socket-io](https://github.com/btford/angular-socket-io)

* [ngSocket](https://github.com/jeffbcross/ngSocket)
