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
 <a href="#sobre">Sobre</a> • 
 <a href="#instalacao">Instalação</a> • 
 <a href="#rotas-aplicacao">Rotas da Aplicação</a> • 
 <a href="#endpoints">Endpoints da API</a> •
 <a href="#colaboradores">Colaboradores</a> •
 <a href="#como-contribuir">Contribuir</a>
</p>


<h2 id="started">📌 Sobre </h2>

Descrição simples do que seu projeto faz e como utilizá-lo.

<h2 id="started">🚀 Instalação </h2>

Aqui você descreve como executar seu projeto localmente

<h3> Pré-requisitos </h3>

Aqui você lista todos os pré-requisitos necessários para executar seu projeto. Por exemplo:

- [NodeJS](https://github.com/)
- [Git 2](https://github.com)

<h3> Clonando o projeto </h3>

Como clonar seu projeto

```bash
git clone your-project-url-in-github
```

<h3>Iniciando o projeto</h3>

How to start your project

```bash
cd project-name
npm some-command-to-run
```

<h2 id="routes">📍 Rotas de aplicação </h2>

Aqui você pode listar as principais rotas da sua API e quais são os corpos de requisição esperados.
​
| rota                | descrição                                           
|----------------------|-----------------------------------------------------
| <kbd>/authenticate</kbd>     | página que lista todas as informações do usuário
| <kbd>/login</kbd>     | página para login
| <kbd>/dashboard</kbd>     | página que contém todas as informações de compras e operações do usuário

<h2 id="contribute">📫 Contribute</h2>

Aqui, você explicará como outros desenvolvedores podem contribuir para o projeto. Por exemplo, explicando como criar suas próprias branches, quais padrões seguir e como abrir um pull request.

1. `git clone https://github.com/www/text-editor.git`
2. `git checkout -b feature/NAME`
3. Siga os padrões de commit.
4. Abra um Pull Request explicando o problema resolvido ou o recurso criado. Se houver, anexe uma captura de tela com as modificações visuais e aguarde a revisão!

<h3>Pré-requisitos</h3>

Aqui você lista todos os pré-requisitos necessários para executar seu projeto. Por exemplo:

- [NodeJS](https://github.com/)
- [Git 2](https://github.com)


<h3> Variáveis ​​de Ambiente </h3>
#Exemplo

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

Aqui você pode listar as principais rotas da sua API e quais são os corpos de requisição esperados.
​
| rota                | descrição                                           
|----------------------|-----------------------------------------------------
| <kbd>GET /authenticate</kbd>     | recupera informações do usuário [response details](#get-auth-detail)
| <kbd>POST /authenticate</kbd>     | autentica o usuário na API  [request details](#post-auth-detail)

<h3 id="get-auth-detail">GET /authenticate</h3>

**RESPONSE**
```json
{
  "name": "Gustavo Magalhães",
  "age": 25,
  "email": "gemail@gmail.com"
}
```

<h3 id="post-auth-detail">POST /autenticar </h3>

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

<h2 id="colab">🤝 Collaborators</h2>

Special thank you for all people that contributed for this project.

<table>
  <tr>
    <td align="center">
      <a href="#">
        <img src="https://t.ctcdn.com.br/n7eZ74KAcU3iYwnQ89-ul9txVxc=/400x400/smart/filters:format(webp)/i490769.jpeg" width="100px;" alt="Elon Musk Picture"/><br>
        <sub>
          <b>Elon Musk</b>
        </sub>
      </a>
    </td>
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
