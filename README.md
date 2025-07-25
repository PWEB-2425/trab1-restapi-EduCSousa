Projeto de Gestão de Alunos
Eduardo Sousa — Nº31658
Projeto final da unidade curricular de Programação Web.

Este projeto permite a gestão de alunos e cursos com uma interface simples, conectada a uma API RESTful desenvolvida em Node.js com base de dados MongoDB. Inclui funcionalidades completas de criação, leitura, atualização e eliminação (CRUD) de dados de alunos, bem como listagem de cursos. O frontend comunica com a API real através de fetch e encontra-se igualmente publicado.

Deploys
Frontend (Vercel): https://projeto-raiz.vercel.app
Backend (Render): https://projeto-raiz-backend.onrender.com

Estrutura do Projeto
O projeto está organizado da seguinte forma:

/frontend — Interface web em HTML, CSS e JavaScript puro

/backend — API desenvolvida com Node.js, Express e MongoDB (Mongoose)

/mock-server — API simulada utilizando JSON-server para testes iniciais

/mock-data — Dados JSON de alunos e cursos

/tests — Coleção Postman com testes da API

README.md — Este ficheiro com todas as instruções

.gitignore, vercel.json, package.json, etc.

Funcionalidades
Listar, criar, editar e eliminar alunos

Listar cursos disponíveis

Interface simples e funcional em HTML/CSS

Ligação completa com API real

Base de dados MongoDB online

Testes com Postman

Deploy final em Vercel (frontend) e Render (backend)

Tecnologias Utilizadas
HTML, CSS, JavaScript (frontend)

Node.js, Express, MongoDB e Mongoose (backend)

dotenv, cors, fetch

Postman

Vercel (para frontend)

Render (para backend)

Instruções para Execução Local
Clonar o repositório:
git clone https://github.com/teu-utilizador/projeto-raiz.git
cd projeto-raiz

Entrar na pasta do backend e instalar dependências:
cd backend
npm install

Criar um ficheiro .env com o seguinte conteúdo:

ini
Copiar
Editar
MONGODB_URI=mongodb+srv://<utilizador>:<palavra-passe>@<cluster>.mongodb.net/escola
PORT=3000
Correr o servidor:
npm start

Abrir o ficheiro frontend/index.html num navegador ou usar o link do Vercel para a versão online.

Notas Finais
O servidor backend precisa estar em execução (Render ou localmente) para que a interface funcione corretamente. Todos os dados de cursos e alunos ficam gravados na base de dados online do MongoDB Atlas.

Autor
Eduardo Sousa
Nº 31658 — Programação Web 2024/25
