# Split strings Kata 

Taken from Codewars to try to practice TDD

## How I will go about this
- install rspec gem
- create a test file
- create a program file
- check all tests pass and behaviour matches

## What is the kata asking?

Complete the solution so that it splits the string into pairs of two characters. If the string contains an odd number of characters then it should replace the missing second character of the final pair with an underscore ('_').

Examples:

* 'abc' =>  ['ab', 'c_']
* 'abcdef' => ['ab', 'cd', 'ef']

## Initial ideas:

- accept input
- check for non-string input
- check length of string
- split strings into 2 chars
- add to a list
- check the last string for length
- add underscore if needed
- return list
