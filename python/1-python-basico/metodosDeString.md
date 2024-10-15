## Métodos de string
manipulam strings para transformar, cortar e manipular

```
texto = "eu adoro comida italiana"
print(texto)

# garantir/transformar tudo em letra minuscula
print(texto.lower())

# garantir/transformar tudo em letra maiuscula
print(texto.upper())

# garantir/transformar a letra inicial da frase em maiuscula
print(texto.captalize())

# procurar por uma letra e retornar a posição/index
print(texto.find('c')) // 9, ele é case sensitive

# procurar por uma palavra e retornar a posição/index
print(texto.find('adoro')) // 3, ele é case sensitive ; se retornar -1 quer dizer que ele não encontrou

# substitui um iten por um novo, deve especificar o antigo e o novo valor
print(texto.replace('a', 'e')) //  'eu adore comide iteline'
print(texto.replace('italiana', 'coreana')) //  'eu adoro comida coreana'

# remove qualquer espaço que tiver antes do primeiro caractere da frase
print(texto.strip()) // '   eu adoro...' > 'eu adoro...'

*testar mais metodos/funções*

```
