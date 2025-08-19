# Go

## New Project

Create a blank directory
```
mkdir hello
cd hello
```

Enable dependency tracking through a go.mod file
```
$ go mod init example/hello
go: creating new go.mod: module example/hello
```

## Hello World

```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```
