## Django Task Manager

Este é o repositório do projeto Django Task Manager, que é parte do meu portfólio de desenvolvimento. O projeto consiste em um sistema de cadastro e gestão de tarefas, onde os usuários podem criar, atualizar, deletar e visualizar suas tarefas.

### Tecnologias Utilizadas

- Django: Um framework web em Python para desenvolvimento rápido e limpo.
- SQLite3: Um banco de dados leve e fácil de usar, perfeito para desenvolvimento e prototipagem.
- Decouple: Uma biblioteca Python para carregar variáveis de ambiente de forma segura.
- Dj Database: Uma ferramenta para simplificar a configuração do banco de dados no Django.
- Bootstrap: Um framework de front-end para desenvolvimento web responsivo e fácil.

### Instalação

1. Clone o repositório para o seu ambiente de desenvolvimento:

```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
```

2. Navegue até o diretório do projeto:

```bash
cd nome-do-repositorio
```

3. Instale as dependências do projeto:

```bash
pip install -r requirements.txt
```

4. Execute as migrações do banco de dados:

```bash
python manage.py migrate
```

5. Inicie o servidor de desenvolvimento:

```bash
python manage.py runserver
```

6. Acesse o projeto em seu navegador web em [http://localhost:8000/](http://localhost:8000/)

```note
Obs: é importante criar o arquivo .env com as configurações locais do projeto como o secret key e hosts de acesso.
```

### Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
