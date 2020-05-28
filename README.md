# Redis Flush

A script to do redis command "FLUSHALL" to multiple redis servers via telnet client

## How To Use

- Make `redisflush.exp` executeable by `chmod +x redisflush.exp`
- Do FLUSHALL to single Redis server 

```
./redisflush.exp <host> <port>
```

- Do FLUSHALL to multiple Redis server

```
./redisflush.exp "<host> <host> <host>" <port>
```

- Do FLUSHALL to multiple Redis server with password 

```
./redisflush.exp "<host> <host> <host>" <port> <password>
```

Note: 

- `<host>`: remote redis server ip/hostname
- `<port>`: remote redis server port
- `<password>`: remote redis server password

