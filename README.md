# Django-Mecajato do Pythonando

```
    # Criar ambiente virtual:
    python -m venv .venv (ex.: python -m venv .venv)

Projeto baseado no vídeo da aula: 
    -> Desenvolvendo uma APLICAÇÃO pra OFICINAS E LAVA JATOS com Python e Django | MECAJATO #01
    -->> https://youtu.be/pNlHlhWDpV0?t=4597
    
    http://localhost:8080/clientes

```


```
.venv\Scripts\activate
 
```



## 1º passo: Criar ambiente e criar projeto.
```
    # Atualiza pip:
        python.exe -m pip install --upgrade pip
        

    # Instala o Django: 
        pip install django

    # Cria o projeto Django (o ponto no final da linha é para não criar varias pastas):
        django-admin startproject mecajato .

    # 
        python manage.py createsuperuser

    # Cria o App  
        python manage.py startapp clientes  

```

## 2º passo: Fatiar o problema

### - 1.Resolver a gestão de clientes.

### - 2.Resolver a gestão de carros.



### - Paefetivar as alterações nos Objetos / Dados no banco precisamos rodar os comandos:
```
    # Create the migrations:
    python manage.py makemigrations

    # Release the migrations:
    python manage.py migrate

```


### - Rodar o servidor:
```
    # Ativar o venv
    .venv\Scripts\activate


    # Rodar o servidor Django.
    python manage.py runserver
```
