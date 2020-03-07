## compare

### Instructions

Écrire une fonction qui se comporte comme la fonction [`Compare`](https://golang.org/pkg/strings/#Compare).

### Fonction attendue

```go
func Compare(a, b string) int {

}
```

### Utilisation

Voici un éventuel programme pour tester votre fonction :

```go
package main

import (
	"fmt"
)

func main() {
	fmt.Println(Compare("Hello!", "Hello!"))
	fmt.Println(Compare("Salut!", "lut!"))
	fmt.Println(Compare("Ola!", "Ol"))
}
```

Et son résultat :

```console
student@ubuntu:~/[[ROOT]]/test$ go build
student@ubuntu:~/[[ROOT]]/test$ ./test
0
-1
1
student@ubuntu:~/[[ROOT]]/test$
```
