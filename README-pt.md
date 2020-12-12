<h1 align="center">
    <img src="./assets/logo.png" alt="Flora"/>
</h1>

<img src="./assets/flora.gif" alt="Gif da aplicação"/>

# 🌱 Flora: loja de plantas
Este é um projeto de e-commerce de plantas para reforçar os conceitos estudados sobre desenvolvimento web contemporâneo. O projeto consiste em dois níveis de acesso, o administrativo e o do cliente. Por parte do administrador, é possível cadastrar e controlar os produtos disponibilizados no e-commerce. Na seção do cliente, há a lista de produtos e o carrinho de compras para simular as vendas.

## 📝 Projeto
Foi utilizada uma API RESTfull para fornecer os dados, dando flexibilidade para distribuir a aplicação em múltiplas plataformas; e um SPA (Single Page Application) no front end web para otimizar o desempenho e garantir a melhor experiência do usuário.


## ⚙️ Back-end

### Tecnologias
- PostgreSQL
- TypeORM
- Node.js
- Express
- Multer (middleware de upload de arquivos)
- TypeScript
- Arquitetura REST

### Conceitos
- Utilização de migrations para criar versões do banco de dados, facilitando o trabalho colaborativo;
- Utilização de ORM para manipular o banco de dados, abstraindo o próprio banco de dados e simplificando possíveis mudanças;
- Utilização de solicitações HTTP semânticas, respeitando os significados dos verbos e nomeando coleções com seu significado real;
- Utilização do conceito de “Serviços” para realizar ações sobre os recursos da aplicação que envolvem regras de negócio, abstraindo cada regra de negócio em um único arquivo, facilitando a manutenção do código;
- Utilização de rotas HTTP para fornecer arquivos estáticos;
- Utilização de uma pasta temporária para fazer upload de arquivos para o servidor. Em aplicações reais de grande escala, o ideal é transferir esses arquivos da pasta temporária para um servidor de arquivos estáticos.

## 💻 Front-end

### Tecnologias
- React.js
- React Hooks
- Styled-Components
- TypeScript

### Conceitos
- Utilização de componentes React em forma de função, com sintaxe moderna para facilitar o entendimento e usando APIs React;
- Utilização do Axios para consumir APIs externas;
- Utilização de hooks do React para manipular estados da aplicação e otimizar os ciclos de renderização;
- Utilização da API de contexto para disponibilizar os itens do carrinho de compras para todas as páginas do aplicativo;
- Utilização da componentização de elementos reutilizáveis, como cartões de produto, cabeçalho e rodapé. Isso permite a modularização da construção do código, proporcionando agilidade no desenvolvimento e tornando ágil a manutenção do sistema;
- Utilização do ESLint e do Prettier para configurar os padrões de escrita de código, evitando discordâncias de escrita entre os membros da equipe.

###  Layout
O layout da aplicação está disponível no [Figma](https://www.figma.com/file/nIT6fFPNfYZF5EOsRtqYg5/Flora-e-commerce?node-id=0%3A1).

## 🔧 Executar no seu PC

- Clone esse repositório;
- Vá para a pasta backend `cd backend`;
- Execute o comando para instalar as dependências, como `npm install` ou `yarn`;
- Crie um database no PostgreSQL com o nome "flora";
- Atualize o arquivo ormconfig.json com o usuário e senha do seu banco;
- Execute as migrations com o comando `yarn typeorm migration:run`;
- Inicie o backend rodando o comando `yarn dev:server` ou `npm dev:server`, seu backend vai iniciar na porta 3333;
- Abra um novo terminal na pasta raiz do projeto e então vá até a pasta web `cd web`;
- Execute o comando para instalar as dependências, como `npm install` or `yarn`;
- Após isso, execute o comando para iniciar o projeto, por exemplo: `npm run dev` ou `yarn start`;
- Acesse a aplicação em <strong> `http://localhost:3000`</strong>, mude a porta caso você tiver configurado outra.

## 🤔 Como contribuir

- Faça um fork desse repositório;
- Crie uma branch com as suas alterações: `git checkout -b my-feature`;
- Commit suas alterações: `git commit -m 'feat: my new feature'`;
- Faça um push para a sua branch: `git push origin my-feature`.

## 📜 Licença

> Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](https://github.com/lauromvs/flora/blob/main/LICENSE.md) para mais detalhes.

---

##### <p align="center"> <strong> < desenvolvido por <a href="github.com/jessicafpx"> @jessicafpx</a> e <a href="github.com/lauromvs"> @lauromvs  </a> /> </strong> 👋