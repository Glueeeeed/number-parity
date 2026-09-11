# number-parity
A simple program written in an Glue language that checks whether numbers in the range from 1 to 100 are even, without using the modulo operator.


Since the language does not have a built-in modulo operator `%` the algorithm uses a property of integer division:

1. It divides the current number by `2` (`half = counter / 2`).
2. It multiplies the result back by `2` (`half * 2`).
3. If the result of the multiplication is equal to the original number, the number is **even** (its square is calculated).
4. Otherwise, the number is **odd** (its product with `2.5` is calculated).
