# Compile to Web - Language Support

The goal of this project is to see what languages can be compiled into Web Assembly (WASM)

## Languages

| Language            | Instructions       | Compiles to LLVM   | LLVM compiles to WASM |
|---------------------|:------------------:|:------------------:|:---------------------:|
| [C](C/)             | :white_check_mark: | :white_check_mark: | :white_check_mark:    |
| [C++](C++/)         | :white_check_mark: | :white_check_mark: | :white_check_mark:    |
| [Crystal](Crystal/) | :question:         | :question:         | :question:            |
| [Go](Go/)           | :question:         | :question:         | :question:            |
| [Haskell](Haskell/) | :question:         | :question:         | :question:            |
| [Java](Java/)       | :question:         | :question:         | :question:            |
| [Julia](Julia/)     | :question:         | :question:         | :question:            |
| [Python](Python/)   | :question:         | :question:         | :question:            |
| [Rust](Rust/)       | :white_check_mark: | :white_check_mark: | :white_check_mark:    |
| [Swift](Swift/)     | :question:         | :question:         | :question:            |

### Key

| Icon               | Meaning |
|:------------------:|---------|
| :white_check_mark: | Success |
| :no_entry:         | Broken  |
| :question:         | Unknown |

## Installation

1.  Install [Vagrant](https://www.vagrantup.com/downloads.html)
2.  Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
3.  For a desired language `cd` into the folder, then run
``` sh
vagrant up
vagrant ssh
install
build
```
