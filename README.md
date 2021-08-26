
#Criando um compilador

###Tokens
São unidades lógicas que representam um ou mais caracteres

- Cada palavra chave é um token. Ex: then, begin, integer
- Cada identificador é um token. Ex: a, soma, var1
- Cada constante é um token. Ex: 123, 123.456, 1.2E3
- Cada sinal é um token. Ex: (, <, <=, +

###Programa fonte
O arquivo lex.l é compilado pelo compilador Lex gerando o arquivo lex.yy.c  de pois é compilado pelo  compilador C gerando o arquivo a.out onde tem o  fluxo de entrada a.out e sequêcia de tokens.

#####exemplo:
```shell
 flex lex.l
 cc lex.yy.c -lfl
 ./a.out
```