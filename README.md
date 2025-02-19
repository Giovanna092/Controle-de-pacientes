# Gerenciador de Pacientes - Django

Este projeto é uma aplicação web desenvolvida em Django para gerenciar pacientes, consultas e tarefas relacionadas ao atendimento psicológico. Ele permite cadastrar pacientes, registrar consultas, associar tarefas e visualizar estatísticas.

## 🚀 Funcionalidades
- Cadastro de pacientes com foto e informações pessoais.
- Registro de consultas com humor, anotações e vídeos.
- Associação de tarefas recorrentes aos pacientes.
- Controle de pagamento dos pacientes.
- Contagem de visualizações das consultas públicas.
- Gráficos de humor ao longo das consultas.

## 🛠️ Tecnologias Utilizadas
- **Django** - Framework web em Python.
- **SQLite** - Banco de dados padrão do Django.
- **Bootstrap** - Para estilização da interface.
- **Chart.js** - Para visualização de gráficos de humor.

## 📦 Instalação
### 1. Clone o repositório:
```bash
git clone https://github.com/Giovanna092/Controle-de-pacientes.git
cd Controle-de-pacientes
```
### 2. Crie e ative um ambiente virtual:
```bash
python -m venv venv  # Criar ambiente virtual
source venv/bin/activate  # Ativar no Linux/macOS
venv\Scripts\activate  # Ativar no Windows
```
### 3. Instale as dependências:
```bash
pip install -r requirements.txt
```
### 4. Realize as migrações do banco de dados:
```bash
python manage.py migrate
```
### 5. Execute o servidor local:
```bash
python manage.py runserver
```
Acesse no navegador: `http://127.0.0.1:8000/`

## 📝 Estrutura do Projeto
```
📂 Controle-de-pacientes
 ├── 📂 pacientes  # Aplicação principal
 │   ├── 📂 migrations  # Arquivos de migração do banco de dados
 │   ├── 📂 static  # Arquivos CSS, JS e imagens
 │   ├── 📂 templates  # Páginas HTML
 │   ├── admin.py  # Configuração do Django Admin
 │   ├── models.py  # Modelos do banco de dados
 │   ├── views.py  # Lógica das requisições
 │   ├── urls.py  # Rotas da aplicação
 ├── manage.py  # Comando para gerenciar o Django
 ├── db.sqlite3  # Banco de dados SQLite
 ├── requirements.txt  # Dependências do projeto
 └── README.md  # Documentação do projeto
```

## 📌 Como Contribuir
1. Faça um fork do repositório.
2. Crie uma branch com sua feature (`git checkout -b minha-feature`).
3. Faça commit das suas alterações (`git commit -m 'Adiciona nova funcionalidade'`).
4. Envie para o repositório remoto (`git push origin minha-feature`).
5. Abra um Pull Request.


