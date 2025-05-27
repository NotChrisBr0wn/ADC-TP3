🍽️ Food Timer App Aplicação web desenvolvida com Flask para gerenciamento de alimentos e controle de temporizadores personalizados.

📌 Sobre o Projeto Este projeto é uma interface web simples, construída com Flask, que permite aos usuários:

Criar, listar e deletar alimentos

Associar temporizadores aos alimentos

Visualizar alimentos por usuário

Organizar tarefas relacionadas à cozinha ou controle de preparo

A aplicação é modularizada, separando claramente configuração, lógica de rotas, templates HTML e arquivos estáticos.

🚀 Tecnologias Utilizadas Python 3.x

Flask

HTML5

CSS3

JavaScript (Jquery)

⚙️ Funcionalidades

📄 Página inicial: lista os alimentos cadastrados

➕ Criação de alimentos: formulário para adicionar novos alimentos

⏱️ Temporizadores: crie e visualize timers vinculados a alimentos

🧑 Visualização por usuário: lista alimentos de um usuário específico

🗑️ Remoção de alimentos: interface para deletar itens cadastrados

🧩 Organização Modular

app.py: Responsável por gerenciar rotas, lógica de negócio e renderização. config/: Define parâmetros globais e gerencia a conexão com o banco de dados. templates/: Contém todos os arquivos HTML com componentes reutilizáveis. static/assets/: Estilos CSS, scripts JavaScript e imagens organizados por tipo.