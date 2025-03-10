## Requistos

* Python 3 ou superior - Conferir a versão: python --version
* Django 5 ou superior - Conferir a versão: django-admin --version
* GIT - Conferir a instalação: git -v

## Sequencia para criar o projeto

Instalar o Django.
```
pip install Django
```

Desinstalar o Django.
```
pip uninstall Django
```

Criar o projeto com Django.
```
django-admin startproject admin .
```

Rodar o projeto.
```
python manage.py runserver
```

meu_projeto/<br>
│<br>
├── manage.py              # Ferramenta CLI para gerenciar o projeto<br>
├── meu_projeto/           # Diretório principal do projeto<br>
│   ├── __init__.py        # Identifica o diretório como um módulo Python<br>
│   ├── settings.py        # Configurações do projeto<br>
│   ├── urls.py            # Rotas principais do projeto<br>
│   ├── asgi.py            # Configuração para ASGI<br>
│   └── wsgi.py            # Configuração para WSGI<br>

Executa as migration.
```
python manage.py migrate
```

## Como usar o GitHub

Baixar os arquivos do GitHub.
```
git clone -b <branch_nome> <repositorio_url> .
```

Verificar a branch.
```
git branch
```

Baixar as atualizações.
```
git pull
```

Adicionar todos os arquivos modificados para staging area - área de preparação.
```
git add .
```

commit representa um conjunto de alterações em um ponto específico da história do seu projeto, registra apenas as alterações adicionadas ao índice de preparação.
O comando -m permite que insira a mensagem de commit diretamente na linha de comando.
```
git commit -m "Descrição do commit"
```

Enviar os commits locais, para um repositório remoto.
```
git push <remote> <branch>
git push origin develop

Remover o cach 
```
git rm --cached db.sqlite3
```