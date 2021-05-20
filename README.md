# 21-mai-twtim

## My Site - Item Lins 

## Este projeto foi feito com:

* Python 3.8.6
* Django 2.2.12

## Como rodar o projeto?

* Clone esse repositório.
* Crie um virtualenv com Python 3.
* Ative o virtualenv.
* Instale as dependências.
* Rode as migrações.

```
git clone https://github.com/rg3915/pizza.git
cd pizza
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python contrib/env_gen.py
python manage.py migrate
