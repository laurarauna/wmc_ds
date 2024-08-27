# Numpy

## Visão Geral

O NumPy é uma biblioteca fundamental para a computação científica em Python. Ele fornece suporte para arrays multidimensionais e funções matemáticas eficientes para operar sobre esses arrays.

**Importando Numpy**

```python

import numpy as np

```

## Array

- Estrutura principal do Nupy
- Formada de grades que armazenam dados
-Podem ter várias dimensões
- Só armazenam um tipo de dado

**Criando um array**

```pyhton

# Criação de um array
l = [4, 8, 2, 12, 5, 8, 0]

arr = np.array(l)
arr

```

## Porque usar Numpy

- Arrays NumPy aceita que todos os elementos sejam de
diferentes tipo de dados, contudo o array sempre terá
apenas um tipo de dados*. Contudo a normal dentro da
análise de dados que usamos apenas um tipo de dados
dentro de um array.
- Ocupa menos espaço (por ser unitipo).
- Listas são unidimensionias.
- Processamento de dados é mais rápido.
- Tipos primitivos de dados podem ser armzenados em arrays e não em listas.

## Tipos de Dados

**Numéricos:**

- numpy.int32, numpy.int64: Inteiros com precisão específica.
- numpy.float32, numpy.float64: Números de ponto flutuante com precisão específica.
- numpy.complex64, numpy.complex128: Números complexos com precisão específica.


**Arrays:**

- numpy.ndarray: Arrays multidimensionais, que podem conter elementos de tipos específicos e suportam operações matemáticas e científicas eficientes.


**Outros Tipos:**

- numpy.bool_: Tipo booleano em arrays NumPy.
- numpy.str_: Strings em arrays NumPy.
- numpy.object_: Tipo genérico que pode conter qualquer tipo de objeto.


**Diferenças com tipos de dados em Python:**
- Mutabilidade: Em Python, listas (list) são mutáveis, enquanto tuplas (tuple) são imutáveis. Em NumPy, arrays (numpy.ndarray) são geralmente mutáveis.
- Precisão Numérica: Python tem tipos int, float e complex com precisão padrão. NumPy permite especificar a precisão dos números com tipos como numpy.float32 e numpy.int64.
- Estruturas de Dados: Python tem tipos básicos e coleções nativas, enquanto NumPy é especializado em arrays multidimensionais para computação científica.

