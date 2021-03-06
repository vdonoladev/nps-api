<h2 align="center">nps-api</h2>

<p align="center">
  <a href="LICENSE">
    <img alt="License" src="https://img.shields.io/badge/license-MIT-%23F8952D">
  </a>
</p>

<h3 align="center">
  <a href="#information_source-sobre">Sobre</a>&nbsp;|&nbsp;
  <a href="#interrobang-motivo">Motivo</a>&nbsp;|&nbsp;
  <a href="#rocket-tecnologias-utilizadas">Tecnologias</a>&nbsp;|&nbsp;
  <a href="#licença">Licença</a>
</h3>

---

## :information_source: Sobre

O <strong>NPS-API</strong> é uma API Restful para Net Promoter Score.

Aplicação web construída na trilha NodeJS da Next Level Week distribuída pela Rocketseat.

## :interrobang: Motivo

Estudos em NodeJS

## :rocket: Tecnologias Utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias

- Node.JS
- Express
- Yarn
- TypeORM

## ⤵ Instruções para Instalação e Execução

Estas instruções o levarão a uma cópia do projeto em execução em seu computador local para teste e desenvolvimento. O teste de integração foi implementado.

Nota: O banco de dados é Sqlite3, se você deseja alterar, configure o arquivo ormconfig.json para seu banco de dados específico (o campo "database" é o nome do banco de dados no SGBD, o projeto é local).

```bash
- git clone https://github.com/vdonoladev/nps-api.git
- cd nps-api
```

Instale dependências (NPM é recomendado para compatibilidade com reflect-metadata)

```bash
- npm install
```

ou

```bash
- yarn install
```

Gerar o arquivo de database.sqlite do Sqlite3, onde ficaram armazenados as tabelas da API

```bash
- yarn devDB
```

Criando tabela das migrations do Sqlite3 por meio do cli do TypeOrm

```bash
- yarn typeorm migration:run
```

Inicializando uma instância local (Script configurado no package.json)

```bash
- yarn dev
```

## ⤵ Testes

Para testar se instalou a aplicação corretamente e se passa em todos os testes de integração, utilize o comando:

```bash
- yarn test
```

---

### :books: Dia 1 (Rumo ao Próximo Nível)

No primeiro dia vamos aprender os conceitos básicos sobre o que é uma API, entender o que é o NodeJS, onde ele tem sido utilizado e qual problema ele veio solucionar e também. Vamos também conhecer o TypeScript e entender como ele irá nos ajudar durante o desenvolvimento da nossa aplicação. Já nessa aula vamos dar início ao desenvolvimento da nossa API, colocando em prática alguns dos conceitos aprendidos.

### :books: Dia 2 (Banco de Dados)

No segundo dia vamos iniciar a configuração do banco de dados na nossa aplicação, aprendendo algumas formas possíveis para realizar o acesso do banco de dados através do Nodejs. Vamos entender os conceitos de migrations, models e criar nossa primeira tabela de usuário. Também nessa aula iremos aprender e criar nosso primeiro Controller, isolando toda regra para dentro dele.

### :books: Dia 3 (Testando a nossa aplicação)

No terceiro dia vamos conhecer o conceito de Repository e como podemos utilizar ele para separar as responsabilidades nos componentes corretos. Vamos também dar inícios aos testes automatizados e entender os benefícios que eles trazem para a nossa aplicação.

### :books: Dia 4 (Envio de E-mail)

No quarto dia vamos aprender como enviar e-mail, utilizando templates customizados com informações vindas do banco de dados. Vamos aprender também como utilizar variáveis de ambiente dentro da aplicação.

### :books: Dia 5 (Finalizando nossa API com Validações)

Nessa última aula vamos finalizar o fluxo da nossa aplicação, inserir validações dos dados recebidos e aprender como tratar os possíveis erros.

---

## Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
