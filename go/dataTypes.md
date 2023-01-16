# Data Types in Golang

| Types | Examples |
|:-------|:--------|
| primitive| int, float, bool, string |
| composit | struct, array, slice, map, channel
| interface | Desribes behavior of a type |

A structured type has no value has a value of **nil**
```go
var var1 type1
```

It is possible to give aliases to data types as shown below: 
```go
type IZ int
```
To declare an integer you can use
```go
var a IZ = 5
```

to declare multiple aliases you can use a factored form:
```go
type (
    IZ int
    FZ float32
    STR string
)

```
