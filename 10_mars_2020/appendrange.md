## appendrange

### Instructions

Écrire une fonction qui prend un `int` minimum et un `int` maximum comme paramètres. Cette fonction retourne une slice d'`int` avec toutes les valeurs comprises entre le minimum et le maximum.

Le minimum est inclus, le maximum est exclu.

Si le minimum est supérieur ou égal au maximum, une slice `nil` est retournée.

`make` n'est pas autorisé pour cet exercice.

### Fonction attendue

```go
func AppendRange(min, max int) []int {

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
	fmt.Println(AppendRange(5, 10))
	fmt.Println(AppendRange(10, 5))
}
```

Et son résultat :

```console
student@ubuntu:~/[[ROOT]]/test$ go build
student@ubuntu:~/[[ROOT]]/test$ ./test
[5 6 7 8 9]
[]
student@ubuntu:~/[[ROOT]]/test$
```
