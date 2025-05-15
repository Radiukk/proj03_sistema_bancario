# proj03_sistema_bancario

<h1> Projeto Banco Virtual em Python </h1>
Este é um projeto simples de sistema bancário desenvolvido em Python como exercício prático de programação. O objetivo principal é demonstrar o uso de funções, estruturas condicionais, laços de repetição, entrada e saída de dados, e manipulação de variáveis globais.

<h2> Funcionalidades Atuais </h2>
O sistema simula as principais operações de um banco virtual, permitindo que o usuário:

Consultar Saldo: Exibe o saldo atual da conta.

Depositar: Permite ao usuário inserir um valor para depósito, que é somado ao saldo.

Sacar: Permite ao usuário retirar um valor da conta, verificando se há saldo suficiente antes da operação.

Sair: Encerra a aplicação de forma segura.

Recursos do Programa
Validação de entrada: Garante que a opção digitada no menu seja um número entre 1 e 4.

Laço de repetição (while True): Mantém o programa em execução até que o usuário escolha sair.

Funções modulares: Cada operação (consultar, sacar, depositar) é implementada como uma função separada.

Uso de variável global: O saldo é mantido como uma variável global e atualizado conforme as operações são realizadas.

Mensagens claras: O sistema fornece feedback para o usuário em cada etapa.

<h2> Estrutura do Código </h2>
O código está organizado em um único arquivo Python (banco_virtual.py ou similar), contendo as seguintes partes:

Declaração do saldo inicial

Funções principais (consultar_saldo(), sacar(), depositar())

Menu interativo com validação

Execução contínua via laço while

Encerramento limpo da aplicação

<h1> Próximos Passos (Sugestões de Melhorias) </h1>
O projeto pode ser expandido com várias funcionalidades adicionais:

Interface Gráfica (GUI): Criar uma versão visual com Tkinter ou PyQt.

Histórico de Transações: Salvar ou exibir as operações realizadas.

Persistência de Dados: Salvar o saldo em arquivo ou banco de dados para manter as informações entre execuções.

Sistema de Login: Permitir múltiplos usuários com autenticação.

Testes Automatizados: Adicionar testes unitários para garantir a integridade das funções.

<h1> Contribuição </h1>
Contribuições são bem-vindas! Se você tiver sugestões, melhorias ou encontrar algum problema, sinta-se à vontade para abrir uma issue ou enviar um pull request.

<h1> Autor: Bruno Radiuk </h1>

Este código foi desenvolvido como um exercício de aprendizado em Python.
