Iniciar o projeto Django

```
python -m venv venv
.\venv\Scripts\\Activate.ps1
pip install django
django-admin startproject project .
python manage.py startapp contact
```

Configurar o git

```
git config --global user.name 'Seu nome'
git config --global user.email 'seu_email@gmail.com'
git config --global init.defaultBranch main

# Configure o .gitignore

git init
git add .
git commit -m 'Mensagem'
git remote add origin https://github.com/Thiago-sa/agenda.git
```