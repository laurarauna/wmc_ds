# Revisão

## Índice

1. [Visão Geral](#visao-geral)
2. [Variáveis](#variaveis)
3. [Estruturas de Controle](#estruturas-de-controle)

---

## Visão Geral

**Dferença de notebook e orientado a objeto:** 
- Orientado a objeto é mais utilizado para backend e engenheiros de dados por ser mais fácil e o processamento está aclopado em métodos 
- Notebook é mais utilizado por analistas e cientistas de dados

## Variáveis


**Principais tipos de dados: string, int, float e booleano.**

```python

var_string = 'nome'
type(var_string) #Função para ver tipo de dado

var_int = 13
type(var_int)

var_float = 13.545
type(var_float)

var_bool = True #Sempre com a primeira maiúscula
type(var_bool)

```

**Principais operadores matemáticos**

```python
#Soma/Subtração/Multiplicação/Divisão
1+2
1-2
1*2
1/2

#Resultado inteiro da divisão
1//2

# Resto da divisão
1 % 2

```

**Principais operadores de comparação:**

Explicação dos Comentários
- Igual a (==): Compara se os valores são iguais.
- Diferente de (!=): Compara se os valores são diferentes.
- Maior que (>): Compara se o valor à esquerda é maior que o valor à direita.
- Menor que (<): Compara se o valor à esquerda é menor que o valor à direita.
- Maior ou igual a (>=): Compara se o valor à esquerda é maior ou igual ao valor à direita.
- Menor ou igual a (<=): Compara se o valor à esquerda é menor ou igual ao valor à direita.
- Expressões compostas: Mostra como combinar operadores de comparação para formar expressões mais complexas.

```python
# Definindo variáveis para comparação
a = 10
b = 20
c = 10

# Operador Igual a (==)
print("a == b:", a == b)  # Verifica se a é igual a b (False)
print("a == c:", a == c)  # Verifica se a é igual a c (True)

# Operador Diferente de (!=)
print("a != b:", a != b)  # Verifica se a é diferente de b (True)
print("a != c:", a != c)  # Verifica se a é diferente de c (False)

# Operador Maior que (>)
print("a > b:", a > b)    # Verifica se a é maior que b (False)
print("b > a:", b > a)    # Verifica se b é maior que a (True)

# Operador Menor que (<)
print("a < b:", a < b)    # Verifica se a é menor que b (True)
print("b < a:", b < a)    # Verifica se b é menor que a (False)

# Operador Maior ou igual a (>=)
print("a >= b:", a >= b)  # Verifica se a é maior ou igual a b (False)
print("a >= c:", a >= c)  # Verifica se a é maior ou igual a c (True)

# Operador Menor ou igual a (<=)
print("a <= b:", a <= b)  # Verifica se a é menor ou igual a b (True)
print("b <= a:", b <= a)  # Verifica se b é menor ou igual a a (False)

# Uso de operadores de comparação em expressões compostas
print("a < b < c:", a < b < c)  # Verifica se a é menor que b e b é menor que c (True)
print("a == b or b < c:", a == b or b < c)  # Verifica se a é igual a b ou b é menor que c (True)
print("not (a > b):", not (a > b))  # Verifica se a não é maior que b (True)

```

**Principais tipos de estrutura dedados: lits, tupla, dicionário e conjunto.**

- Listas (list): Estrutura de dados mutável, que permite adicionar, remover e acessar elementos. Usa colchetes [].
- Tuplas (tuple): Estrutura de dados imutável. Seus elementos não podem ser alterados após a criação. Usa parênteses ().
- Dicionários (dict): Estrutura de dados que armazena pares chave-valor. Permite acesso rápido aos valores através das chaves. Usa chaves {}.
- Conjuntos (set): Estrutura de dados que armazena elementos únicos e não ordenados. Também usa chaves {}.

```python
# 1. Listas
print("Listas:")
lista = [1, 2, 3, 4, 5]
print("Lista original:", lista)

# Adicionar elementos
lista.append(6)
print("Após adicionar 6:", lista)

# Remover elementos
lista.remove(3)
print("Após remover 3:", lista)

# Acessar elementos
print("Elemento na posição 2:", lista[2])

# Iterar sobre a lista
for item in lista:
    print("Item da lista:", item)

print()

# 2. Tuplas
print("Tuplas:")
tupla = (10, 20, 30, 40)
print("Tupla original:", tupla)

# Acessar elementos
print("Elemento na posição 1:", tupla[1])

# Tuplas são imutáveis, então não podemos adicionar ou remover elementos

# Iterar sobre a tupla
for item in tupla:
    print("Item da tupla:", item)

print()

# 3. Dicionários
print("Dicionários:")
dicionario = {'nome': 'Alice', 'idade': 30, 'cidade': 'São Paulo'}
print("Dicionário original:", dicionario)

# Adicionar um novo par chave-valor
dicionario['email'] = 'alice@example.com'
print("Após adicionar email:", dicionario)

# Remover um par chave-valor
del dicionario['idade']
print("Após remover idade:", dicionario)

# Acessar valores
print("Nome:", dicionario['nome'])

# Iterar sobre o dicionário
for chave, valor in dicionario.items():
    print(f"Chave: {chave}, Valor: {valor}")

print()

# 4. Conjuntos
print("Conjuntos:")
conjunto = {1, 2, 3, 4}
print("Conjunto original:", conjunto)

# Adicionar elementos
conjunto.add(5)
print("Após adicionar 5:", conjunto)

# Remover elementos
conjunto.discard(2)
print("Após remover 2:", conjunto)

# Conjuntos não permitem elementos duplicados
conjunto.add(4)
print("Após tentar adicionar 4 novamente:", conjunto)

# Iterar sobre o conjunto
for item in conjunto:
    print("Item do conjunto:", item)


```

## Estruturas de Controle

