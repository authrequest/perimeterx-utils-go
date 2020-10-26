# Perimeterx Helper Functions

## Install
```bash
$ go get github.com/incizzle/perimeterx-utils-go
```
```go
import pxutils "github.com/incizzle/perimeterx-utils-go"
```
## Compile to .so file

Run Command
```go
go build -o pxutils.so -buildmode=c-shared pxutils.go
```

## Usage

Create PC Variable
```go
pxutils.CreatePC(jsonstring, tag) // Create PC Variable pass in jsonstring payload and uuid:tag:ftag
```

Obfuscate String
```go
pxutils.ObfuscateString(text, factor) // Simple Function to Obfuscate string using a factor
```

By: iNcizzle#1337  
Decoder Website: https://px.incizzle.dev/  
Enjoy 💜  