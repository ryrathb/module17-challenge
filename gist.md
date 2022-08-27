# Email Regex 

In this gist file, I will be analyzing all parts of the regular expression (regex) used to identify and validate email addresses.
This regex is extremely important because email addresses must be valid for them to send and recieve mail, so if a software application doesn't have the ability to do that, it could potentially mess with a lot of data flow. Emails are used in both professional and personal settings, meaning there is no telling what a faulty email application could do to our interconnected world. This is why we must analyze email regexes.

## Summary

This gist file will show how a regular expression can validate and email address input. Below is an example of using a regex to validate onces email:

/^([a-z0-9_.-]+)@([\da-z.-]+).([a-z.]{2,6})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors

Anchors are what defines the start and end of a string being examined. The "^" symbol is an anchor that represents the start of a string, and the "$" symbol is an anchor that represents the end of a string. Anchors also examine the characters placed in between brackets, so [a-z0-9_.-], [\da-z.-], and [a-z.] are what the anchors analyze. 

### Quantifiers



### Grouping Constructs

### Bracket Expressions

The brackets defined in the email regex are using ranges of characters that are predetermined, or they define specific ones that are valid. In the email regex, the first bracket ([a-z0-9_.-]) says that any letter from a to z is valid, any number from 0 to 9 is valid, and an underscore, a period, and hyphen are also valid.

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
