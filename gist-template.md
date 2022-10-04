# Regex Tutorial

## Summary

A regex, which is short for regular expression, is a sequence of characters that defines a specific search pattern. When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input.

For example, the following regular expression can be used to verify that user input is a valid email address:

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

There are three compontents that go into an email validation.

Component 1: ([a-z0-9_\.-]+)
In this component the "/^" indicates that what comes next is how the emails username is allowed to be entered. Inside the parenthesis, the brackets encapsulate that any letters from a-z, any numbers from 0-9, and any underscores, slashes, periods, or dashes can be entered as valid characters.

Component 2: ([\da-z\.-]+)
This component comes after an @ symbol which is what seperates the first component from the second. All this means is when you've finished the username type "@" which dictates that it is now time to enter the email domain. It allows letters, numbers, and dashes.

Component 3: ([a-z\.]{2,6})
This component comes after a period and involves any letters.

### Anchors

^ and $
^ signifies the beginning parameters^([a-z0-9_\.-]+) of a string and $ signifies the parameters([a-z\.]{2,6})$ of end of a string.

### Quantifiers

* + ? and {}
The + in our example of an email validation is to signify that the string will be followed by one or more strings. The {2,6} signifies that the string [a-z\.] can include between 2-6 characters.

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
