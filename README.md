📚 Escola Backend Django

Este é um projeto de backend desenvolvido com Django e Django REST Framework para gerenciar recursos relacionados a uma escola, como cursos e alunos. O objetivo principal é fornecer uma API RESTful para cadastro, consulta e gerenciamento de dados educacionais.
🚀 Tecnologias Utilizadas

    Python 3.13

    Django

    Django REST Framework

    SQLite (banco de dados padrão)

    Virtualenv

✅ Funcionalidades

    CRUD de Cursos.

    CRUD de Alunos.

    Endpoints RESTful.

    Interface administrativa do Django.

    Serialização de dados com DRF.

    Organização em apps e uso de ViewSets.

⚙️ Pré-requisitos

    Python 3.x instalado.

    Git instalado.

    Virtualenv (recomendado).

💻 Como executar o projeto
1. Clone o repositório:

git clone https://github.com/MikaelReis/escola_backend_django.git
cd escola_backend_django

2. Crie e ative o ambiente virtual:

Windows:

python -m venv venv
venv\Scripts\activate

Linux/Mac:

python3 -m venv venv
source venv/bin/activate

3. Instale as dependências:

pip install -r requirements.txt

Se ainda não tiver um arquivo requirements.txt, posso te ajudar a gerar com o comando:

pip freeze > requirements.txt

4. Realize as migrações do banco de dados:

python manage.py makemigrations
python manage.py migrate

5. Crie um superusuário (opcional, mas recomendado):

python manage.py createsuperuser

6. Inicie o servidor de desenvolvimento:

python manage.py runserver

Acesse: http://127.0.0.1:8000/
