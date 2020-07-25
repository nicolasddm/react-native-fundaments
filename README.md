# react-native-concepts
Challenge of RocketSeat GoStack about react-native concpets

## Sumário 

- [Instalação](#instalação)
- [Créditos](#créditos)

---

## Instalação

- É necessário instalar várias dependências para rodar uma aplicação em react native no seu computador, dependendo do seu sistema operacional, seu celular, seu computador. Por isso este link pode te ajudar pra qualquer ambiente que você tenha com você.
https://react-native.rocketseat.dev/

- Essa aplicação tem apenas código para o Front-end, porém a intenção dele é apenas mostrar os dados que eu possuo no back-end. Você pode conectar seu próprio "base_url" para usar a sua API em './src/services/api.js'.

- Além disso, eu uso o yarn. Intalá-lo acesse no ubuntu https://classic.yarnpkg.com/en/docs/install/#debian-stable

### Clone

- Clone esse repositório na sua máquina local `https://github.com/nicolasddm/FastFeet.git`

### Setup

> Instale as dependências do projeto pelo yarn

```shell
$ yarn install
```

> Para que você tenha os dados para exibir em tela, você poderá utilizar uma fake API para te prover esses dados. um arquivo chamado server.json que contém os dados para uma rota /products. Para executar esse servidor você pode executar o seguinte comando:

```shell
$ yarn json-server server.json -p 3333
```
> Ou se você for usar um dispositivo físico. Basta rodar:

```shell
$ yarn json-server --host <IP_DA_SUA_MÁQUINA> server.json -p 3333
```

> Agora basta rodar o projeto. No package.json você pode encontrar alguns scripts.

```shell
$ yarn start
```

> É necessário instalar o app no seu dispositivo também, seja ele físico ou um emulador. Em outro terminal rode

```shell
$ yarn android
```

> Caso você queira rodar o projeto com os testes para ver se a aplicação está fazendo o que é esperado você pode

```shell
$ yarn test
ou
$ yarn test --watchAll
```
---

## Créditos
 - Esse repositório foi feito por mim apenas. Nicolas Dencker De Marco.
 - Para entrar em contato, segue meu LinkedIn: https://www.linkedin.com/in/nicolas-de-marco/

