## Goal

A server that runs in a single thread can only serve one request at a time, it can create a problem by simulating some slow requests. This can be fixed by making it handle multiple requests at once (mutithreaded)


## Test

Run: 

```shell
cargo run
```

Check out these at the same time in two different tabs in the browser:

- http://127.0.0.1:7878/sleep
- http://127.0.0.1:7878/