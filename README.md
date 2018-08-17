
Inspired by Gustavo Rodriguez-Rivera and Justin Ennen: Introduction to Systems Programming: a Hands-on Approach
https://www.cs.purdue.edu/homes/grr/SystemsProgrammingBook/

To compile,
```
make
./xshell
```
Files
```
shell.c, shell.h - contains built-in functions, execution functions, and how the shell functions.
lexer/lex.l, put the input char together into tokens.
parser/yacc.y - parses tokens according to 'Backus-Naur Form' grammar and build the command table.
lists/chain.c and ll.c - linked list and command table container definitions.
```

Commands in the form of
```
cmd [arg]* [|cmd [arg]*]* [< fn1] [>[>] fn2] [2>fn3 || 2>&1] [&]
'''
