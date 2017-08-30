# RegExCheatSheet
---

## Brackets

#### [abc]
    Find any character between the brackets
```javaScript
/[abc]/ 

```
#### [^abc]
    Find any character NOT between the brackets
```javaScript
/[^abc]/ 

```
#### [0-9]
    Find any character between the brackets (any digit)
```javaScript
/[0-9]/ 

```
#### [^0-9]
    Find any character NOT between the brackets (any non-digit)
```javaScript
/[^0-9]/ 

```
#### (x|y)
    Find any of the alternatives specified
```javaScript
/(x|y)/ 

```
---

## Metacharacters

#### Single Character (.)
    
```javaScript
/h.t/g

```

#### Digits/Numerables & Reversal
    The \d metacharacter is used to find a digit from 0-9.
```javaScript
/\d/ 

```

OR

    Find a non-digit character
```javaScript
/\D/ 

```
#### Words & Reversal

    A word character is a character from a-z, A-Z, 0-9, including the _ (underscore) character.

```javaScript
/\w/ 

```
OR
    Find a non-word character
```javaScript
/\W/ 

```

#### Global Search 
    The g modifier is used to perform a global match (find all matches rather than stopping after the first match).
```javascript
/\d/g 
```
#### Whitespace & Non-Whitespace

    The \s metacharacter is used to find a whitespace character.

```javaScript
/\s/ 

```
OR
    Find a non-Whitespace character
```javaScript
/\S/ 

```
#### Case-Insensitive Matching
    The i modifier is used to perform case-insensitive matching.
```javaScript
/lee/i
```
#### Match at the beginning or the end of a word
    Find a match at the beginning/end of a word
```javaScript
/\bgoogle/g
```

OR
    Find a match not at the beginning/end of a word
```javaScript
/\Bgoogle/g
```
#### Find a NUL character
    \0 returns the position where the NUL character was found. If no match is found, it returns -1.
```javaScript
/\0/
```
#### Find a new line character
```javaScript
/\n/
```
#### Find a form feed character
```javaScript
/\f/
```
#### Find a carriage return character
    \r returns the position where the carriage return character was found. If no match is found, it returns -1.
```javaScript
/\r/
```
#### Find a tab character
    \t returns the position where the tab character was found. If no match is found, it returns -1.
```javaScript
/\t/
```

---

## Quantifiers

#### Matches any string that contains at least (x)
```javaScript
/n+/g
```
#### Matches any string that contains zero or more occurrences of (x)
```javaScript
/n*/g
```
#### Matches any string that contains zero or one occurrences of (x)
```javaScript
/n?/g
```
#### Matches any string that contains a sequence of (x) n's
```javaScript
/n{x}/g
```
#### Matches any string that contains a sequence of (x) to (z) n's
```javaScript
/n{x,z}/g
```
#### Matches any string that contains a sequence of at least (x) n's
```javaScript
/n{x,}/g
```
#### Matches any string with n at the end of it
```javaScript
/n$/g
```
#### Matches any string with n at the beginning of it
```javaScript
/^n/g
```
#### Matches any string that is followed by a specific string n
```javaScript
/?=n/g
```
#### Matches any string that is not followed by a specific string n
```javaScript
/?!n/g
```
