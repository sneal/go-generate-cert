# Go Certificate Generator

Super simple x509 self signed certificate generator [from the Go project](https://golang.org/src/crypto/tls/generate_cert.go)

This exists because I got tired of creating an OpenSSL configuration file just generate a simple self signed **test** cert.

## Run from Source
```bash
go run main.go -host host.example.com
```

## Building & Running
```bash
go build -o /usr/local/bin/generate-cert .
generate-cert -host host.example.com
```
