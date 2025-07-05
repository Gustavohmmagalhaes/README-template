[JAVASCRIPT__BADGE]: https://img.shields.io/badge/Javascript-000?style=for-the-badge&logo=javascript
[TYPESCRIPT__BADGE]: https://img.shields.io/badge/typescript-D4FAFF?style=for-the-badge&logo=typescript
[REACT__BADGE]: https://img.shields.io/badge/React-005CFE?style=for-the-badge&logo=react
[VUE__BADGE]: https://img.shields.io/badge/VueJS-fff?style=for-the-badge&logo=vue
[GATSBY__BADGE]: https://img.shields.io/badge/Gatsby-7026b9?style=for-the-badge&logo=gatsby
[ANGULAR__BADGE]: https://img.shields.io/badge/Angular-red?style=for-the-badge&logo=angular
[EXPRESS__BADGE]: https://img.shields.io/badge/express-005CFE?style=for-the-badge&logo=express
[NEST__BADGE]: https://img.shields.io/badge/nest-7026b9?style=for-the-badge&logo=nest
[GRAPHQL__BADGE]: https://img.shields.io/badge/GraphQL-e10098?style=for-the-badge&logo=graphql
[JAVA_BADGE]:https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white
[SPRING_BADGE]: https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white
[MONGO_BADGE]:https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white
[AWS_BADGE]:https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white



<h1 align="center" style="font-weight: bold;">Nome do Projeto 💻</h1>

![react][REACT__BADGE]
![gatsby][GATSBY__BADGE]
![angular][ANGULAR__BADGE]
![vue][VUE__BADGE]
![express][EXPRESS__BADGE]
![nest][NEST__BADGE]
![graphql][GRAPHQL__BADGE]
![AWS][AWS_BADGE]
![spring][SPRING_BADGE]
![java][JAVA_BADGE]
![mongo][MONGO_BADGE]


<p align="center">
    <img src="./logo-comp.png" alt="logo" width="400" height="70">
</p>
<p align="center">
 <a href="#sobre">Visão Geral</a> • 
 <a href="#sobre">Pré-requisitos</a> • 
 <a href="#instalacao">Como executar o Projeto</a> • 
 <a href="#rotas-aplicacao">Rotas da Aplicação</a> • 
 <a href="#endpoints">Endpoints da API</a> •
 <a href="#structure">Estrutura do Projeto</a> •
 <a href="#diagrams">Diagramas do projeto</a> •
 <a href="#contribute">Contribuir</a> •
 <a href="#colab">Colaboradores</a> •
</p>


<h2 id="started">🌐 Visão Geral </h2>

Escreva uma descrição simples do que seu projeto.

<h2 id="prerequisites">:pushpin:Pré-requisitos </h2>

Liste todos os pré-requisitos necessários para executar seu projeto. Por exemplo:

- [NodeJS](https://github.com/)
- [Git 2](https://github.com)

<h2 id="started">🚀 Como Executar </h2>

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

<h2 id="routes">📍 Rotas da aplicação </h2>

Liste as principais rotas da sua API e quais são os corpos de requisição esperados. Exemplo:
​
| rota                | descrição                                           
|----------------------|-----------------------------------------------------
| <kbd>/authenticate</kbd>     | página que lista todas as informações do usuário
| <kbd>/login</kbd>     | página para login
| <kbd>/dashboard</kbd>     | página que contém todas as informações de compras e operações do usuário

<h2> Variáveis ​​de Ambiente </h2>

Variáveis de ambiente são pares chave=valor que armazenam informações de configuração fora do código-fonte da aplicação. Exemplo:

| Variável  | Descrição                   | Valor Padrão   |
|-----------|----------------------------|---------------|
| DB_HOST   | Host do banco de dados  | -          |
| DB_USER   | User do banco de dados  | -         |
| DB_PASSWORD   | Senha do Mysql  | -          |
| DB_NAME   | Nome do banco no MySQL    | -   |
| JWT_SECRET   |  Chave JWT  | essa-chave-eh-muito-forte     |
| JWT_EXPIRES_IN   | Validade JWT     | 24h            |
| GMAIL_USER   | Usuário google para envio de emails   | joseacerbialmeida@gmail.com          |
| GMAIL_APP_PASSWORD   | Chave do google    | wlni omwf gpvf xeve          |
| CLOUDINARY_API_SECRET | Senha da API do Cloudinary    | 8-_eSBfJn4nx6qqpkPIrLWa32tQ         |
| CLOUDINARY_CLOUD_NAME  | Nome da cloud no Cloudinary    | dxqcebqx3          |
| CLOUDINARY_API_KEY   | Chave da API do Cloudinary    | 612318217586866          |
| FRONTEND_URL | Url Front  | http://localhost:3001          |

<h2 id="Endpoints">📍 API Endpoints</h2>

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
<h2 id= "structure">📁 Estrutura do Projeto <h2>
    
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

<h2 id="diagrams">📖 Diagramas</h2>

<h3>:bookmark_tabs:Diagrama de Classe</h3>

<h3>:newspaper:Diagrama de Pacote</h3>

<h2 id="contribute">:compass:Como Contribuir</h2>

Aqui, você explicará como outros desenvolvedores podem contribuir para o projeto. Por exemplo, explicando como criar suas próprias branches, quais padrões seguir e como abrir um pull request.

1. `git clone https://github.com/www/text-editor.git`
2. `git checkout -b feature/NAME`
3. Siga os padrões de commit.
4. Abra um Pull Request explicando o problema resolvido ou o recurso criado. Se houver, anexe uma captura de tela com as modificações visuais e aguarde a revisão!
    
<h2 id="colab">🤝 Colaboradores</h2>

Um agradecimento especial a todas as pessoas que contribuíram para este projeto.

<table>
  <tr>
    <td align="center">
      <a href="#">
        <img src="https://miro.medium.com/max/360/0*1SkS3mSorArvY9kS.jpg" width="100px;" alt="Foto do Steve Jobs"/><br>
        <sub>
          <b>Steve Jobs</b>
        </sub>
      </a>
    </td>
  </tr>
</table>
