# java-daytimeserver
TCP and multithreaded UDP daytime server in Java

The TCP version was an assignment from Network Programming (LA01) class

## Usage
### TCP Server
```
$ javac TcpDaytimeServer.java
$ java TcpDaytimeServer
Starts TCP daytime server on the specified port.
Usage: TcpDaytimeServer [<port>]
```
### TCP Client
```
$ javac TcpDaytimeTestClient.java
$ java TcpDaytimeTestClient
Usage: TcpDaytimeTestClient [<host>] [<port>]
```
![screenshot](screenshot01.png?raw=true "TCP Daytime Server")

### Multithreaded UDP Server
```
$ javac MultithreadedUdpDaytimeServer.java
$ java MultithreadedUdpDaytimeServer
Starts UDP daytime server on the specified port.
Usage: MultithreadedUdpDaytimeServer [<port>]
```
### UDP Client
```
$ javac UdpDaytimeTestClient.java
$ java UdpDaytimeTestClient
Usage: UdpDaytimeTestClient [<hostname>] [<port>]
```
![screenshot](screenshot02.png?raw=true "Multithreaded UDP Daytime Server")

### Used Compiler
```
$ javac -version
javac 1.8.0_121
```
