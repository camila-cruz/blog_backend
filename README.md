# Backend do Blog

## ❓ O que é?

É o backend do meu blog ainda não lançado! Provavelmente pode servir de base para outros blogs também.

## 🛠 Ferramentas

* Django
* Django REST Framework

## ☢ Como rodar?

Todos os comandos a seguir serão feitos no terminal. 
Primeiro, instale as dependências do projeto (de preferência, em um _virtual environment_, a famosa _venv_):

```s
$ pip install -r requirements.txt
```

Em seguida, crie um super usuário para acessar o painel de admin:
```s
$ python manage.py createsuperuser
```

Depois, faça as migrações do banco de dados para que as tabelas sejam criadas:
```s
$ python manage.py makemigrations
$ python manage.py migrate
```

Por fim, suba o servidor e acesse a url `http://localhost:8000/admin`. Para logar, use o e-mail e senha cadastrados no super usuário.
```s
$ python manage.py runserver
```