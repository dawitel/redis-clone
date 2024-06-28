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
cd redis-clone


1. Ensure you have `go (1.19)` installed locally
2. Run `./spawn_redis_server.sh` to run your Redis server, which is implemented
   in `app/server.go`.
