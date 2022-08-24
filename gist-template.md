# Title (replace with your title)

We are going to  explain a specifics of regex so that we can understand the search pattern 
## Summary

for example , we will explain today is: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]<\/\1>|\{2,6})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)


## Regex Components

### Anchors
It contains The anchors used to contain ^ to start, and $ to finish.



### Quantifiers
{2,6} -forces the input of characters between two & six characters long.

[a-z0-9_\.-] - includes case sensitive characters from a-z, numbers from 0-9 an underscore, periods and hyphens.

"+" means 1 or more of the preceding token.
"*" means 0 or more of the preceding token.
"?" means 0 or 1 of the preceding token, effectively making it optional.
"?" means the preceding quantifier lazy, causing it to match as few characters as possible. By default, quantifiers are greedy, and will match as many characters as possible.

[\s\S] A character set that can be used to match any character, including line breaks, without the dotall flag. An alternative is [^] carrot in brackets, but it is not supported in all browsers.

### Grouping Constructs

[a-z0-9_\.-] - has characters from a-z, numbers from 0-9 an underscore, periods and hyphens.

 [\da-z\.-] - has all digits, case sensitive characters from a-z, periods and hyphens

 [a-z\.] - has haracters from a-z and periods.


  <\/\1> -  is a numeric Referance

 {2,6} -forces the input of characters between two & six characters long.

### Bracket Expressions

A bracket expression enclosed in square brackets is a regular expression that matches a single character, or collating element. If the initial character is a circumflex ^, then this bracket expression is complemented.

### Character Classes

In our example our character classes are confined within brackets []. for example here, 
[a-z0-9_\.-] contains characters from a-z, numbers from 0-9 an underscore, periods and hyphens.
### The OR Operator

or operator indicates that it could either of the components that we are separating with the |


## Author
Dongyu Guo
new developer in learning
