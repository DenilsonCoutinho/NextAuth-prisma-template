<p>Este Starter Kit foi desenvolvido para poupar seu tempo, oferecendo tudo o que você precisa para começar a desenvolver seu projeto com segurança.<p/>
<br>
<h1>
  Tecnologias e Bibliotecas
</h1>
<div>
<img src="https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white"/>
<img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB"/>
<br>
<img src="https://camo.githubusercontent.com/155334dc24b2f2f66adc27c61d12aef11e6de40c93ebe0a2e4de459314f69e34/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d53484144434e55492d53484144434e55493f6c6162656c436f6c6f723d30303030303026636f6c6f723d303030303030"/>
<img src ="https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white"/>
  <img src ="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white"/>
  <img src="https://raw.githubusercontent.com/nodemailer/nodemailer/master/assets/nm_logo_200x136.png" alt="Nodemailer" style="width: 5%;">
</div>
<br>
<h1>Vamos lá</h1>
Clone o repositório:

```sh
git clone https://github.com/DenilsonCoutinho/NextAuth-prisma-template.git
```
<br>
Entre na pasta do projeto e instale os pacotes:

```sh
npm install
```
<br>
<h1>Configuração de Envio de E-Mail</h1>

É necessário criar uma chave de API no googleAccouts para envios de email e  verificação de usuário.
<img src="https://github.com/user-attachments/assets/d55ee801-2ecd-4dea-ba9c-2166cc4dea23" style="width: 60%;"/>

caso tenha dificuldades para gerar a chave de API, assista este video <a target="_blank" href="https://www.youtube.com/watch?v=nuD6qNAurVM&pp=ygUSYXBwIHBhc3N3b3JkIGdtYWls">Clicando aqui</a>

<h1>Variáveis de ambiente</h1>
Renomeie o arquivo .env.example para .env. Depois, modifique as variáveis de ambiente conforme necessário:

Váriável do banco de dados:

```sh
# Exemplo utilizando mongoDb
DATABASE_URL="mongodb+srv://teste:GAsd3dsa#a@teste.nhi49b7.mongodb.net/teste"
```
Variável de encriptação do token JWT:


```sh
AUTH_SECRET=314FUJnJeO1zGfxpxbmqqxQsBiCl/NwOyJ9AONpG03Y=
```

Para gerar a chave AUTH_SECRET, utilize o comando
```sh
# Unix
openssl rand -base64 32
```

ou

```sh
# Windows
npm exec auth secret
```

Caso deseje executar em modo produção npm run start, será necessário descomentar a variável:

```sh
AUTH_TRUST_HOST=true
```

<h1>Alguma dúvida?</h1>

chama no zap: 47992128261

fico a disposição :)

