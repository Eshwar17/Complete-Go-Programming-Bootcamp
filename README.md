# GO
     -Next Gen Language
     
Golang is a **compiled** language.
    Go tool can run file directly, without VM
    Executables are different for OS

## What and where we can use Golang?

System apps to web apps - **Cloud**
Already in production

## Object Oriented?

Yes and No😅 (Because it doesn't have classes but it contains struts)
What you see on the screen is the code

## First Program in Golang

main.go

```go
package main

import "fmt"

func main() {
	fmt.Println("Hello Go!!!");
}
```

### Running your Go program
###### run go main.go
Above command is used to compile and run the program

## Lexer in Golang and Types

In programming, a lexer is a program or function that breaks down input code into a sequence of tokens, which are meaningful units of code. Go, a popular programming language provides a built-in package called “text/scanner” for implementing lexers.
For example if you forgot to put a semicolon at the place where it is required, lexer comes into the play and adds the semicolon.

### Types in Golang
Types are case insensitive, sometimes types even define whether you are going to make it public or private.
Variable type should be known in advance in Golang.
Everything is a Type.

##### String
##### Bool
##### Integer - uint8 - uint64 - int8 - int64 - uintptr
##### Floating - float32 - float64
##### Complex
##### Array
##### Slices
##### Maps
##### Structs
##### Pointers

Almost everything - functions, channels, mutex...
