# Exercício 1

Crie um programa que imprima na tela o seguinte resultado:

```
Olá José, seja bem vindo!
```

Dica: Lembre-se de utilizar uma variável para armazenar o nome ```José```.

# Exercício 2 (Desafio)

Faça um programa que imprima a data de hoje. Com o seguinte resultado:

```
Hoje é dia 27/11/2021.
```
Dica: Utilize uma variável para dia, mês e ano

## Problemas do Exercício 2

Você deve ter percebido que após resolver o exercício, pode ter ocorrido alguns problemas no seu código.

O primeiro problema é que o código ficou muito grande e confuso, por exemplo:

```
dia = "27"
mes = "11"
ano = "2021"

print("Hoje é dia " + dia + "/" + mes + "/" + ano)
```
Você pode utilizar um outro jeito para diminuir seu código:

```
dia = "27"
mes = "11"
ano = "2021"

print("Hoje é dia %i/%i/%i"%(dia,mes,ano))
```

Perceba que o ```%i```, assim como o ```%d``` é utilizado para substituir o lugar de uma variável no Python, e após as aspas do comando é necessário apenas escrever ```%()``` e dentro dos parênteses as respectivas variáveis, como foi indicado no código acima dentro das aspas do ```print()```.