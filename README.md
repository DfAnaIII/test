# Hello World 
(dans pleins de langage de programmation) 

## En Assembly
```
section .data
    msg db "Hello world!", 0ah

section .text
    global _start

_start:
    mov rax, 1
    mov rdi, 1
    mov rsi, msg
    mov rdx, 13
    syscall
    mov rax, 60
    mov rdi, 0
    syscall
```

## En Basic 
```
PRINT "Hello, World!"
```

## En C
```
#include <printf.h>

int main () {
    printf("Hello World !");
}
```

## En C++
```
#include <printf.h>

int main () {
    printf("Hello World !");
}
```

## En C#
```
Console.WriteLine("Hello, World!");
```

## En D
```
import std.stdio;
void main()
{
    writeln("Hello world!");
}
```

## En Python 
```
print("Hello World !")
```

## En R
```
print("Hello World !")
```

## En HTML
```
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Hello World</title>
</head>
<body>
    <p>Hello world</p>
</body>
</html>
```

## En Java
```
public Class Hello
{
public static void main(String[] args)
{
  System.out.println("Hello World !");
}
}
```
## En PHP
```
<?php

echo "Hello world!\n";
```
## En GO
```
package main

import "fmt"

func main() {
    fmt.Println("Hello world!")
}
```

## En Ruby
```
puts "Hello world!"
```

## En TypeScript
```
const message:string = "Hello world!";
console.log(message);
```

## En Fortran
```
program main
    print *, "Hello world!"
end program main
```

## En Lua
```
print 'hello world!'
```

## En Erlang
```
main(_) -> io:format("Hello world!").
```

## En Clojure
```
(println "Hello world!")
```

## En Perl
```
print 'Hello world !';
```

## En Kotlin
```
fun main() {
    println("Hello world!")
}
```

## En Swift
```
print("Hello world!")
```

## En Rust
```
fn main() {
    println!("Hello world!")
}
```

## En NodeJs
```
console.log("Hello, World!");
```
## En JavaScript
```
console.log("Hello, World!");
```
## En Groovy
```
println "Hello, World!"
```
## En Jshell
```
System.out.println("Hello, World!");
```
## En Haskell
```
main = putStrLn "Hello, World!"
```
## En TCL
```
puts "Hello, World!"
```
## En Ada
```
with Ada.Text_IO; use Ada.Text_IO;
procedure Hello is
begin
		Put_Line ("Hello, World!");
end Hello;
```
## En CommonLisp
```
(format t "Hello, World!")
```
## En Elixir
```
IO.puts "Hello, World!"
```
## En Racket
```
#lang racket/base
(display "Hello, World!")
```
## En Ocaml
```
print_string "Hello, World!"
```
## En VB
```
Public Module Program
	Public Sub Main(args() As string)
		Console.WriteLine("Hello, World!")
	End Sub
End Module
```
## En Bash
```
echo "Hello, World!"
```
