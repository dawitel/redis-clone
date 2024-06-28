## Redis clone

A toy Redis clone that's capable of handlingbasic commands like 
`PING`, `SET` and `GET`. Along the way we'll learn about
event loops, the Redis protocol and more.

**Note**: If you think this is impressive wait until you here the original redis 
was implemented using C.

# Getting started

The entry point for this Redis implementation is in `app/server.go`:

```sh
git clone https://github.com/dawitel/redis-clone # any msg
```
```sh
cd redis-clone
```

1. Ensure you have `go (1.19)` installed locally
2. Run this command to run the Redis server, which is implemented in `app/server.go`.
   ```sh
   ./spawn_redis_server.sh
   ```
