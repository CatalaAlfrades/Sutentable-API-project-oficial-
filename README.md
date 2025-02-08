🌱 API RESTful para Ações Sustentáveis (ODS 12)

Este projeto é uma API RESTful que incentiva ações sustentáveis alinhadas ao ODS 12 (Consumo e Produção Sustentáveis) da ONU. Usuários podem registrar ações ecológicas, acumular pontos e visualizar suas contribuições para um mundo mais sustentável. 🚀🌍

📌 Funcionalidades

✅ Autenticação JWT (Login e Registro)✅ CRUD de Ações Sustentáveis (Criar, Ler, Atualizar e Deletar)✅ Sistema de Pontuação baseado em impacto ambiental✅ Interface Web Simples para testes e interações

🛠️ Tecnologias Utilizadas

Backend: Node.js, Express.js, MongoDB Atlas

Frontend: HTML, CSS, JavaScript (Fetch API)

Autenticação: JSON Web Token (JWT)

Hospedagem: Railway/Render (backend), Vercel/Netlify (frontend)

🚀 Como Rodar o Projeto

🔧 Configuração Inicial

Clone o repositório:

git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio

Instale as dependências:

npm install

Crie um arquivo .env e configure suas variáveis de ambiente:

MONGO_URI=sua_string_de_conexao_mongodb
JWT_SECRET=seu_segredo_super_seguro

Inicie o servidor:

npm start

Acesse a API em http://localhost:5000

🖥️ Testando o Frontend

Navegue até a pasta frontend:

cd frontend

Abra index.html no navegador ou utilize um servidor local como o VS Code Live Server.

📡 Rotas da API

🔑 Autenticação

POST /api/auth/register → Criar conta

POST /api/auth/login → Fazer login

🌍 Ações Sustentáveis

POST /api/actions → Registrar uma ação

GET /api/actions → Listar ações

PUT /api/actions/:id → Atualizar uma ação

DELETE /api/actions/:id → Remover uma ação

🌍 Como Contribuir

Faça um fork do repositório.

Crie uma branch com sua funcionalidade (git checkout -b minha-feature).

Faça commit das suas alterações (git commit -m 'Minha nova feature').

Faça um push para a branch (git push origin minha-feature).

Abra um Pull Request 🚀.

📄 Licença

Este projeto está sob a MIT License - sinta-se livre para utilizá-lo e contribuir! 💚

