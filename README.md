# go-lab
A laboratory for learning Go

## Study Materials
- [Test-Driven Development By Example by Kent Beck](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnx0ZXN0MTIzNHNpbTQ2NXxneDpiYTJmYWIwYTAyOGJiZmQ)
- [The Go Programming Language by Donovan & Kernighan](https://beyondkmp.com/books/golang/The.Go.Programming.Language.pdf)
- [Head First Design Patterns by Eric Freemen & Elisabeth Robson](https://github.com/ajitpal/BookBank/blob/master/%5BO%60Reilly.%20Head%20First%5D%20-%20Head%20First%20Design%20Patterns%20-%20%5BFreeman%5D.pdf)

## Environment
This project is built using the nix flakes, A feature present in the [nix package manager]().
To configure your local development environment perform the following steps:
[Install nix to your local machine](https://nixos.org/download.html):
```
sh <(curl -L https://nixos.org/nix/install) --daemon
```
Once installation is complete you can clone the repository and enter the environment:
```
nix develop
```
To build the application from source:
```
nix build
```
The binary can be found in `result/bin/go-lab`

## Infrastructure

## Contributing

