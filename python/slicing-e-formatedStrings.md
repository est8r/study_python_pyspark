## Slicing
serve para quando queremos usar apenas um 'pedaço' de um certo dado

```
fruta = 'abacate'
print(fruta)

# queremos dar print somente na ultima letra especificando seu index
print(fruta[6])

# de uma letra até outra
print(fruta[2:6]) //acat, sem a ultima letra pois por regras internas do python, ele não mostra o ultimo index mesmo especificando

# com valor negative
print(fruta[-1])
// E

```
- cada caracter das strings possuem uma posição, um index, começando em 0
- python é uma das unicas linguagens que aceita numeros negativos nas funções e chamadas

mais exemplos:
```
valor = 99.75
valor = str(valor) // precisa converter pois tipo float não aceita definição de index

print(valor[3:5]) // 75, o :5 é um numero a mais de index para que ele mostre o ultimo valor
print(valor[2:]) // .75, tambem funciona
```
- para passar por cima da regra do python que não mostra o ultimo caracter, basta colocar um numero de index a mais



