# pseudo-random-yellowbook
A yellow-book of pseudo-random number generation of modern programming languages.

List ordering follows [TIOBE Index](https://www.tiobe.com/tiobe-index/).


| Language | Module | 1 <= integer <= 10 | 0 <= float < 100 |
|----------|--------|--------------------|------------------|
| [C](#c) | [`stdlib.h`](https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/stdlib.h.html) | [`rand() % 10 + 1`](https://www.gnu.org/software/libc/manual/html_node/ISO-Random.html) | `rand() / (float)RAND_MAX * 100` |
| [Python](#python) | [`random`](https://docs.python.org/3/library/random.html) | [`random.randint(1, 10)`](https://docs.python.org/3/library/random.html#random.randint) | [`random.random() * 100`](https://docs.python.org/3/library/random.html#random.random) |
| [Java](#Java) | [`java.util.Random`](https://docs.oracle.com/en/java/javase/16/docs/api/java.base/java/util/Random.html) | [`new Random().nextInt(10) + 1`](https://docs.oracle.com/en/java/javase/16/docs/api/java.base/java/util/Random.html#nextInt()) | [`new Random().nextFloat() * 100`](https://docs.oracle.com/en/java/javase/16/docs/api/java.base/java/util/Random.html#nextFloat()) |
| [C++](#C++) |
| C# |
| Visual Basic |
| JavaScript |
| Assembly |
| PHP |
| SQL |
| Ruby |
| Go |
| Swift |
| MATLAB |
| Fortran |
| R |
| Perl |
| Delphi |
| Rust |

## C

(detailed description goes here...)

## Python

## Java

## C++

## C#

## Visual Basic

## JavaScript

