## example of Server-Sent Events 

The server sends events to the client in a unidirectional manner.


### Client Code on browser
```
    let sse = new EventSource("http://localhost:8080/stream");

    sse.onmessage = console.log
```


Resource: https://developer.mozilla.org/en-US/docs/Web/API/EventSource
