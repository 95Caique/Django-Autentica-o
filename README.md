Use a branch Master

Projeto de autenticação Django bem simples, para executar siga os comandos a seguir:

1 - Clone o repostório

2 - Navegue até a pasta do projeto com cd django_autenticacao

3 - Crie seu ambiente virtual (venv) para instalar os pacotes:
Linux - python3 -m venv venv
Ative com: source venv/bin/activate

Windows - python3 -m venv venv
ative com: venv\Scripts\activate
se estiver assim (venv) está ativada, pode instalar os requirements nesse ambiente criado

4 - Instale os requirements com a venv ativa (venv) com o comando pip install -r requirements.txt

5 - Execute o comando python manage.py makemigrations e python manage.py migrate para executar as migrações
e popular o banco de dados, em seguida execute com python manage.py runserver.

Ao executar o projeto, esta deverá ser a página inicial:
![1](https://github.com/user-attachments/assets/78d8f570-731c-497a-9e38-b4b82dfa0beb)

Clique em Registrar e crie sua conta:
![2](https://github.com/user-attachments/assets/a06d11f2-5315-4458-a041-14000dcc5344)

Conta criada, coloque seu usuário e senha para logar:
![3](https://github.com/user-attachments/assets/c4c9ac3d-f8a4-434e-b629-db469de3d202)

E por fim, autenticação feita e como podemos observar, o usuário está autenticado.
Clique em Sair para fazer deslogar da página.
![4](https://github.com/user-attachments/assets/5b390406-150f-48f8-8dfc-4de1af998b60)
