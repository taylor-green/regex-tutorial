# Regex Tutorial 

Regex, short for Regular Expression, is a sequence of characters that define a search pattern. It is commonly used for string matching and string replacement. Regex is supported in many programming languages, such as JavaScript, Python, and C#. In this tutorial, we will follow an example code snippet that can be used to match an email address.

## Summary

The following code will be used throughout the tutorial to give specific examples for how the components of regex can be used. The following code can be used for matching emails. One use for this code is that it can be used to validate to make sure that an email follows the correct format.

Matching Email-

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors

The anchor is what starts and ends the regular expression. In the matching email code,

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/,

the anchors are the ^ and the $. This code specifically is saying that we are looking for something that starts with

^([a-z0-9_\.-]+)

we will define what everything inside the parentheses later in this tutorial, but what the anchor means is that if we are to find a match it has follow those initial guidelines. It also has to end with

.([a-z\.]{2,6})$.

So, it must start and end with the given parameters within the code. If it does not, then it is not a match.


### Quantifiers

### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
