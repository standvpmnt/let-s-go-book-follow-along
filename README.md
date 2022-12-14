`go mod verify` to check the downloaded packages have the same
checksums as stored in go.sum file.

`go mod download`

`go get -u <package>` to upgrade to a specific version

To cleanup run, `go mod tidy -v` or `go get <package>@none`

For chaining middlewares, look at [package](github.com/justinas/alice@v1)
