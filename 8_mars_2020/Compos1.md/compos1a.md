## compo1a

### Instructions

Écrire une fonction `compo1a` qui affiche un rectangle **valide** de largeur `x` et de hauteur `y`.

Cette fonction doit dessiner les rectangles comme sur les examples.

### Fonction attendue

```go
func compo1a(x,y int) {

}
```

### Utilisation

Voici d'éventuels programmes pour tester votre fonction :

Programme #1

```go
package main

import (
	
)

func main() {
	compo1a(5,3)
}
```

Et son résultat :

```console
student@ubuntu:~/[[ROOT]]/test$ go build
student@ubuntu:~/[[ROOT]]/test$ ./test
o---o
|   |
o---o
student@ubuntu:~/[[ROOT]]/test$
```

Programme #2

```go
package main

import (
	
)

func main() {
	compo1a(5,1)
}
```

Et son résultat :

```console
student@ubuntu:~/[[ROOT]]/test$ go build
student@ubuntu:~/[[ROOT]]/test$ ./test
o---o
student@ubuntu:~/[[ROOT]]/test$
```

Programme #3

```go
package main

import (
	
)

func main() {
	compo1a(1,1)
}
```

Et son résultat :

```console
student@ubuntu:~/[[ROOT]]/test$ go build
student@ubuntu:~/[[ROOT]]/test$ ./test
o
student@ubuntu:~/[[ROOT]]/test$
```

Programme #4

```go
package main

import (
	
)

func main() {
	compo1a(1,5)
}
```

Et son résultat :

```console
student@ubuntu:~/[[ROOT]]/test$ go build
student@ubuntu:~/[[ROOT]]/test$ ./test
o
|
|
|
o
student@ubuntu:~/[[ROOT]]/test$
```
