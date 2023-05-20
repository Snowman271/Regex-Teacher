# Title (replace with your title)

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
Regular expressions are powerful tools for pattern matching and manipulating text. 
### Anchors
Anchors are used to match specific positions within the text. The two most used being ^ and $.
### Quantifiers
Quantifiers allow you to specify the number of occurrences or repetitions of a character or group in a regex. Some commonly used quantifiers are +, ?, * and {n}.
### OR Operator
The OR operator allows you to match either one expression or another. In regex, the OR operator is represented by the | (pipe) symbol. For example, the regex apple|orange will match either 'apple' or 'orange'.
### Character Classes
Character classes allow you to match a specific set of characters. They are enclosed in square brackets [ ]. such as [abc] or [0-9].
### Flags
Flags are optional parameters that can modify the behavior of a regex pattern. The most commonly used flags are g, i and m.
### Grouping and Capturing
Parentheses () are used for grouping and capturing subexpressions within a regex. Grouping allows you to apply quantifiers or modifiers to multiple characters or expressions. Capturing allows you to extract the matched content for further processing.
### Bracket Expressions
Bracket expressions, denoted by [ ], are used to match any single character from a specified set or range. They are similar to character classes but provide more flexibility.
### Greedy and Lazy Match
By default, regex quantifiers are greedy, meaning they match as much as possible. However, you can make them lazy by appending a ? (question mark) after the quantifier. Lazy matching will match as little as possible.
### Boundaries
Boundaries are used to match positions that are not directly preceded or followed by specific characters. Here are some commonly used boundaries. Such as /b, /B, and # matching thte words to different boundries.
### Back-references
Back-references allow you to refer to previously captured groups within the same regex pattern. They are denoted by \ followed by a digit representing the group number.
### Look-ahead and Look-behind
Look-ahead and look-behind assertions are used to match a pattern only if it is followed or preceded by another pattern, without including the matched content in the result. Look-ahead assertions are denoted by (?=...), while look-behind assertions are denoted by (?<=...) or (?<!...).
## Author
GitHub: [Snowman271](https://github.com/Snowman271)

Email: [tbenzmiller@cs.com](mailto:tbenzmiller@cs.com) 