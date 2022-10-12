# Regex Tutorial

## Summary

This Regex tutorial is used to match an email address.

/^([a-zA-Z0-9_-])+@([a-z]+[.\])+([a-z]){3,18}$/

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

/^([a-zA-Z0-9_-])+@([a-z]+[.\])+([a-z]){3,18}$/

/^([a-zA-Z0-9_-]) -- ^ anchor to match the beginning of the text.

([a-z]){3,18}$/ -- $ anchor to match the end of the text.


### Quantifiers

 A regex quantifier such as + tells the regex engine to match a certain quantity of the character, token or subexpression immediately to its left.
/^([a-zA-Z0-9_-])

### Grouping Constructs

/^([a-zA-Z0-9_-])+@([a-z]+[.\])+([a-z]){3,18}$/

() - Use parenthesis for grouping. By placing part of a regular expression inside round brackets or parentheses, you can group that part of the regular expression together. This allows you to apply a quantifier to the entire group or to restrict alternation to part of the regex.

### Bracket Expressions

/^([a-zA-Z0-9_-])+@([a-z]+[.\])+([a-z]){3,18}$/

[a-zA-Z0-9_-]

This guidelines is for matching the group. It can contain letters a-z, an underscore, hyphen, numbers 0-9 or period.

### Character Classes

/^([a-zA-Z0-9_-])+@([a-z]+[.\])+([a-z]){3,18}$/

With a “character class”, also called “character set”. Simply place the characters you want to match between square brackets.

### The OR Operator

/^([a-zA-Z0-9_-])+@([a-z]+[.\])+([a-z]){3,18}$/

You can use the | operator  to match characters or expression of either the left or right of the | operator.
However the OR operator is not applicable on the given Email code. 


### Flags
A regex flag is not used in the matching email code.

### Character Escapes

([a-z]+[.\])

To insert characters that are illegal in a string, use an escape character. An escape character is a backslash \ followed by the character you want to insert.

## Author
This tutorial was created by Jovy Ira Naraga. She is a coding student at the University of Pennsylvania and currently completing a certification in Full-Stack Development.

Contact Info:

GitHub: https://github.com/Jlnaraga

LinkedIn: https://www.linkedin.com/in/jovy-ira-naraga-9b1534238/

