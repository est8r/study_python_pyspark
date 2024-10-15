## Input
o comando Input serve para interagir com o usuário coletando alguma informação para utilizar dentro do código

```
# frase: a ester tem 22 anos e mora na idade de são paulo

nome = input("Qual é o seu nome: ") //o programa irá ler esta linha, entender o comando input e solicitar ao usuario a informação
idade = input("qual a sua idade? ")
cidade = "são paulo"

// após as perguntas, a frase aparecerá completa

```
- o programa não irá continuar a execução até que o usuário digite o dado solicitado no input
- o texto digitado após o comando irá aparecer para o usuario, quando ele responder, a informação da resposta será diretamente
guardada na variavel em que antes estava a mensagem para ser usada

## Calculando com input

sem input:
```
anoNascimento = 1985
idade = 2024 - anoNascimento

print(idade)
// 39
```

com input:
```
anoNascimento = input("em que ano vc nasceu? ") //sera uma string, tem que converter
idade = 2024 - int(anoNascimento)

print(idade)
// 39
```
- agora, o usuario irá digitar o ano (interagir), esse dado sera armazenado na variavel e servirá para fazer o calculo da idade
