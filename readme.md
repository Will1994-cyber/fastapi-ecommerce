FastAPI Ecommerce - API de Estudo

Este é um projeto de API desenvolvido com [FastAPI](https://fastapi.tiangolo.com/) com fins educacionais e de portfólio.  
A aplicação simula um ponto de partida para um sistema de e-commerce com estrutura REST e documentação automática via Swagger.

Tecnologias Utilizadas

- [FastAPI](https://fastapi.tiangolo.com/)
- [Uvicorn](https://www.uvicorn.org/) como servidor ASGI
- Python 3.10+
- Git e GitHub

Estrutura do Projeto

ecommerce-api/
	main.py # Ponto de entrada da aplicação
	venv/ # Ambiente virtual (ignorado pelo Git)
 	requirements.txt # Dependências do projeto
 	README.md

1. Clone o repositório:

git clone https://github.com/Will1994-cyber/fastapi-ecommerce.git
cd fastapi-ecommerce

2. Crie e ative o ambiente virtual:

python -m venv venv
# Ativar:
# No Windows:
venv\Scripts\activate
# No Linux/Mac:
source venv/bin/activate

3. Instale as dependências:

pip install fastapi uvicorn

4. Execute o servidor:

uvicorn main:app --reload

5. Acesse a documentação interativa:

Swagger: http://127.0.0.1:8000/docs

Redoc: http://127.0.0.1:8000/redoc

Desenvolvido por Willians Santana
Conecte-se comigo no LinkedIn (https://www.linkedin.com/in/willians-santana-oliveira/) ou aqui pelo GitHub.

Sinta-se à vontade para contribuir, estudar ou adaptar este projeto.