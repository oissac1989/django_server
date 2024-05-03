# Django Server


## Criação do ambiente virtual
    
```bash
sudo apt install python3-venv

python3 -m venv .venv

source .venv/bin/activate
```


## Instalação do Django

```bash
pip install django
```

Criação do projeto Django

```bash
django-admin startproject setup .
```

Criação de um novo app (nesse caso o "todos")

    python3 manage.py startapp todos

Criação de migrate de um novo APP (deve ser executado sempre que um novo model for criado)

    python3 manage.py makemigrations

Criação de tabelas

    python3 manage.py migrate

Iniciar o server Django

    python3 manage.py runserver

Configuração basicas usadas neste projeto (/setup/settings.py)

    LANGUAGE_CODE = 'pt-br'

    TIME_ZONE = 'America/Sao_Paulo'

Lista de time zone Djnago: https://github.com/guilhermeonrails/language_code_django/blob/tz_list/list.py

## Instalação do DB SQLite3

sudo apt -y install sqlite3

## Lib Decouple

Instalação

    pip install python-decouple

## Lib DJ Database

Instalação

    pip install dj-database-url


## Bootstrap - Framework de Estilização

Integração com o Django

    pip install crispy-bootstrap5