# mecajado

## Configuração

* Crianção do projeto com o **Django**

1. Criar o ambiente virtual do Python

```python
# Linux
python3 -m venv venv
```

2. Inicializar o ambiente virtual

```python
# Linux
source venv/bin/activate
```

3. Instalar o **DJango**

```python
# Linux
pip install django==4.1.1
```

4. Criar o projeto inicial

```python
# Linux
django-admin startproject mecajado .
```

### Cliente

1. Criação do APP de cliente

```python
# Linux
python3 manage.py startapp cliente
```

2. Inicializando o servidor

```python
# Linux
python3 manage.py runserver
```
 
* URL Clientes

```
http://127.0.0.1:8000/clientes/
```
