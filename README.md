# Python-Back-end

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

### Função que retorna saudação para o usuário
```
def exibir_saudacao_hora():
    hora_atual = int(input('Digite a hora atual (digite números entre 0 a 23): '))

    if hora_atual < 12:
        return 'Bom dia!'
    elif hora_atual < 18:
        return 'Boa tarde!'
    else:
        return 'Boa noite!'    

print(exibir_saudacao_hora())
```

### Verifica se um produto já foi cadastrado no sistema
```
produtos = ['Creme Facial Hidratante LuminaSoft 50ml', 'Sérum Anti-Idade RadiantLift 30ml', 'Gel de Limpeza PurifySkin 120ml', 'Tônico Revitalizante SkinBoost 200ml' ]
produto = input('Digite o produto que você quer verificar: ')

if produto in produtos:
  print('Produto já cadastrado no sistema')
else:
  print('O produto ainda não está cadastrado no sistema')  

print(f'Lista de produtos cadastrados: {produtos}')
```


### Compara a maior venda quantidade entre dois produtos
```
po_compacto = input('Digite a quantidade de Pó compacto vendida: ')
base_liquida = input('Digite a quantidade de Base líquida vendida: ')

if po_compacto > base_liquida:
   print('O pó compacto obteve uma quantidade de venda maior.')
elif po_compacto < base_liquida:
  print('A base liquida obteve uma quantidade de venda maior')
else:
  print('As dois itens tiveram a mesma quantidade de vendas')
```

### Solicita dois números para o usuário, realiza a soma dos números recebidos e compara se é maior, igual ou menor que 100.
```
def somar(a,b):
  return a + b

while True:
  try:
      numero_1 = int(input('Digite um numero inteiro: '))
      numero_2 = int(input('Digite um numero inteiro: '))

      soma = numero_1 + numero_2

      print(f'A soma dos números é {soma}.')

      if soma > 100:
        print('A soma dos números é maior que 100.')
      elif soma == 100:
        print('A soma dos números é igual a 100.')
      else:
        print('A soma dos números é menor que 100.')  
      break

  except ValueError:
        print("Digite apenas números válidos")
```    
