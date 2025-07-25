<!-- Selececione os Badges que preferir -->

[REACT__BADGE]: https://img.shields.io/badge/React-005CFE?style=for-the-badge&logo=react
[TYPESCRIPT__BADGE]: https://img.shields.io/badge/typescript-D4FAFF?style=for-the-badge&logo=typescript
[ANGULAR__BADGE]: https://img.shields.io/badge/Angular-red?style=for-the-badge&logo=angular
[EXPRESS__BADGE]: https://img.shields.io/badge/express-005CFE?style=for-the-badge&logo=express
[NEST__BADGE]: https://img.shields.io/badge/nest-7026b9?style=for-the-badge&logo=nest
[GRAPHQL__BADGE]: https://img.shields.io/badge/GraphQL-e10098?style=for-the-badge&logo=graphql
[AWS_BADGE]: https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white
[SPRING_BADGE]: https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white
[JAVA_BADGE]: https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white
[MONGO_BADGE]: https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white



<h1 align="center" style="font-weight: bold;">Nome do Projeto 💻</h1>

<!-- Selececione os Badges que preferir -->

![react][REACT__BADGE]
![typescript][TYPESCRIPT__BADGE]
![angular][ANGULAR__BADGE]
![express][EXPRESS__BADGE]
![nest][NEST__BADGE]
![graphql][GRAPHQL__BADGE]
![AWS][AWS_BADGE]
![spring][SPRING_BADGE]
![java][JAVA_BADGE]
![mongo][MONGO_BADGE]



<p align="center">
    
<!-- Substitua essa imagem pela logo do seu projeto -->

<img src="./img/logo-comp.png" alt="logo" width="400" height="70">

</p>
    <p align="center"></p>
     <a href="#about">Visão Geral</a> • 
     <a href="#tech">Tecnologias Utilizadas</a> • 
     <a href="#timeline">Cronograma</a> • 
     <a href="#Squad">Squad de Desenvolvimento</a> • 
     <a href="#client">Cliente</a> • 
     <a href="#prerequisites">Pré-Requisitos</a> • 
     <a href="#started">Como executar o Projeto</a> • 
     <a href="#deploy">Deploy</a> • 
     <a href="#routes">Rotas da Aplicação(FrontEnd)</a> • 
     <a href="#endpoints">Endpoints da API</a> •
     <a href="#structure">Estrutura do Projeto</a> •
     <a href="#diagrams">Diagramas do Projeto</a> •
     <a href="#model">Modelo de Entidade Relacionamento</a> •
     <a href="#doc">Documentação </a> •
     <a href="#contribute">Como Contribuir</a> •
     <a href="#add">Informações Adicionais</a> 
    </p>


<h2 id="about">🌐 Visão Geral</h2>

<!-- Substitua este texto com a descrição do seu projeto -->

Escreva uma descrição simples sobre o projeto.


<h2 id="tech">💻 Tecnologias Utilizadas</h2>

<!-- Substitua -->

- Front-end: Next.js (React)
- Back-end: Node.js + Fastify
- Banco de Dados: PostgreSQL + Prisma
- Autenticação: Keycloak
- Mensageria: Kafka ou RabbitMQ
- Containerização: Docker + Docker Compose

<h2 id="timeline">📆 Cronograma</h2>

<!-- Substitua -->

- **Data de Início:** 05/06/2025  
- **Data de Conclusão:** 02/07/2025  
- **Duração Total:** 4 semanas
  
<h2 id="Squad">👨‍💻 Squad de Desenvolvimento</h2>

<!-- Substitua -->

**Squad:** Squad CompJr / Turma 05
  
<h3 id="colab">🤝 Desenvolvedores</h3>

<table>
  <tr>
    <td align="center">
      <a href="#">
        <img src="https://miro.medium.com/max/360/0*1SkS3mSorArvY9kS.jpg" width="100px;" alt="Foto do Steve Jobs"/><br>
        <sub>
          <b>Steve Jobs - Front-End</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

<h2 id="client">📋 Cliente </h2>

<!-- Substitua -->

- **Nome:** João Carlos (Imobiliária AlugMais)
- **Contato:** (31) 99999-9999 / joao.alugmais@email.com

<h2 id="prerequisites">📦 Pré-requisitos</h2>

<!-- Substitua  -->

Liste todos os pré-requisitos necessários para executar seu projeto. Por exemplo:

- [NodeJS](https://github.com/)
- [Git 2](https://github.com)

<h2 id="started">🚀 Como Executar o Projeto</h2>

<!-- Substitua -->

Descreva como executar seu projeto localmente. Exemplo:

1. **Clone o repositório**:

```bash
git clone https://github.com/JoseJaan/ToDoList-Zetta
cd ToDoList-Zetta
```

2. **Instale as dependências**:
```bash
npm install
cd frontend
npm install
```

3. **Arquivo .env**:
- Na raíz do projeto, crie um arquivo .env e adicione os valores com base na tabela abaixo

4. **Execute o projeto**:
- Back end:
```bash
npm run dev
```
ou
```bash
docker-compose up --build
```
- Front end:
```bash
cd frontend
npm run dev
```

5. **Testes**:
```bash
npm run test
```
O back end é executado em `http://localhost:3000` e o front end em `http://localhost:3001`.


<h2 id="deploy">📌 Deploy</h2>

<!-- Substitua -->

- **Frontend:** https://meu-projeto-front.vercel.app
- **Backend/API:** https://meu-projeto-api.onrender.com
- **Documentação da API:** https://documentacao-api.exemplo.com

<h2 id="routes">📮 Rotas da Aplicação (Front-end)</h2>

<!-- Substitua -->

Liste as principais rotas da sua API e quais são os corpos de requisição esperados. Exemplo:
​
| rota                | descrição                                           
|----------------------|-----------------------------------------------------
| <kbd>/authenticate</kbd>     | página que lista todas as informações do usuário
| <kbd>/login</kbd>     | página para login
| <kbd>/dashboard</kbd>     | página que contém todas as informações de compras e operações do usuário


<h2 id="Endpoints">🔌 Endpoints da API </h2>

<!-- Substitua -->

Aqui você pode listar os principais Endpoints da sua API e quais são os corpos de requisição esperados.
​
| rota                | descrição                                           
|----------------------|-----------------------------------------------------
| <kbd>GET /authenticate</kbd>     | recupera informações do usuário [response details](#get-auth-detail)
| <kbd>POST /authenticate-user </kbd>     | autentica o usuário na API  [request details](#post-auth-detail)

<h3 id="get-auth-detail">GET /authenticate</h3>

**RESPONSE**
```json
{
  "name": "Gustavo Magalhães",
  "age": 25,
  "email": "gemail@gmail.com"
}
```

<h3 id="post-auth-detail">POST /authenticate-user </h3>

**REQUEST**
```json
{
  "username": "joao123",
  "password": "4444444"
}
```

**RESPONSE**
```json
{
  "token": "OwoMRHsaQwyAgVoc3OXmL1JhMVUYXGGBbCTK0GBgiYitwQwjf0gVoBmkbuyy0pSi"
}
```

<h2 id="variables">:gear:Variáveis ​​de Ambiente</h2>

<!-- Substitua -->

Variáveis de ambiente são pares chave=valor que armazenam informações de configuração fora do código-fonte da aplicação. Exemplo:

| Variável  | Descrição                   | Valor Padrão   |
|-----------|----------------------------|---------------|
| DB_HOST   | Host do banco de dados  | -          |
| DB_USER   | User do banco de dados  | -         |
| DB_PASSWORD   | Senha do Mysql  | -          |
| DB_NAME   | Nome do banco no MySQL    | -   |
| JWT_SECRET   |  Chave JWT  | XXXXXXXXXXXXX     |
| JWT_EXPIRES_IN   | Validade JWT     | 24h            |
| GMAIL_USER   | Usuário google para envio de emails   | XXXXXXXXXXXXXX          |
| GMAIL_APP_PASSWORD   | Chave do google    | XXXXXXX    |
| CLOUDINARY_API_SECRET | Senha da API do Cloudinary    | XXXXXXXXXXX         |
| CLOUDINARY_CLOUD_NAME  | Nome da cloud no Cloudinary    | XXXXXXXXXXX          |
| CLOUDINARY_API_KEY   | Chave da API do Cloudinary    | XXXXXXXXXXXX       |
| FRONTEND_URL | Url Front  | XXXXXXXXXXX          |

<h2 id= "structure">📁 Estrutura do Projeto<h2>
    
<!-- Substitua este texto com a estrutura do seu projeto -->   

#Exemplo
    
```
├──frontend/
│   ├── public/ 
│   │ └── index.html # Porta de entrada da página
│   ├── src/ 
│   │ ├── components/ # Pastas com arquivos componentizados
│   │ │   ├── auth/ # Componentes de autenticação
│   │ │   ├── layout/ # Componentes de Header e Footer
│   │ │   └── tasks/ # Componentes de Tasks
│   │ ├── pages/ # Pastas com páginas
│   │ │   ├── DashboardPage.ts 
│   │ │   ├── ForgotPasswordPage.ts 
│   │ │   ├── LoginPage.ts 
│   │ │   ├── RegisterPage.ts 
│   │ │   └── ResetPasswordPage.ts
│   │ ├── services/ # Pastas com services
│   │ │   ├── AuthService.ts 
│   │ │   └── TaskService.ts
│   │ ├── styles/ # Estilos scss
│   │ │   ├── components
│   │ │   │  ├── _auth.scss
│   │ │   │  ├── _dashboard.scss
│   │ │   │  ├── _footer.scss
│   │ │   │  └── _header.scss
│   │ │   └── main.scss
│   │ ├── services/ # Pastas com definição das entidades
│   │ │   ├── Auth.ts 
│   │ │   └── Task.ts
│   │ ├── utils/ # Pasta com router
│   │ │   └── router.ts
│   │ └── main.ts # Porta de entrada da aplicação
│   ├── package-lock.json
│   └── package.json
├──src/
│   ├── config/ # Configurações de conexão com o banco de dados e Multer
│   ├── controllers/ # Pasta com controllers
│   │ ├── authController.ts
│   │ ├── taskController.ts
│   │ └── userController.ts
│   ├── middleware/ # Middleware de autenticação
│   │ └── authMiddleware.ts
│   ├── models/ # Entidades Sequelize
│   │ ├── index.ts
│   │ ├── PasswordReset.ts
│   │ ├── Task.ts
│   │ └── User.ts
│   ├── routes/ # Arquivos de rotas
│   │ ├── authRoutes.ts
│   │ ├── index.ts
│   │ ├── taskRoutes.ts
│   │ └── userRoutes.ts
│   ├── services/ # Pasta com services
│   │ ├── authService.ts
│   │ ├── cloudinaryService.ts
│   │ ├── emailService.ts
│   │ ├── taskService.ts
│   │ └── userService.ts
│   ├── utils/ # Pasta com validators
│   │ ├── authValidation.ts
│   │ ├── taskValidation.ts
│   │ └── userValidation.ts
│   └── index.ts # Porta de entrada da aplicação
├──images/ # Imagens usadas na documentação
├──__tests__/ # Arquivos de testes unitários
├── .dockerignore
├── .env 
├── .gitignore 
├── docker-compose
├── dockerfile
├── jest.config.js
├── package-lock.json 
├── package.json
├── README.md 
├── RotasToDoList 
├── RotasToDoList.har 
├── README.md 
└── tsconfig.json                            

```

<h2 id="diagrams">📊 Diagramas</h2>
<!-- Substitua -->
<h3>:bookmark_tabs:Diagrama de Classes</h3>

```bash
    insira o Diagrama de Classes aqui
```

<h3>:newspaper:Diagrama de Pacotes</h3>

```bash
    insira o Diagrama de Pacotes aqui
```
<h2 id="model">🧬 Modelo Entidade Relacionamento</h2>

```bash
    insira o Modelo Entidade Relacionamento aqui
```
<h2 id="doc">:pushpin:Documentação</h2>

<!-- Substitua  -->

- [📘 Documento de Requisitos](https://link-doc-requisitos)
- [🎨 Protótipo/Design no Figma](https://figma.com/projeto-exemplo)
- [📋 Documento de Arquitetura](https://link-doc-arquitetura)
- [📑 Outros documentos](https://link-outros-docs)

<h2 id="contribute">🙌 Como Contribuir</h2>

<!-- Substitua  -->

Aqui, você explicará como outros desenvolvedores podem contribuir para o projeto. Por exemplo, explicando como criar suas próprias branches, quais padrões seguir e como abrir um pull request.

1. `git clone https://github.com/www/text-editor.git`
2. `git checkout -b feature/NAME`
3. Siga os padrões de commit.
4. Abra um Pull Request explicando o problema resolvido ou o recurso criado. Se houver, anexe uma captura de tela com as modificações visuais e aguarde a revisão!

<h2 id="add">🤔 Informações adicionais </h2>

<!-- Substitua  -->

```
    Adicione informações extras do projeto aqui
```
    
