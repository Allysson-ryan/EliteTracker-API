# EliteTracker API

Bem-vindo ao repositório da **EliteTracker API**! Esta é a API que alimenta o **EliteTracker-interface**, um aplicativo desenvolvido para monitorar hábitos diários e ajudar na gestão de produtividade.

> **Nota**: Essa api foi desenvolvida com o objetivo de ser utilizado com o frontend **EliteTracker Interface**.

<br/>

### Link do Front-end: https://github.com/Allysson-ryan/EliteTracker-interface

<br/>

## 🔧 Funcionalidades

- CRUD completo para gerenciamento de hábitos
- Autenticação JWT para segurança
- Validação de dados com Zod
- Integração com banco de dados MongoDB
- Configuração de variáveis de ambiente com dotenv
- Middleware para tratamento de erros

<br/>

## 💡 Tecnologias Utilizadas

- TypeScript
- Express.js
- MongoDB (via Mongoose)
- JWT para autenticação
- Zod para validação de dados
- Day.js para manipulação de datas
- Docker para conteinerização do ambiente

<br/>

## 🔄 Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/Allysson-ryan/elitetracker-api.git
   cd elitetracker-api
   ```

2. Instale as dependências:

   ```bash
   npm install
   ```

3. Configure o arquivo `.env` com suas variáveis de ambiente:

   ```bash
   PORT=3000
   MONGO_URI=your_mongo_connection_string
   JWT_SECRET=your_jwt_secret
   ```

4. Inicie o servidor em modo desenvolvimento:

   ```bash
   npm run dev
   ```

<br/>

## 🌍 Endpoints Principais

- `POST /login` - Login do usuário
- `POST /habits` - Criar novo hábito
- `GET /habits` - Listar todos os hábitos
- `PUT /habits/:id` - Atualizar hábito
- `DELETE /habits/:id` - Remover hábito
