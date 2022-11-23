

# Title (replace with your title)
Matching a url
/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/


Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Matching a URL](#matching-a-url)

## Regex Components

### Anchors
Anchors are used to define the current location in a string. For example, the anchor charactor ^ signifies the tart of a string while $ signigies the end. The search - ^abc - would match anystring which began with the characters abc, while the search - abc$ - will match a string which ends with the characters abc. <br />
### Quantifiers
Quantifiers serve to select a variable number of characters or sets of characters. The quantifiers which appear in our example are * (zero times or more), ? (zero times or once), and {x,y} (atleast x times, atmost y times). <br />
Examples: A*b would match: b (or the b in) mb (or) Ab (or) AAAb <br />
          A+b would match: Ab (or) AAAb, BUT WOULD NOT MATCH: b (or) mb <br />
          A{3,5}b would match: AAAb (or) AAAAb (or) AAAAAb <br />

### Character Classes
Character Classes are used to define a set of characters such that any one of the specified characters will provide a match. They are denoted with square brackets, [], and contain the allowed characters within. Including a carat [^ ] at the start of the class turns it into the inverse, or any character not specified within the set. <br />
Examples: [abc]a would match: aa (or) ba (or) ca <br />
          [\dA-C]b would match: 2b (or) Bb (or) any one digit 0-9 or any one of the capital letters A,B,C followed by b <br />
          [^\da-d] would match: any character that is neither a digit 0-9 nor a,b,c,d <br />
### Grouping and Capturing
Grouping refers to placing one or more characters within parentheses in order to gain more control over how the expression is evaluated. This is commonly seen when using quantifiers in order to specify what the quantifier applies to. Capturing allows us to reference groups later in the expression. The first group used in an expression can be referenced again with - \1 - and the second with - \2. For example, the expression - 
(ab)c(de)f\1\2 - is identicle to - abcdefabde. <br />
Examples: (abc)+ would match: abcabc <br />
          a(bc)+ would match: abcbc <br />
          d(e)fin\1 would match: define <br />

### Greedy and Lazy Match


### Matching a URL


## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)