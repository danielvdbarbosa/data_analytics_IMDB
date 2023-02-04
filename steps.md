### Documentação de passo a passo de criação do ambiente

#### 1. Ambiente:
- Python 3.11.1
- VSCode

---
#### 2. Bibliotecas:
- jupyter
- numpy
- pandas

---
#### 3. Criação do Virtual Environment (Ambiente Virtual)
O comando a seguir cria um ambiente virtual para a instalação de bibliotecas de forma isolada (Não afeta o python instalado no PC) 
```bash
$ python -m venv .env
```

Descrição do comando:
python: chamada do Python na linha de comando
-m = Invoca um módulo instalado do Python (Geralmente instalado via pip)
venv = **V**irtual **env**ironment, ambiente virtual, é um módulo do python que já vem built-in ("nativo" do python)
.env = nome do virtual environment.

---
#### 4. Instalação das bibliotecas
Após a criação do ambiente virtual, é necessário ativar o ambiente caso não esteja no VSCode (No VSCode este processo é automático):
```bash
$ .\.env\Scripts\Activate.ps1
```
Para a instalação das bibliotecas utilizadas, segue o comando
```bash
$ pip install numpy pandas jupyter matplotlib
```

---
