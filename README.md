# Tasks
Sistema desenvolvido com foco em pessoas com TDAH, priorizando simplicidade, organização e redução de distrações.

-Descrição

O Tasks é uma aplicação web responsivo para dispositivos movéis que permite ao usuário gerenciar suas tarefas diárias de forma simples e eficiente.O sistema foi projetado pensando em usuários com Transtorno de Déficit de Atenção e Hiperatividade (TDAH), oferecendo uma interface limpa e funcional.

---------------------------------------------------------------------------------------------------
🎯 Objetivo

Ajudar usuários a organizarem suas tarefas e manterem o foco, utilizando uma abordagem minimalista e intuitiva.

---------------------------------------------------------------------------------------------------
🚧 Status do Projeto

O projeto encontra-se em fase de planejamento e prototipação.
A implementação do código será realizada nas próximas etapas.

---------------------------------------------------------------------------------------------------
🚀 Funcionalidades Planejadas

✅ Adicionar tarefas
📋 Listar tarefas
✔️ Marcar como concluída
❌ Remover tarefas
🎯 Destacar tipo de tarefas

---------------------------------------------------------------------------------------------------
🏗️ Arquitetura

O sistema utilizará:
Arquitetura Cliente-Servidor
Arquitetura em Camadas

Camadas:
Front-end: HTML, CSS, JavaScript
Back-end: PHP
Banco de Dados: MySQL

---------------------------------------------------------------------------------------------------
🛠️ Tecnologias Utilizadas

Figma

Google Docs

GitHub

Canva

Flaticon

Draw.io

DBdesigner 4

---------------------------------------------------------------------------------------------------
🌐 Comunicação Web

A comunicação entre cliente e servidor será feita através do protocolo HTTP.

Exemplos:

GET /listar_tarefas.php → Buscar tarefas

POST /criar_tarefa.php → Criar nova tarefa

Status HTTP:

200 → Sucesso

404 → Não encontrado

500 → Erro no servidor

---------------------------------------------------------------------------------------------------
🔄 Fluxo de Funcionamento da Aplicação

➕ Adicionar tarefa

-O usuário insere uma nova tarefa na interface

-O front-end envia uma requisição HTTP do tipo POST

-O back-end processa a requisição em PHP

-A tarefa é armazenada no banco de dados MySQL

-O servidor retorna uma resposta de sucesso (200 OK)

-A tarefa é exibida na lista para o usuário

📋 Listar tarefas

-O sistema envia uma requisição GET ao servidor

-O back-end consulta o banco de dados

-As tarefas são retornadas ao front-end

-O usuário visualiza a lista de tarefas

❌ Remover tarefa

-O usuário clica na opção de remover

-Uma requisição é enviada ao servidor

-O back-end remove a tarefa do banco de dados

-O sistema atualiza a lista exibida

---------------------------------------------------------------------------------------------------
📷 Protótipo

O protótipo foi desenvolvido no Figma e inclui:

-Tela inicial

-Tela de cadastro

-Lista de tarefas

-Pomodoro

🔗 (https://www.figma.com/proto/BWURP4ijdagguRCXLtP8v3/Tasks?node-id=367-33&starting-point-node-id=175%3A8)
