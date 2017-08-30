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
