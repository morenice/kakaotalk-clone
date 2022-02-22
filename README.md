# Simple Chat

Using Spring Boot and WebSocket(STOMP) with Java 17

```
Client            Client
   |                |
   | websoket       |  websocket
+---------------------------------+
|           Web Server            |
+---------------------------------+
               |
               | pub/sub
+---------------------------------+
|           Redis                 |
+---------------------------------+
```
