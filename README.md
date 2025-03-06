# Sistema Bancário Simples em Python

Este projeto é uma replicação de um sistema bancário simples desenvolvido como parte de um curso na plataforma educacional Digital Innovation One (DIO). O objetivo principal é demonstrar e praticar conceitos básicos de programação em Python, como funções, estruturas de controle, manipulação de dados e interação com o usuário através do terminal.

## Funcionalidades

O sistema bancário implementa as seguintes funcionalidades:

* **Depósito:** Permite adicionar um valor ao saldo da conta.
* **Saque:** Permite retirar um valor do saldo da conta, com limite de valor e número de saques diários.
* **Extrato:** Exibe um histórico de depósitos e saques, além do saldo atual.
* **Criação de Usuário:** Permite cadastrar novos usuários no sistema.
* **Criação de Conta:** Permite criar novas contas bancárias associadas a usuários existentes.
* **Listagem de Contas:** Exibe informações de todas as contas cadastradas.

## Como Executar

### Pré-requisitos

* Python 3.6 ou superior instalado.
* VS Code (opcional, mas recomendado).

### Execução

1.  Clone ou baixe este repositório.
2.  Abra o terminal e navegue até o diretório do projeto.
3.  Execute o arquivo `sistema_bancario_otimizado.py` com o comando `python sistema_bancario_otimizado.py`.
4.  Siga as instruções no terminal para interagir com o sistema.

## Estrutura do Código

O código está organizado em funções que representam as diferentes operações bancárias e de gerenciamento de usuários e contas. As principais funções são:

* `menu()`: Exibe o menu principal e captura a opção do usuário.
* `depositar()`: Realiza a operação de depósito.
* `sacar()`: Realiza a operação de saque.
* `exibir_extrato()`: Exibe o extrato da conta.
* `criar_usuario()`: Cadastra um novo usuário.
* `filtrar_usuario()`: Busca um usuário por CPF.
* `criar_conta()`: Cria uma nova conta bancária.
* `listar_contas()`: Lista todas as contas cadastradas.
* `main()`: Função principal que controla o fluxo do programa.

## Observações

Este projeto é uma replicação de um desafio proposto pela DIO, com algumas adaptações e melhorias. O objetivo é consolidar conhecimentos em programação Python e demonstrar a capacidade de implementar um sistema simples e funcional.

## Contribuição

Contribuições são bem-vindas! Se você tiver sugestões de melhorias ou correções, sinta-se à vontade para abrir uma issue ou enviar um pull request.
