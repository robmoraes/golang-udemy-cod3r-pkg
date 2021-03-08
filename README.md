# golang-udemy-cod3r-pkg
Prática de obtenção de pacotes direto do repositório

## Como usar

### Download do pacote

```bash
$ go get -u github.com/robmoraes/golang-udemy-cod3r-pkg
```

### Uso

```go
package main

import (
	"fmt"

	"github.com/robmoraes/golang-udemy-cod3r-pkg/abc"

	"github.com/robmoraes/golang-udemy-cod3r-pkg/area"
)

func main() {
	ac := area.Circ(4.0)
	ar := area.Rect(5.4, 2.9)
	fmt.Println(ac, ar)
	abc.Epa()
}
```
