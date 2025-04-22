# fs-permutation-gnerator

Build a Permutation Generator
In this lab, you will build a permutation generator that will take a string and return all possible permutations of the characters in the string. For example, the possible permutations of the string cat are cat, cta, act, atc, tac, and tca.

Objective: Fulfill the user stories below and get all the tests to pass to complete the lab.

User Stories:

1.  You should create a function named permuteString.
2.  The permuteString function should take three parameters- a string, a prefix value and an empty array for storing and returning the results. The prefix value would accumulate characters to form a permutation.
3.  Inside the function, you should check if the length of the passed string is 0. If it is, push the current prefix to the results and return the results.
4.  Iterate over each character in the input string and for each iteration, remove the current character from the string and call the permuteString function recursively with updated arguments to build the remaining permutations.
5.  You should return the final results array.
6.  You should ensure that the permutations are unique by removing duplicates.