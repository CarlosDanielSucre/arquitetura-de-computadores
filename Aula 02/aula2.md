

[Link de calculadora online](https://www.calculadoraonline.com.br/basica)

## Padrões Informatica

- Tabela ASCII ➔ Código criado na década de 60 por Robert W. Bemer
para unificar a representação de caracteres alfanuméricos em
computadores
- ASCII significa “American Standard Code for Information Interchange”
ou ”Código Padrão Americano para o Intercâmbio de Informação”
- Sua função é padronizar a forma como os computadores representam
letras, números, acentos, sinais diversos e alguns códigos de controle
- Vai do número 0 até 127, sendo que os 32 primeiros e o último são
considerados de controle, os demais representam "caracteres imprimíveis"
- Alguns caracteres caíram em desuso, como o Line Feed que fazia a
impressora avançar o papel

## Aritmética de bases Numéricas

- Operações números binários ➔ de forma análoga aos números
decimais, pode-se fazer operações matemáticas como somar, subtrair,
multiplicar, dividir, etc diretamente com números binários

### a) Soma de números binários 

Regras:
```
0 + 0 = 0
0 + 1 = 1
1 + 1 = 0 (Carrega 1 para o dígito de ordem superior)
1 + 1 + 1 = 1 (Carrega 1 para o dígito de ordem superior)
```
Exemplo:
```bin
  0101  
+ 0010
-------
  0111

  0011
+ 0110
------
  1001
```

### b) Subtração de números binários 

Regras:
```
0 − 0 = 0
0 − 1 = 1
1 − 0 = 1
1 − 1 = 0
```
Exemplo:
```
  0111
− 0011
------
  0100
   
  0110
− 0011
------
  0011

```
## b) Subtração de números binários
▪ Uma opção é usar complemento de 2 do numero binário (negativo do
número), para isto, faço do complemento de um (negar o número) e somar 1
▪ A – B = A + (-B)
Exemplo
```
  0111
− 0011       Complemento de 2 de 0011 = 1100 + 0001 = 1101
------
    ?

  0111
+ 1101
------
  0100
```

## Operações números hexadecimais
De forma análoga aos números decimais e binários, pode-se fazer operações matemáticas como somar, subtrair, multiplicar, dividir, etc diretamente com números hexadecimais

### a) Soma de números hexadecimais 
Somar os elementos e caso “estoure” a contagem, carregar 1 para a próxima coluna
```
  5𝐶12
+ 27𝐴4
------
  83𝐵6
```