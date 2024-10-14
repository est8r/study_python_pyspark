## Variaveis
São como containers que armazenam dados de tipos diversos (numero, texto, boolean e etc).

- para declarar uma variavel basta iniciar com um nome:
```
x = 2
y = 6
```

<img width="295" alt="image" src="https://github.com/user-attachments/assets/e7eab336-218d-42fc-9fbf-4406760fd21c">

## Modificação de Dados
Durante os processos das aplicações, pode ser necessário trocar os tipos e/ou valores das variaveis, ex:

```
x = 3
y = 4
z = 5

print(x) // 3
print(y) // 2
print(z) // 5

// transformar o integer X em string
x = str(3) // "3"

// fixar o integer Y em um integer fixo
y = int(4)

// transformar o integer Z em float
z = float(z)

print(x + x) //"33", os dois textos "3" concatenaram
print(y + y) // 8, somou
print(z + z) // 10.0. continua um float
```

### praticando...

- mesclar variaveis de texto com variaveis de numero e string literal
```
# frase: a ester tem 22 anos e mora na idade de são paulo

nome = "ester"
idade = 22
cidade = "são paulo"

print("a " + nome + " tem " + str(idade) + " anos e mora na cidade de " + cidade)
// a ester tem 22 anos e mora na idade de são paulo
```
- usar str() nos integers pois somente strings se concatenam entre si
- poderiamos resolver o erro já convertendo na declaração com idade = str(22), porém não poderiamos usar o valor da idade em fomato numero em mais nenhum local do código, sendo melhor então, converter no local de uso

