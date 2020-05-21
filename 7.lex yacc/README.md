Run following commands on console

lex while_ic.l

yacc -dy while_ic.y

gcc y.tab.c -ll ly

./a.out

Enter the expression : while(b=c/d) b=b*c+f;
