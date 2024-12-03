# Projeto DJANGO - SGE (Sistema de Gerenciamento de Estoque)

- criar diretório do projeto
- instalar ambiente virtual
- ativar ambiente virtual
- instalar django
- criar o projeto django-admin startproject app . 
- python manage.py migrate
- python manage.py createsuperuser
- python manage.py runserver
- python manage.py startapp <'nome_da_app'>
- configurar a app no installed apps do settings.py
- criar os models
- python manage.py makemigrations
- python manage.py migrate
- criar a pasta templates dentro da psta principal do projeto
- settings.py TEMPLATES: 'DIRS': ['app/templates']
- criar arquivo urls.py dentro de cada app e configurar o include no arquivo urls.py dentro da pasta do projeto