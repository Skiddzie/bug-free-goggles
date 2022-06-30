# Title (replace with your title)

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.
We're going to be looking at the regular expression ^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$ this regex scans the text and picks out any valid email address
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
Anchors are the "^" and "$" commands
^ determines the start of the text you're looking for, and $ marks the end.
For example ^regex will look for text that starts with the word regex, and regex$ will look for text that ends with regex

### Quantifiers
Quantifiers are the "*", "?", "+", and "{}" and they determine how many times in a row our token can be matched

"*" matches from none to an unlimited amount of times
"?" matches from none up to one time
"+" matches from once to an unlimited amount of times, meaning "+" will make that token necessary
"{}" lets you determine what the minimum and maximum amount of times the token can appear

### OR Operator
the or operators is "|" and "[]"
"regex(1|2)" will capture anything that says regex1 or regex2 this could also be written out as regex[12]

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
