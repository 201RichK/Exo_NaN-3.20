## isprime

### Instructions

Écrire une fonction qui renvoie `true` si l'`int` passé en paramètre est un nombre premier. Autrement elle renvoie `false`.

La fonction devra être optimisée pour éviter les time-outs avec le testeur.

### Fonction attendue

```go
func IsPrime(nb int) bool {

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
	fmt.Println(IsPrime(5))
	fmt.Println(IsPrime(4))
}
```

Et son résultat :

```console
student@ubuntu:~/[[ROOT]]/test$ go build
student@ubuntu:~/[[ROOT]]/test$ ./test
true
false
student@ubuntu:~/[[ROOT]]/test$
```
