Imports in go are very useful. The syntax looks like this
```go
import "fmt"
```

to import multiple packages you can do this
``` go
import(
    "fmt"
    "os"
)
```

The scope for packages to expose their code outside of the package is follows the following rule enforced by the compiler:

When the identifier starts with a capital letter, like, Group1, then the object is visible outside of the package it is declared in.