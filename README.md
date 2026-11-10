# 🛒 Atividade: Manipulação de Listas em Python

![Python](https://img.shields.io/badge/python-3.x-blue.svg) 
![Status](https://img.shields.io/badge/status-concluido-success.svg) 
![Licença](https://img.shields.io/badge/license-MIT-green.svg)

Este repositório contém uma aplicação prática e interativa em Python voltada para o estudo e manipulação de estruturas de dados básicas, especificamente listas dinâmicas (`list`).

## 📌 Sobre o Projeto

O programa simula um fluxo de cadastro e controle simplificado de estoque de uma loja de roupas. Ele permite que o usuário adicione novos produtos com seus respectivos preços, liste os produtos de forma pareada e realize operações de exclusão baseadas na lógica de **Pilha** (LIFO - *Last In, First Out*).

### Conceitos Praticados:
- **Métodos de Lista:** Uso do `.append()` para inserção de dados e `.pop()` para remoção.
- **Funções Integradas:** Uso do `zip()` para iterar simultaneamente sobre duas listas distintas (produtos e preços).
- **Estruturas de Controle:** Validações de fluxo com estruturas condicionais (`if/else`) e repetição (`for`).
- **Tipos de Dados:** Conversão de tipos (`float` e `int`) na entrada de dados via console.

## ⚙️ Funcionalidades

1. **Estoque Inicial:** O programa inicia com uma lista padrão de produtos (Camiseta, Calça e Jaqueta).
2. **Cadastro Dinâmico:** O usuário pode cadastrar um novo produto informando nome e preço.
3. **Visualização em Tempo Real:** Exibição da tabela de preços atualizada formatada.
4. **Remoção de Itens:** Permite ao usuário remover o último item adicionado da lista caso tenha cometido algum erro.

## 🚀 Como Executar o Projeto

### Pré-requisitos
Você precisará ter o **Python 3** instalado em sua máquina.

### Passo a Passo
1. Clone este repositório para o seu ambiente local:
   ```bash
   git clone https://github.com/okamA3/Atividade-Lista-em-Python.git
Acesse a pasta do projeto:
cd Atividade-Lista-em-Python
Execute o script:
python main.py
(Ou execute diretamente no seu ambiente de preferência como VS Code ou Google Colab)
💻 Exemplo de Execução no Terminal
**** Cadastre um novo produto ****

Digite o nome do produto: Moletom de Cria
Digite o preço do produto: 49.59

Produto cadastrado com sucesso!

Camiseta Básica custa R$ 49.9
Calça Jeans custa R$ 129.9
Jaqueta Corta-Vento custa R$ 219.9
Moletom de Cria custa R$ 49.59

Deseja excluir um produto cadastrado?: 1 = Sim 0 = Não
1
O Moletom de Cria de R$ 49.59 foi removido com sucesso!

Camiseta Básica custa R$ 49.9
Calça Jeans custa R$ 129.9
Jaqueta Corta-Vento custa R$ 219.9
🤝 Contribuidores
[redacted link] - Desenvolvedor do projeto.
Desenvolvido como atividade prática para fixação de conceitos de lógica em Python. ```
