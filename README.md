# RegularExpressionHub

# Tools
* [Reg Exr](https://regexr.com/)    
* [Regex 101](https://regex101.com/)      
* [Regex Pal](https://www.regexpal.com/)

# Repositories    
* LearnRegularExpressions        
   * [Learn Regular Expressions (Regex) - Crash Course for Beginners - YouTube - freeCodeCamp - Beau Carnes](https://www.youtube.com/watch?v=ZfQFUJhPqMM)
* Lookaround     
   * [Regular expressions: lookaround assertions by example - Blog - Deep JavaScript](https://exploringjs.com/deep-js/ch_regexp-lookaround-assertions.html)
# References  
* [w3schools](https://www.w3schools.com/jsref/jsref_obj_regexp.asp)   

* [Everything You Need to Know About Regular Expressions In JavaScript - Lucas F. Costa](https://lucasfcosta.com/2016/12/25/Regular-Expressions-in-JavaScript-Part-Two.html)
* [Session 2: Regular Expressions - Programming with Text - YouTube - The Coding Train - Sam Lavigne](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6YEypLuls7iidwHMdCM6o2w)

# Cheat Sheet Reference
* [QuickRef.ME](https://quickref.me/regex)

# Cheat Sheet      
## Modifiers
* d Flag - Expression match should contain the start and end string
* g Flag - Expression should be tested against all possible matches in a string
* i Flag - Do a case-insensitive search
* m Flag - Multi-line search
* s Flag - Allows . to match newline characters
* u Flag - Treat a pattern as a sequence of unicode code points
* y Flag  - Perform a "sticky" search that matches starting at the current position in the target string

## Groups and Ranges

* OR Group - (x|y) Matches either "x" or "y"
* Specify Range - [abcd] is the same as [a-d]. They match the "b" in "brisket", and the "c" in "chop".
* Negated Range - [^a-c] They initially match "on" in "bacon" and "hop" in "chop" with global flag set
* Capturing Group - Matches x and remembers the match. (go)+ means go, gogo, gogogo and so on
* Capturing Group \nth - Where "n" is a positive integer. \1 refers to the first capturing group in the regular expression. \2 will refer to the second capturing group and \n will refer to an nth capturing group   

## Meta characters   
 * . - Find a single character, except newline or line terminator   
 * \w - Find a word character. A word character is a character a-z, A-Z, 0-9, including _ (underscore)
 * \W - Find a non-word character
 * \d - Find a digit
 * \D - Find a non-digit character
 * \s - Find a whitespace character
 * \S - Find a non-whitespace character
 * \b - Find a match at the beginning/end of a word
 * \B - Find a match, but not at the beginning/end of a word
 * \0 - Find a NULL character
 * \n - Find a new line character
 * \f - Find a form feed character
 * \r - Find a carriage return character
 * \t - Find a tab character
 * \v - Find a vertical tab character
 * \xxx - Find the character specified by an octal number xxx
 * \xdd - Find the character specified by a hexadecimal number dd
 * \udddd - Find the Unicode character specified by a hexadecimal number dddd

## Quantifiers    
* n+ - Matches any string that contains at **least one** n
* n* - Matches any string that contains **zero or more occurrences** of n
* n? - Matches any string that contains **zero or one occurrences** of n
* n{X} - Matches any string that contains a **sequence of X** n's
* n{X,Y} - Matches any string that contains a **sequence of X to Y** n's
* n{X,} - Matches any string that contains a **sequence of at least X** n's
* n$ - Matches any string with n at the **end** of it
* ^n - Matches any string with n at the **beginning** of it
* ?=n - Matches any string that is **followed by a specific string** n
* ?!n - Matches any string that is **not followed by a specific string** n
