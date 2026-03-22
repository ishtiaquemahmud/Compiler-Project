How to run:::

flex filename.l

bison -d -t bisonfilename.y

gcc lex.yy.c filename.tab.c

./a.exe



Features::::

Variable declaration: num, real, text

Input/output: take, show

Comments:

Single-line: :: comment

Multi-line: ::< ... >::
