all:
	flex parser.l
	yacc -d parser.y
	gcc -o example lex.yy.c y.tab.c -ll -w