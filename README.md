# <b>_CRUD em Python e Django - MedicalSys_</b>
 
CRUD em Python e Django contendo nome, telefone, endereço, CPF, entre outros.

Feature: 

- Máscara no telefone e CPF.

----------------------
# <b>_Instalação_</b>
----------------------

Para instalar o Django e criar o projeto foram utilizados os seguintes comandos:

    mkdir django_project
    
    cd django_project
    
    python -m venv venv_serviceNet
    
    set-executionpolicy remotesigned
    
    venv_serviceNet\Scripts\activate
    
    C:\Users\vitor\django_project\venv_serviceNet\Scripts\python.exe -m pip install --upgrade pip
    
    pip3 install django
    
    django-admin startproject serviceNet
    
    cd serviceNet
    
    python manage.py migrate
    
    python manage.py createsuperuser
    
    python manage.py runserver
    
    --Alterar idioma   
    
    --Abrir outro terminal
    
    1) cd django_project
    
    2) venv_serviceNet\Scripts\activate
        
    3) cd serviceNet
    
    4) django-admin startapp sample
        
    --Criar classe Cliente
        
    1) python manage.py makemigrations
    
    2) python manage.py migrate
    
    --Executar a aplicação
    
    1) cd django_project
    
    2) venv_serviceNet\Scripts\activate

    3) cd serviceNet

    4) python manage.py runserver
    
    --Logar na aplicação
    
    1) Acessar: http://localhost:8000/admin/
    
    2) Logar com:
    
    usuário: admin
    senha: admin

    
    
    
    
 
    
 
    
