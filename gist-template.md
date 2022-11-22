

# Title (replace with your title)
Matching a url
/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/


Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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
Anchors are used to define the current location in a string. For example, the anchor charactor ^ signifies the tart of a string while $ signigies the end. The search - ^abc - would match anystring which began with the characters abc, while the search - abc$ - will match a string which ends with the characters abc.
### Quantifiers
Quantifiers serve to select a variable number of characters or sets of characters. The quantifiers which appear in our example are * (zero times or more), ? (zero times or once), and {x,y} (atleast x times, atmost y times).
Examples: A*b would match: b (or the b in) mb (or) Ab (or) AAAb
          A+b would match: Ab (or) AAAb, BUT WOULD NOT MATCH: b (or) mb
          A{3,5}b would match: AAAb (or) AAAAb (or) AAAAAb
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