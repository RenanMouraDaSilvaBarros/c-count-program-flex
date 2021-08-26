
**Tokens** são unidades lógicas que representam
um ou mais caracteres

– Cada palavra chave é um token. Ex: then, begin, integer
– Cada identificador é um token. Ex: a, soma, var1
– Cada constante é um token. Ex: 123, 123.456, 1.2E3
– Cada sinal é um token. Ex: (, <, <=, +

programa fonte

lex.l-> compilador Lex-> lex.yy.c -> compilador C a.out -> fluxo de entrada a.out -> sequêcia de tokens

```shell
 flex fb1-1.l
 cc lex.yy.c -lfl
 ./a.out
```