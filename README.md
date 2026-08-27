python -m venv venv -> Criar máquina virtual
.\venv\Scripts\activate -> Ativar a máquina virtual
pip install -r requirements.txt -> Reinstalar bibliotecas
uvicorn main:app --reload -> Rodar servidor
localhost:8000/docs -> Abrir a documentação
pip freeze > requirements.txt -> Atualizar requirements


# 1) Entrar na pasta do projeto
cd api-produtos

# 2) Ativar o ambiente virtual
venv\Scripts\activate      # Windows
source venv/bin/activate   # Linux/Mac

# 3) Instalar as bibliotecas desta aula
pip install pytest httpx