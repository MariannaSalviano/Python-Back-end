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

### Solicita dois números para o usuário e realiza a soma dos números recebidos
```
def somar(a, b):
    return a + b

try:  
    numero_1 = float(input('Digite o primeiro número: '))
    numero_2 = float(input('Digite o segundo número: '))
    
    resultado = numero_1 + numero_2
    print(f'A soma é {resultado}')
    
except ValueError:
    print("Digite apenas números válidos")
```    
  print('A quantidade de vendas foi a mesma para ambos os itens')
```
