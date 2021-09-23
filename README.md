# Go Certificate Generator

Super simple x509 self signed certificate generator [from the Go project](https://golang.org/src/crypto/tls/generate_cert.go)

## Run from Source
```bash
go run main.go -host host.example.com
```

## Building & Running
```bash
go build -o /usr/local/bin/generate-cert .
generate-cert -host host.example.com
```
