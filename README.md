# go-generate-detect
Hacky way to detect if a user has run `go generate`.

# Usage
```
$ go build
# github.com/Minnozz/go-generate-detect
./gendetect.go:4:7: undefined: _YouNeedToRunGoGenerate
$ go generate
$ go build
$ # Success!
```
