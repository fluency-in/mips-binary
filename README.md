# MIPS Assembly: Binary

Write a program that will convert a binary number, represented as a string (e.g. '101010'), to its decimal equivalent using first principles

Implement binary to decimal conversion. Given a binary input
string, your program should produce a decimal output. The
program should handle invalid inputs.

## Note
- Implement the conversion yourself.
  Do not use something else to perform the conversion for you.

## About Binary (Base-2)
Decimal is a base-10 system.

A number 23 in base 10 notation can be understood
as a linear combination of powers of 10:

- The rightmost digit gets multiplied by 10^0 = 1
- The next number gets multiplied by 10^1 = 10
- ...
- The *n*th number gets multiplied by 10^*(n-1)*.
- All these values are summed.

So: `23 => 2*10^1 + 3*10^0 => 2*10 + 3*1 = 23 base 10`

Binary is similar, but uses powers of 2 rather than powers of 10.

So: `101 => 1*2^2 + 0*2^1 + 1*2^0 => 1*4 + 0*2 + 1*1 => 4 + 1 => 5 base 10`.

For these problems, we use the popular MIPS simulator [MARS](http://courses.missouristate.edu/KenVollmar/mars/). Download the MARS jar archive from the MARS website and place it somewhere easily accessible. Also install the Java SDK if you do not have it already.

To run the tests, assemble and run the test runner file for a given exercise either via the MARS simulator GUI, or on the command line. To run on the command line,
specify first the runner file and then your implementation, like so:

    java -jar /path/to/mars.jar nc runner.mips impl.mips

To run in the GUI, `include` your implementation at the bottom of "runner.mips"
by uncommenting the final line.

The test runner will either complete with a “success” message or terminate on a failing test with a message specifying the input for which that test failed.

## Source

All of Computer Science [http://www.wolframalpha.com/input/?i=binary&a=*C.binary-_*MathWorld-](http://www.wolframalpha.com/input/?i=binary&a=*C.binary-_*MathWorld-)

This exercise is from the [MIPS Assembly][mips] track on [Exercism][exercism]

[exercism]: http://exercism.io
[mips]: http://exercism.io/languages/mips



