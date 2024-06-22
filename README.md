# Projeto Store.py

Este código Python é uma aplicação para gerenciamento de loja que oferece menus interativos para adicionar, remover, buscar e ordenar produtos, pedidos e clientes, incluindo funcionalidades como geração de dados aleatórios, embaralhamento de arquivos e operações em uma árvore B, além de fornecer informações sobre o saldo da loja.

## Focos Principais
Organização dos Dados em Memória Secundária: O projeto se concentra em técnicas avançadas de organização de dados em memória secundária, incluindo arquivos, acesso sequencial e aleatório, registros de tamanho fixo e variável, ordenação em disco, reutilização de espaço e indexação de arquivos.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação usada para desenvolver a aplicação.
- **Pandas**: Biblioteca utilizada para manipulação e análise de dados.
- **Faker**: Usado para gerar dados falsos para simulação.
- **ArvoreB**: Implementação personalizada de uma árvore B para estruturas de dados.
- **Busca Binária**: Algoritmo eficiente para busca em listas ordenadas.
- **Seleção Natural**: Método de seleção de partições ordenadas para otimização de dados

## Dependências

Para executar o projeto, você precisa ter as seguintes bibliotecas instaladas:

```python
import time
import random
import os
import pandas as pd
from faker import Faker
# Certifique-se de ter o módulo ArvoreB disponível
from ArvoreB import *
