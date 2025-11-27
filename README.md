# Python-Back-end

´´´
Função que calcula a idadde de um usuário
´´´

´´´

### Função que calcula a idade de um usuário
```
def calcular_idade():
    ano_nascimento = int(input('Digite o ano que você nasceu: '))
    ano_atual = int(input('Digite o ano atual no formato yyyy: '))
    idade = ano_atual - ano_nascimento
    return idade
print(f'A sua idade é {calcular_idade()}' ' anos.')
```

### Função que conta caracteres de uma palavra digitada pelo usuário
```
def contagem_caracteres(palavra):
    return len(palavra)

palavra = input('Digite uma palavra: ')
print(f'A sua palavra contém {contagem_caracteres(palavra)} caracteres.')
```
