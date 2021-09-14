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
| Ruby |
| Go |
| Swift |
| [MATLAB](#matlab) | intrinsic | [`randi(imax)`](https://www.mathworks.com/help/matlab/ref/randi.html) | [`rand`](https://www.mathworks.com/help/matlab/ref/rand.html) | 
| [Fortran](#fortran) | intrinsic | Convert from float random number | [`CALL RANDOM_NUMBER(r)`](https://gcc.gnu.org/onlinedocs/gfortran/RANDOM_005fNUMBER.html#RANDOM_005fNUMBER) | 
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

## MATLAB

## Fortran
* Declare output variable first and pass it to `RANDOM_NUMBER`.
  ```fortran
    program test_random_number
        REAL :: r(5,5)
        CALL RANDOM_NUMBER(r)
    end program
  ```

## Scala
