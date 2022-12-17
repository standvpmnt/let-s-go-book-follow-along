`go mod verify` to check the downloaded packages have the same
checksums as stored in go.sum file.

`go mod download`

`go get -u <package>` to upgrade to a specific version

To cleanup run, `go mod tidy -v` or `go get <package>@none`

For chaining middlewares, look at [package](github.com/justinas/alice@v1)

To generate a certificate use the `generate_cert.go` tool available in the standard library

```
go run /usr/local/go/src/crypto/tls/generate_cert.go --rsa-bit
s=2048 --host=localhost
```
