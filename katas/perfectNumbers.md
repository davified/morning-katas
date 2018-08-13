# Perfect Numbers

The Greek mathematican Nicomachus devised a classification scheme for natural numbers, identifying each as belonging uniquely to the categories of **abundant**, **perfect**, or **deficient**. 

A perfect number equals **the sum of its positive divisors—the pairs of numbers whose product yields the target number, excluding the number itself.** Examples of perfect numbers:
- 6, because its divisors are 1, 2, 3, and 6 = 1 + 2 + 3
- 28, because 28 = 1 + 2 + 4 + 7 + 14

| classification | condition |
| -------------- | --------- |
| Perfect | Sum of factors = number |
| Abundant | Sum of factors > number |
| Deficient | Sum of factors < number |

One additional mathematics concept assists in the implementation: the aliquot sum, which is defined as the sum of the factors of a number not including the number itself, which is nominally one of the factors. Using an aliquot sum rather than the proper sum of the factors makes the comparisons for perfection easier: `aliquotSum === number`, rather than `sum - number == number`.

Task:
- Create a function `isPerfect(num)`, that returns true if `num` is perfect, and false if otherwise.
- Create a function `isAbundant(num)`
- Create a function `isDeficient(num)`

Tips:
- Try to solve this using the functional programming paradigm (i.e. avoid mutable state; use higher order functions such as `filter`)
- To think in the functional programming paradigm, think about desired results, not steps
- Try things out using pen and paper first, before writing any code.
- Create smaller helper functions if necessary
- TDD this!