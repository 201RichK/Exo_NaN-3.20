## advancedsortwordarr

### Instructions

Écrire une fonction `AdvancedSortWordArr` qui trie un tableau de `string`, basé sur la fonction `f` passée en paramètre.

### Fonction attendue

```go
func AdvancedSortWordArr(array []string, f func(a, b string) int) {

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

	result := []string{"a", "A", "1", "b", "B", "2", "c", "C", "3"}
	AdvancedSortWordArr(result, Compare)

	fmt.Println(result)
}
```

Et son résultat :

```console
student@ubuntu:~/[[ROOT]]/test$ go build
student@ubuntu:~/[[ROOT]]/test$ ./test
[1 2 3 A B C a b c]
student@ubuntu:~/[[ROOT]]/test$
```
