# Sistema de Vendas de Salgados

Este sistema foi desenvolvido como projeto prático para a disciplina de Programação Orientada a Objetos (POO). A aplicação gerencia o fluxo de vendas, cadastros de clientes e processamento de pedidos para uma lanchonete.

## Tecnologias e Arquitetura

O projeto utiliza **Python 3** e **SQLite** para o banco de dados. A arquitetura seguiu o padrão de projeto **MVC (Model-View-Controller)** para assegurar a separação de responsabilidades e facilitar a manutenção do código.

## Estrutura de Diretórios

* **models/**: Contém as classes principais (`Usuario`, `Alimento`, `Pedido`, `Salgado`, `Bolo`) e a lógica de negócio.
* **views/**: Implementa as interfaces de usuário via **Flet**.
* **controllers/**: Atua como intermediário, processando as entradas da View e manipulando os Models.
* **data/**: Camada responsável pela comunicação com o banco de dados.

## Documentação de Design

O projeto inclui documentação técnica detalhada localizada na pasta `docs/`, incluindo o diagrama de classes **UML** e o relatório técnico em **LaTeX**, que detalham as decisões de design e a hierarquia de classes (como a herança de `Alimento` por `Salgado` e `Bolo`).

## Instalação e Execução

Para configurar e executar o projeto em seu ambiente local, execute os seguintes comandos no terminal:

```bash
# 1. Clonar o repositório
git clone https://github.com/Cauecmps/sistema_vendas.git

# 2. Acessar o diretório do projeto
cd sistema_vendas

# 3. Executar a aplicação
python main.py
