 Projeto: Modelagem de Fluxo de Reset de Senha (BPMN 2.0)
 Descrição do Processo
Este diagrama mapeia o fluxo crítico de recuperação de senha utilizando a notação BPMN 2.0. O objetivo é separar claramente as responsabilidades entre Client-side (Usuário) e Server-side (Sistema).

🛠 Componentes Técnicos Utilizados:
Pools/Lanes: Organização de responsabilidades (User vs. Backend).

Service Tasks: Representam chamadas de API e consultas ao Banco de Dados (ex: validação de e-mail).

User Tasks: Pontos de interação humana onde o sistema aguarda um input de tela.

Exclusive Gateways (XOR): Lógica condicional para tratamento de exceção (usuário não encontrado).
