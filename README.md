![logo](https://user-images.githubusercontent.com/54605079/84615574-c36daf80-ae9f-11ea-9dbc-4c6ae23fa2ef.png)


## 💻 Sobre

♻️Ecoleta - é uma forma de conectar empresas e entidades de coleta de resíduos orgânicos e inorgânicos as pessoas que precisam descartar seus resíduos de maneira ecológica.

As empresas ou entidades poderão se cadastrar na plataforma web enviando:
- uma imagem do ponto de coleta
- nome da entidade, email e whatsapp
- e o endereço para que ele possa aparecer no mapa
- além de selecionar um ou mais ítens de coleta: 
  - lâmpadas
  - pilhas e baterias
  - papéis e papelão
  - resíduos eletrônicos
  - resíduos orgânicos
  - óleo de cozinha

Os usuários terão acesso ao aplicativo móvel, onde poderão:
- navegar pelo mapa para ver as instituições cadastradas
- entrar em contato com a entidade através do E-mail ou do WhatsApp

Projeto desenvolvido durante a **NLW - Next Level Week** oferecida pela [Rocketseat](rs).
O NLW é uma experiência online com muito conteúdo prático, desafios e hacks onde o conteúdo fica disponível durante uma semana.

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Expo][expo]
- [Node.js][nodejs]
- [React][reactjs]
- [React Native][rn]
- [TypeScript][typescript]



### Mobile

<p align="center">
  <img alt="NextLevelWeek" title="#NextLevelWeek" src="https://user-images.githubusercontent.com/54605079/84616248-da150600-aea1-11ea-81fe-fa40dbaff4b9.png" width="200px">

  <img alt="NextLevelWeek" title="#NextLevelWeek" src="https://user-images.githubusercontent.com/54605079/84616249-dbdec980-aea1-11ea-8d1b-7434783b6a34.png" width="200px">
</p>

### Web

<p align="center" style="display: flex; align-items: flex-start; justify-content: center;">
  <img alt="NextLevelWeek" title="#NextLevelWeek" src="https://user-images.githubusercontent.com/54605079/84615577-c49edc80-ae9f-11ea-8f5e-7d89c893a8bd.png" width="400px">

  <img alt="NextLevelWeek" title="#NextLevelWeek" src="https://user-images.githubusercontent.com/54605079/84615576-c49edc80-ae9f-11ea-9f59-5e4973f51804.png" width="400px">
</p>


## 🚀 Como rodar este projeto

Podemos considerar este projeto como sendo divido em três partes:
1. Back End (pasta server) 
2. Front End (pasta web)
3. Mobile (pasta mobile)

💡Tanto o Front End quanto o Mobile precisam que o Back End esteja sendo executado para funcionar.


### 🎲 Rodando o Back End (servidor)

```bash
# Clone este repositório
$ git clone https://github.com/pleonardodp12/Ecoleta

# Acesse a pasta do projeto no terminal/cmd
$ cd Ecoleta

# Vá para a pasta server
$ cd server

# Instale as dependências
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ npm run dev:server

# O servidor inciará na porta:3333 - acesse http://localhost:3333 
```

### 🧭 Rodando a aplicação web (Front End)

```bash
# Clone este repositório
$ git clone https://github.com/pleonardodp12/Ecoleta

# Acesse a pasta do projeto no seu terminal/cmd
$ cd Ecoleta

# Vá para a pasta da aplicação Front End
$ cd web

# Instale as dependências
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ npm run start

# A aplicação será aberta na porta:3000 - acesse http://localhost:3000
```



[nodejs]: https://nodejs.org/
[typescript]: https://www.typescriptlang.org/
[expo]: https://expo.io/
[reactjs]: https://reactjs.org
[rn]: https://facebook.github.io/react-native/
[yarn]: https://yarnpkg.com/
[vscode]: https://code.visualstudio.com/
[vceditconfig]: https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig
[license]: https://opensource.org/licenses/MIT
[vceslint]: https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
[rs]: https://rocketseat.com.br
