### Building command

```bash
CC=arm-linux-gnueabi-gcc GOOS=linux GOARCH=arm GOARM=7 CGO_ENABLED=1 go build -ldflags "-linkmode external -extldflags '-static'" .
```

