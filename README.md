# Tasks

DESCRIÇÃO

Ferramenta prática que ajudará o usuário a manter o controle de suas atividades, promovendo maior produtividade e organização pessoal por meio de uma navegação simples e objetiva.

---------------------------------------------------------------------------------------------------
🎯 Objetivo

Este projeto tem como objetivo desenvolver uma aplicação de lista de tarefas voltada para pessoas com Transtorno de Déficit de Atenção e Hiperatividade (TDAH), priorizando simplicidade, clareza e facilidade de uso. A proposta busca não apenas atender às necessidades básicas de organização de tarefas, mas também oferecer uma experiência que reduza distrações e ajude o usuário a manter o foco em suas atividades diárias.

---------------------------------------------------------------------------------------------------
🚧 Status do Projeto

O projeto encontra-se em fase de planejamento e prototipação.
A implementação do código será realizada nas próximas etapas.

---------------------------------------------------------------------------------------------------
🏗️ Arquitetura

O sistema será desenvolvido com base na arquitetura cliente-servidor, na qual o front-end (cliente) é responsável por capturar as interações do usuário e enviar requisições HTTP ao back-end (servidor). O servidor, por sua vez, processa essas requisições, aplica as regras de negócio e realiza a comunicação com o banco de dados, retornando respostas ao cliente de forma organizada e eficiente.
Além disso, a aplicação seguirá o padrão de arquitetura em camadas, promovendo uma melhor organização do código, facilidade de manutenção e escalabilidade. Essa divisão será estruturada da seguinte forma:


- Camada de Apresentação, desenvolvida com HTML, CSS e JavaScript, será responsável pela interface com o usuário. Nela, o usuário poderá visualizar suas tarefas, adicionar novas atividades, marcar como concluídas e excluir itens. O foco dessa camada será proporcionar uma experiência intuitiva, responsiva e visualmente limpa.

- Camada de Lógica, implementada em PHP, será responsável por processar as requisições recebidas do front-end. Nessa camada serão aplicadas as regras de negócio, como validação de dados, controle das tarefas (criar, listar, atualizar e excluir) e tratamento de possíveis erros, garantindo o correto funcionamento da aplicação.

- Camada de Dados, utilizando MySQL, será encarregada do armazenamento e gerenciamento das informações. Ela manterá os registros das tarefas, incluindo seus estados (concluída ou pendente), permitindo consultas rápidas e seguras. Essa separação garante maior integridade dos dados e facilita futuras modificações na estrutura do banco.
Com essa abordagem, o sistema se torna mais organizado, modular e preparado para futuras evoluções, além de facilitar o trabalho em equipe e a manutenção do projeto.


---------------------------------------------------------------------------------------------------
🛠️ Tecnologias Utilizadas

HTML,CSS e Js(futuro)

PHP(futuro)

SQL(futuro)

Figma

Google Docs

GitHub

Canva

Flaticon

Draw.io

DBdesigner 4

Trello
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
