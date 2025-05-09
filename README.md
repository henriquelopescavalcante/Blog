📝 Blog

Aplicação web para criação e gerenciamento de posts em um blog, desenvolvida com Django. Este projeto visa demonstrar habilidades no desenvolvimento de sistemas de conteúdo dinâmico e a implementação de funcionalidades básicas de CRUD (Create, Read, Update, Delete).

🧭 Visão Geral

Este sistema permite:

- Cadastro de posts de blog (título, conteúdo, data de criação)
- Edição e exclusão de posts
- Visualização de posts com detalhes (título, conteúdo e data)
- Listagem de todos os posts com ordenação por data de criação

O projeto segue uma estrutura simples e limpa, ideal para demonstrar a implementação de um sistema de blog com Django, usando recursos como `models`, `views`, `forms`, `templates`, e `urls`.

🛠️ Tecnologias

- **Linguagem:** Python 3
- **Framework:** Django 4
- **Banco de Dados:** SQLite (padrão do Django)
- **Template Engine:** Django Templates
- **Estilização:** Bootstrap (para layout responsivo)

📂 Estrutura do Projeto

blog/
├── blog/ # Aplicação principal com models, views e templates
├── blog_project/ # Configurações globais do projeto Django
├── static/ # Arquivos estáticos (CSS, JS, etc.)
├── templates/ # Templates HTML reutilizáveis
├── db.sqlite3 # Banco de dados SQLite
└── manage.py # Interface de gerenciamento do Django


🚀 Como Executar Localmente

1. Clone o repositório:
git clone https://github.com/henriquelopescavalcante/Blog.git
cd Blog

Crie um ambiente virtual:
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

Instale as dependências:
pip install -r requirements.txt

Execute as migrações e rode o servidor:
python manage.py migrate
python manage.py runserver

Acesse no navegador:
http://127.0.0.1:8000/

🎯 Objetivo do Projeto
O objetivo deste projeto é demonstrar as habilidades de desenvolvimento backend com Django, implementação de sistemas de conteúdo dinâmico, e as melhores práticas de organização de código para manutenção e escalabilidade. O sistema segue o padrão Model-Template-View (MTV) e pode ser facilmente expandido para incluir novas funcionalidades como comentários e categorias de posts.

👨‍💻 Autor
Desenvolvido por Henrique Lopes
https://github.com/henriquelopescavalcante | https://www.linkedin.com/in/henriquelopescs/
