# Projeto Final INF0994

Projeto desenvolvido a pedido do **Prof. Dr. Bruno Cafeo** como atividade de conclusão da disciplina **Gerenciamento Ágil
de Projetos - INF0994** do curso de extensão **Tecnologias Microsoft**, oferecido pela **Universidade de Campinas (UNICAMP)**. O objetivo desse trabalho é utilizar técnicas de gerenciamento ágil e Lean para desenvolver um produto que atenda a uma necessidade de um cliente fictício. Durante o projeto os membros da equipe foram distribuídos nos seguintes papéis Scrum:
* Scrum Master: Rodrigo Mauricio de Oliveira
* Product Owner: Fernando Cipriano Dias
* Equipe de Desenvolvimento: Matheus Ribeiro da Silva
* Equipe de Desenvolvimento: Marcos de Souza Ribeiro Junior

## Proposta de Solução:

Desenvolveremos um sistema para gerenciamento de ordens de serviço de uma assistência técnica de notebooks, desktops e smartphones chamada **PauloNotebook**.

### Principais Funcionalidades

* Cadastro de Clientes
* Cadastro de equipamentos com defeito
* Geração de Ordem de Serviço

#### Cadastro de Clientes

O sistema deve ser capaz de cadastrar novos clientes, realizando validações para campos que possam diferenciar um cliente de outro. Também deve ser possível efetuar operações de edição, consulta e remoção dos cadastros realizados.

#### Cadastro de equipamentos com defeito

O sistema deve ser capaz de cadastrar os equipamentos com defeito, vinculando os mesmos aos seus proprietários e inserir a descrição do problema fornecida pelo proprietário.<br>
A equipe técnica deverá ser capaz de consultar o histórico de atendimento daquele equipamento, identificando se já foi realizada alguma manutenção no mesmo. Também deverá ser possível realizar consultas por tipo de defeito classificado, verificando outros aparelhos que apresentaram o mesmo problema.

#### Geração de Ordem de Serviço

O sistema deve ser capaz de gerar uma ordem de serviço (OS) contendo os dados do cliente solicitante e equipamento com defeito. Essa ordem de serviço terá posteriormente o diagnóstico emitido pela equipe técnica e o orçamento para realização da manutenção.<br>
O atendente balcão poderá realizar consultas na OS para verificar o status do serviço e quando este for finalizado, deverá ser capaz de encerrar a OS, retirando o pedido da fila de atendimento.

## Fluxo de Trabalho PauloNotebook

<img src="https://github.com/MarcosRibeiroJ/PauloNotebook/blob/master/img/PauloNotebook.jpg">
