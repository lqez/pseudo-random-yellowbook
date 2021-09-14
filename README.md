# pseudo-random-yellowbook
A yellow-book of pseudo-random number generation of modern programming languages.

List ordering follows [TIOBE Index](https://www.tiobe.com/tiobe-index/).


| Language | Module | 1 <= integer <= 10 | 0 <= float < 100 |
|----------|--------|--------------------|------------------|
| [C](#c) | [`stdlib.h`](https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/stdlib.h.html) | [`rand() % 10 + 1`](https://www.gnu.org/software/libc/manual/html_node/ISO-Random.html) | `rand() / (float)RAND_MAX * 100` |
| [Python](#python) | [`random`](https://docs.python.org/3/library/random.html) | [`random.randint(1, 10)`](https://docs.python.org/3/library/random.html#random.randint) | [`random.random() * 100`](https://docs.python.org/3/library/random.html#random.random) |
| [Java](#java) | [`java.util.Random`](https://docs.oracle.com/en/java/javase/16/docs/api/java.base/java/util/Random.html) | [`new Random().nextInt(10) + 1`](https://docs.oracle.com/en/java/javase/16/docs/api/java.base/java/util/Random.html#nextInt()) | [`new Random().nextFloat() * 100`](https://docs.oracle.com/en/java/javase/16/docs/api/java.base/java/util/Random.html#nextFloat()) |
| [C++](#C++) | `<random>` | (mt19937...) | |
| C# |
| Visual Basic |
| [JavaScript](#javascript) | [`Math`](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Math) | [`Math.floor(Math.random() * 10) + 1`](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Math/random) | `Math.random() * 100` |
| Assembly |
| [PHP](#php) | [Math](https://www.php.net/manual/en/book.math.php) (core) | [`mt_rand(1, 10)`](https://www.php.net/manual/function.rand.php) | [`mt_rand() / (float)(mt_getrandmax() + 1) * 100`](https://www.php.net/manual/en/function.mt-getrandmax.php) |
| SQL |
| [Ruby](#ruby) | [Random](https://ruby-doc.org/core-3.0.2/Random.html) | [`rand 10+1`](https://ruby-doc.org/core-2.6/Random.html#method-i-rand) | [`rand * 100`](https://ruby-doc.org/core-2.6/Random.html#method-i-rand) |
| Go |
| Swift |
| MATLAB |
| Fortran |
| R |
| Perl |
| Delphi |
| Rust |
| [Scala](#scala) | [`scala.util.Random`](https://www.scala-lang.org/api/3.0.2/scala/util/Random.html) | [`Random.nextInt(10) + 1`](https://www.scala-lang.org/api/3.0.2/scala/util/Random.html#nextInt-fffffbe0) | [`Random.between(1f, 100f)`](https://www.scala-lang.org/api/3.0.2/scala/util/Random.html#between-44b) |


## C

(detailed description goes here...)

## Python

## Java

## C++

## C#

## Visual Basic

## JavaScript

## PHP

## Ruby

## Scala
