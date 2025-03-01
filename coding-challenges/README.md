# List of Coding Challenges

## Week 3

### Day 1: Login page using Bootstrap

Create a login page using bootstrap which looks like the below screenshot

![bootstrap login page](images/bootstrap-login-page.png)

### Day 2: Looping through an array

Given the following array: 
```
var players = [
    { name: "Roger Federer", rank: 1 },
    { name: "Rafel Nadal", rank: 2 },
    { name: "Nalbandian", rank: 12 },
    { name: "Andy Murray", rank: 14 },
    { name: "Andy Roddick", rank: 4 },
    { name: "Pete Sampras", rank: 3 },
    { name: "Rod Laver", rank: 190 },
    { name: "Andre Agassi", rank: 11 },
    { name: "Novak Djokovic", rank: 5 },
    { name: "Arthur Ashe", rank: 8 },
];
```
Write a `for` loop that only prints players with rank less than or equal to 10.

### Day 3: Find initials of a name

Write a JavaScript function which accepts a name and prints the initials.

Input: `Mahendra Singh Dhoni`
Output: `MSD`

Input: `Shah Rukh Khan`
Output: `SRK`

### Day 5: Compare two arrays

Write a JavaScript function that compares two arrays and prints whether they are equal or not.

**Note:** Two arrays are considered equal if both arrays contain the same number of elements, and all corresponding pairs of elements in the two arrays are equal. In other words, two arrays are equal if they contain the same elements in the same order.

----------
## Week 4

### Day 1: Star pattern

Write a JavaScript function that produces a star pattern likes this.

```
*
**
***
****
*****
****
***
**
*
```

**Hint:** Nested `for` loop.

### Day 2: Hamming distance

Write a program to find the Hamming distance between two strings.

**Note:**  Hamming distance between two strings of equal length is the number of positions at which the corresponding characters are different. In more technical terms, it is a measure of the minimum number of changes required to turn one string into another.

The Hamming distance between:

1. "karolin" and "kathrin" is 3.
2. "karolin" and "kerstin" is 3.
3. 1011101 and 1001001 is 2.
4. 2173896 and 2233796 is 3.

### Day 4: Ajax

First, load [cities.json](data/cities.json) using Ajax (either vanilla JavaScript or jQuery is fine).

Then write a Javascript function that takes a letter and finds all the cities that starts with that letter.

----------
## Week 5

### Day 1: Ajax 2

Use data from the file [cities.json](data/cities.json) to
create a function which takes a state as input and loops through the data to output the cities that belong to that state.

### Day 2: Formatting time

Write a function that takes a number input in seconds and returns the number of hours, minutes and seconds as output. Separate the number of hours, minutes and seconds with colons `:`.

```
Input: 126
Output: "0:2:6"

Input: 45
Output: "0:0:45"

Input: 3700
Output: "1:1:40"
```

### Day 4: Express CRUD

Create an Express application that has routes for creating, adding, updating and deleting a person's contact information - 

```
{
    name: "Name",
    phone: "phone-no"
}
```

### Day 5: URL parameter extraction

Write a function to take a url as a string input and extract all url parameters from it. Return an object contaning these key-value pairs.

```
Input: "http://localhost:3000/add?num1=5&num2=3"
Output: { "num1": 5, "num2": 3 }

Input: "http://localhost:3000/search"
Output: "Missing URL parameters!"
```

----------
## Week 6

### Day 2: Anagram

Given 2 strings, find whether one is an anagram of the other.

**Note:** Two strings are anagrams if they are written using the same exact letters. Each letter should have the same count in both strings. e.g. 'binary' and 'brainy'

### Day 4: Palindrome

Write a function to check whether a given string is a palindrome.

**Note:** A palindrome is a word that is the same when read backwards. e.g. `kayak`, `madam`, `malayalam`

### Day 5: Character increment

Write a function to take a string as input and change each letter to the next letter in the alphabet.

```
Input: "hello"
Output: "ifmmp"

Input: "zeta"
Output: "afub"
```

----------
## Week 7

### Day 2: Factorial

Write  a function to take a number input and output its factorial.

**Note:** The factorial of any number is the product of all positive integers less than or equal to it. Factorial is mathematically denoted by the symbol `!`.

```
4! = 4 * 3 * 2 * 1 = 24

6! = 6 * 5 * 4 * 3 * 2 * 1 = 720
```

### Day 3: Pangram

Given a string, find all characters that are missing from the string, i.e., the characters that can make the string a pangram. Print the output in alphabetic order, case-insensitive.

**Note:** A pangram is a sentence containing every letter in the English alphabet.

```
Input : The quick brown fox jumps
Output : adglvyz
```

### Day 5: Decimal to binary

Write a function to input a decimal (base-10) number and return its binary equivalent (base-2). The image below illustrates the method to get a binary equivalent `10001` of a decimal number `17`.

![conversion](images/decimal-binary.png)

----------
## Week 8

### Day 1: Fibonacci

Write a function to take an input n and print first n terms of the Fibonacci series.

**Note:** The Fibonacci Sequence is the series of numbers - `0, 1, 1, 2, 3, 5, 8, 13, 21, 34, ...` Any term of the Fibonacci series is found by adding up the two numbers before it.

### Day 2: Triangle pattern

Given a number N, the task is to print the following pattern:
```
Input: 10
Output:                    
          * 
         * * 
        * * * 
       * * * * 
      * * * * * 
     * * * * * * 
    * * * * * * * 
   * * * * * * * * 
  * * * * * * * * * 
 * * * * * * * * * * 

Input: 5
Output:
     * 
    * * 
   * * * 
  * * * * 
 * * * * * 
```

### Day 3: Array min-max

Create two Javascript functions - `largest` and `smallest`.

Both of them takes an array of numbers as an input.

`largest` should return the largest number in the array.
`smallest` should return the smallest number in the array.

Feel free to use any technique - either algo based or any of the JS' builtin feature to solve this problem.

### Day 4: Check for power of 2

Create a Javascript function that checks if a number is a power of two.

For a number that is power of two, you should return `true`. For others, you should return `false`.
Examples: `isPowerOfTwo(16)` => `true`, `isPowerOfTwo(9) => `false`

*Hint:* You can easily check if a number is power of two by - repeatedly dividing it by two and checking for any remainder - until the number becomes 1 or less. If at any point the remainder is not 0, the number is not a power of two.


# Week 12

## Day 5

Write a Javascript function that takes two arrays as an input and calculate the number of elements that belong to both of the arrays.

For example, given two arrays - `let a =[5,2,8,9,4]` and let b = `[3,2,9,5]`` The function commonElements(a, b) should return `[]2, 5, 9]` because 2, 5 and 9 are common to both of the arrays.

# Week 13

## Day 5

Consider the following rule for creating a number sequence -
If the `previous number is even, the next number is n / 2`.
If the `previous number is odd, the next number is 3 * n + 1`
If we use the above rule and start the sequence from 13, we will have the `following sequence 13, 40, 20, 10, 5, 16, 8, 4, 2, 1`
This is how it was created -
We started from 13, which is an odd number.
So the next number is calculated as 3 * n + 1, that is, 3 * 13 + 1 = 40
40 is even, so the next number is n / 2, that is 40 / 2 = 20
20 is even, so the next number is n / 2, that is 20 / 2 = 10
10 is even, so the next number is n / 2, that is 10 / 2 = 5
5 is odd, so the next number is 3 * n + 1, that is 3 * 5 + 1 = 16
and so on until 1... 

# Week 14 

## Day 1

Write a Javascript function that checks if a string contains all unique characters. Return true if all the characters are unique or false if it contains duplicate characters.

For example, ansal contains two a and hence the function should return false for it. arkesh contains no repeated character and hence the function should return true.

You can treat small case and big case of same characters as different characters.

Hint: Use javascript object for storage 