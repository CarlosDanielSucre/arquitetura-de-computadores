# Multiplicação e divisão de numeros binarios

## Passos para multiplicar números binários:

### 1. Multiplicação:
Multiplique cada dígito do multiplicador pelo multiplicando. Se o dígito do multiplicador for 1, o resultado parcial será o próprio multiplicando. Se for 0, o resultado parcial será 0. 
### 2. Deslocamento:
Desloque cada resultado parcial para a esquerda em uma posição em relação ao anterior. O primeiro resultado parcial não é deslocado, o segundo é deslocado uma posição, o terceiro duas, e assim por diante. 
### 3. Soma:
Some todos os resultados parciais deslocados para obter o resultado final da multiplicação. 
### Exemplo:

Para multiplicar 1101 por 101:
#### Multiplicação:
```
1 * 1101 = 1101
0 * 1101 = 0000
1 * 1101 = 1101
```
#### Deslocamento:
```
    1101
   0000 (deslocado uma posição)
  1101 (deslocado duas posições)
```
#### Soma: 
```
     1101
    0000
   1101
   -----
   100001
```

Portanto, 1101 * 101 = 100001. 
Dica: É importante lembrar que a multiplicação por zero sempre resulta em zero, e a multiplicação por um não altera o número original. 
