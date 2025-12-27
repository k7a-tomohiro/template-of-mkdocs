# Snippet

https://squidfunk.github.io/mkdocs-material/setup/extensions/python-markdown-extensions/#snippets

### block style

```go
package main

import "fmt"

func main() {
    fmt.Println("hello world")
}
```

### import from file

```go
--8<-- "menu1/snippet/main.go"
```

### import from file with line range

```go
--8<-- "menu1/snippet/main.go:5:7"
```
