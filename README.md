# Redis

Installation

$ wget http://download.redis.io/releases/redis-3.2.8.tar.gz

$ tar xzf redis-3.2.8.tar.gz

$ cd redis-3.2.8

$ make

The binaries that are now compiled are available in the src directory. Run Redis with:

$ src/redis-server

You can interact with Redis using the built-in client:

$ src/redis-cli

redis> set foo bar

OK
redis> get foo

"bar"
