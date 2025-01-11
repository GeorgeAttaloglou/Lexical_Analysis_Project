
# Instructions

in the terminal enter these commands
- flex lexer.l > creates lex.yy.c file
- bison -d parser.y > creates parser.tab.c/h
- g++ parser.tab.c lex.yy.c -o parser > creates parser
- ./parser > executes parser

---

# TODO  
1. Implement file read
2. Add interval operation syntax

# Resources
- [lex and bison videos i found](https://www.youtube.com/watch?v=POjnw0xEVas)
- [eclass examples](https://www.dit.uoi.gr/e-class/modules/document/file.php/336/Flex_Examples.pdf)
.
.
.