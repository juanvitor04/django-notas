# 🚀 Guia de Instalação do Projeto Python (com venv)

Este documento explica como instalar e executar um projeto Python em qualquer máquina usando um ambiente virtual (venv).

---

## 📦 Pré-requisitos

Antes de começar, certifique-se de ter instalado:

- Python 3.10+
- Git

Para verificar:
```bash
python3 --version
git --version
``


---

## 🧱 2. Criar o ambiente virtual (venv)

python3 -m venv venv


Isso criará uma pasta chamada `venv` com um ambiente virtual isolado.

---

## ▶️ 3. Ativar o ambiente virtual

### Linux / macOS

source venv/bin/activate

### Windows (PowerShell)

venv\Scripts\Activate

Se der certo, o nome `(venv)` aparecerá no início da linha do terminal.

---

## 📦 4. Instalar as dependências

Se existir um arquivo `requirements.txt` no projeto:

pip install -r requirements.txt


---

## ▶️ 5. Executar o projeto

python manage.py migrate
python manage.py runserver



