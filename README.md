# Grammar
Grammar is the set of rules that describe all the possible strings in given language.

# Token
Individual unit

# Parser

# Compiler
A compiler is a program that translates code written in one programming language into another language.

# Interpreted Languages
Implements semantics themselves. For example interpreter answers the questions:

- How a function is called?
- What does it mean to create a variable?

# Compile Time (Static Time)
The phase program have not been executed.

Example of a static time operations:
```
Tokenizer -> Tokens -> Parser -> AST
```

# Compiled Languages
Delegate semantics to a target language

# Parser Combinators
Small parsers that combine to make more complex parsers


# Tokenizer (Lexical Analysis)
Tokens are pieces of strings which has identified meaning in a language.

Example code:
```

(add 1 2 (subtract 6 3))

```
Tokens for this example are "(", "add", "1" , "2", "(", "subtract", "6", "3", ")", ")"

Tokens have types and values.

So for the given example it would be like:

{ "opening_paranthesis" : "(" }
{ "keyword" : "add" }

and so on..
