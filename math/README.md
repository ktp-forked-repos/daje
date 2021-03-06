## math
Common math functions and snippets.

## Current contents

* digit-operations.hpp
  * __sum_of_digits__ : calculates the sum of the digits of a number 
  
* eratosthenes-sieve.h
  * __sift__ : implementation of the Sieve of Eatosthenes taken from "From Mathematics to Generic Programming"
 
* factorial.h
  * __fact_recursive__ : classical recursive implementation of factorial
  * __fact_iterative__ : classical iterative implementation of factorial 
  * __fact_bounded__ : 64bit unsigned long long bounded version of factorial (lookup table)
  * __fact_generate__ : generates first N factorials by using only standard algorithms

* fibonacci.hpp
  * __nth_fibo__ : returns the nth Fibonacci number by using Binet's formula
  * __is_fibo__ : returns true if an int is a Fibonacci number, false otherwise
  * __recursive_fibo__ : returns the nth Fibonacci number by using naive recursion - O(2^n)
  * __dp_fibo__ : returns the nth Fibonacci number by using Dynamic Programming - O(n)
  * __std_fibo__ : returns the nth Fibonacci number by using 'adjacent_difference' - O(n)
  * __matrix_fibo__ : returns the nth Fibonacci number by using Matrix Exponentiation method - O(log(n))

* integer-pow.h
  * __ipow__ : integer power implemented in terms of exponentiation by squaring

* isprime.h
  * __is_prime__ : checks if an int is prime

* perfect-squares.h
  * __is_perfect_square__ : returns if an int number is a square of another (and its root, eventually)
  * __perfect_squares_in_range__ : returns the number of perfect squares in a range [a, b]
  * __perfect_squares_in_range__ : calls a function for each perfect square in a range [a, b] 

* prime-factors.h
  * __prime_factors_of__ : returns all the prime factors of a number
  * __sum_of_prime_factors__ : calculates the sum of all the prime factors of a number

* repdigit.h
  * __repdigit__ : returns the number composed of repeated instances of the same digit in a positional number system. (e.g. 111, 33333)
  * __repdigit_base10__ : returns the number composed of repeated instances of the same digit in base 10 (e.g. 111, 33333)
  
* roman_numbers.h
  * __to_roman_ifcascade__ : converts an int into the corresponding Roman number, by using the classic "if-cascade" approach
  * __to_roman_lower_bound__ : converts an int into the corresponding Roman number, by using std::map + lower_bound
  
* stats_warmup.h
  * __mean__ : calculates the average of a vector of ints
  * __weighted_mean__ : calculates the weighted mean of a vector of ints
  * __median__ : calculates the mediant of a vector of ints
  * __mode__ : returns the most occuring element of a vector of ints (the smallest in case of ambiguity)
  * __std_dev__ : calculates the standard deviation of a vector of ints
  * __confidence_bounds__ : calculates the lower and upper boundary of the 95% Confidence Interval for the mean

## This is NOT a library
.hpp files in this folder are not intended to be included somewhere. They contain snippets, easy to copy-and-paste into the challenge editor.

__However__ .h files can be used as header-only.
