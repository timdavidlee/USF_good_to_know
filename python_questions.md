### Python Practice Questions


#### Example 1

```
# Find duplicates in a string with a function:
# ----------------------------------------------------
# dups("programming")
# g : 2
# r : 2
# m : 2
```

#### Example 2

```
# count vowels and consonants in a string:
# ----------------------------------------------------
# countTypes('java')
# this has 2 vowels and 2 consonants
```
#### Example 3

```
# count number of occurrences in a string
# ----------------------------------------------------
# occurrences('java'), also return and note the maximum
# a : 2
# v : 1
# j : 1
# the maximum is a @ 2 chars
```
#### Example 4

```
# give all permutations of a given string, 'ab', 'abc','abcd'
# ----------------------------------------------------
# 'ab' --> ['ab','ba']
# 'abc' --> ['abc','acb','bac','bca','cab','cba']
```
#### Example 5

```
# Reverse all the words in a sentence:
# ----------------------------------------------------
# phrase = 'python is best programming language'
# ---> '"language programming best is python'
```
#### Example 6

```
# Check to see if a word is a palindrome
# ----------------------------------------------------
# phrases = ['radar','madam','java']
# ---- > True, True, False
```
#### Example 7

```
# Remove duplicates from a string:
# ----------------------------------------------------
# 'bananas' -- > 'bans'
```
#### Example 8

```
# given the following phrases, identify which phrases are anagrams
# ----------------------------------------------------------------------
# anagrams = ['catba', 'batca', 'atcab', 'dog','god']

phrases = ['catba', 'batca','tree', 'atcab', 'dog','god','mussel']
```

#### Example 9

```
# create a function to check if the sentence is a pangram
# ----------------------------------------------------------------------
#)

# a = "We promptly judged antique ivory buckles for the next prize"
# "panagram"

# b = "We promptly judged antique ivory buckles for the prize"
# "not pangram"

#'

#'

#'

f = 'Pack my box with five dozen liquor bottles'
```
#### Example 10

```
# 10 - longest string given bookends
# -------------------------------------------------------------------------

#
# strDist("catcowcat", "cat") → 9
# strDist("catcowcat", "cow") → 3
# strDist("cccatcowcatxx", "cat") → 9
```
#### Example 11

```
# 12 - calculate nth fibonacci number
# -------------------------------------------------------------------------
# fib(0) # => 0
# fib(1) # => 1
# fib(2) # => 1
# fib(3) # => 2
# fib(4) # => 3
```
#### Example 12

```
#13 - return sum, excluding duplicates:
#---------------------------------------

lone_sum(1, 2, 3) → 6
lone_sum(3, 2, 3) → 2
lone_sum(3, 3, 3) → 0
```
#### Example 13

```
#14 - is there 22 in the list?
#---------------------------------------
has22([1, 2, 2]) → True
has22([1, 2, 1, 2]) → False
has22([2, 1, 2]) → False
```

#### Example 14

```
#15 - print staircase size n:
#---------------------------------------
staircase(4)
   #
  ##
 ###
####
```
#### Example 15

```
#16 - transform a string into counts
#------------------------------------

lettercount(‘aaabbccccddeeffff’)
A3b2c4d2e2f4
```
#### Example 16

```
#16 - transform a string into counts
#------------------------------------

lettercount(‘aaabbccccddeeffff’)
A3b2c4d2e2f4
```
#### Example 17

```
#18 - Count how many times an phrase shows up in a given text?
#---------------------------------------------------------------
ABCDCDC
CDC
Answer: 2

BLKSJFLKSJJFLOIJFJFL
JFL
Answer: 3

```
#### Example 18

```
# 
#----------------------------------------------
[2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 
47, 53, 59, 61, 67, 71, 73, 79, 83, 89, 97]
```

#### Example 19
```
# Return a list recursively
#---------------------------------------------------------------
```

#### Example 20
```
# merge overlapping ranges 
#---------------------------------------------------------------
#[(1, 5), (2, 4), (3, 6)] --->  [(1, 6)]
#[(1, 3), (2, 4), (5, 6)] --->  [(1, 4), (5, 6)]
```

#### Example 21
```
# Given a list of numbers, determine if they are a result of squares:
# ---------------------------------------------------------------
test([12,25,16,3]) → False, True, True, False
```

#### Example 22
```
# Text wrap, given a text string and number, split the string and wrap the text:
#---------------------------------------------------------------
ABCDEFGHIJKLIMNOQRSTUVWXYZ
4
ABCD
EFGH
IJKL
IMNO
QRST
UVWX
YZ
```

#### Example 23

```
# Whats the second largest number, and the second smallest number of a list? 
#-----------------------------------------------------------
2 3 6 6 5 7 8 9 10 11 13
```

#### Example 24
```
# Tell me the % of the list that are 
#-----------------------------------------------------------
# Positive
# Negative
# Zero

-4 3 -9 0 4 1
#500000
#333333
#166667
```

#### Example 25
```
#30 Give the maximum and the minimum values of the sum of 4 values:
#-----------------------------------------------------------
A = [1,2,3,4,5]
Answer = 10, 14

Bonus: for more than 6 inputs
B = [1,2,3,4,5,6]
Answer = 10, 18

```

#### Example 26
```
# Returning names with proper grammar
#----------------------------------------------------------------
Given: an array containing hashes of names
Return: a string formatted as a list of names separated by commas 
except for the last two names, which should be separated by an 
#
Example:

namelist([ {'name': 'Bart'}, {'name': 'Lisa'}, {'name': 'Maggie'} ])
# returns 'Bart, Lisa & Maggie'

namelist([ {'name': 'Bart'}, {'name': 'Lisa'} ])
# returns 'Bart & Lisa'

namelist([ {'name': 'Bart'} ])
# returns 'Bart'

namelist([])
# returns ''
```

#### Example 27
```
# Sum of lowest integers
#----------------------------------------------------------------
Create a function that returns the sum of the two lowest positive 
# No floats or empty 
# For example, when an array is passed like 
#
#
```

#### Example 28
```
# Sum of lowest integers
#----------------------------------------------------------------
Create a function that returns the sum of the two lowest positive 
# No floats or empty 
# For example, when an array is passed like 
#
#
```

#### Example 29
```
#
#----------------------------------------------------------------
Find the missing letter
Write a method that takes an array of consecutive (increasing) 
#
# And it will be always exactly one 
#
#
Example:
['a','b','c','d','f'] -> 'e'
['O','Q','R','S'] -> 'P'
```

#### Example 30
```
# 
#----------------------------------------------------------------
Complete the solution so that it splits the string into pairs of 
# If the string contains an odd number of characters 
then it should replace the missing second character of the final 
#
Examples:
solution('abc') # should return ['ab', 'c_']
solution('abcdef') # should return ['ab', 'cd', 'ef']
```