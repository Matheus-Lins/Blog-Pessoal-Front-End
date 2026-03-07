# Blog Pessoal

Aplicacao web de blog pessoal desenvolvida para oferecer uma experiencia simples de navegacao, autenticacao e gerenciamento de conteudo.

O projeto foi construido com foco em organizacao visual, fluxo de uso claro e integracao com API para cadastro, listagem, edicao e exclusao de dados.

## Sobre o projeto

Este projeto representa o front-end de uma plataforma de blog onde o usuario pode acessar sua conta, visualizar postagens, cadastrar novos temas e administrar o proprio conteudo.

Mais do que uma interface, ele demonstra a construcao de uma aplicacao completa no lado do cliente, com formularios, rotas, autenticacao e comunicacao com servicos externos.

## O que pode ser feito na aplicacao

- Entrar na plataforma com autenticacao de usuario
- Criar uma nova conta
- Visualizar postagens cadastradas
- Criar, editar e excluir postagens
- Criar, editar e excluir temas
- Acessar a pagina de perfil
- Receber mensagens visuais de sucesso, erro e carregamento durante as acoes

## Destaques do projeto

- Navegacao organizada entre as principais areas da aplicacao
- Estrutura baseada em componentes reutilizaveis
- Integracao com API para operacoes de cadastro, consulta, atualizacao e exclusao
- Controle de autenticacao para liberar ou restringir o acesso a determinadas telas
- Feedback visual para melhorar a experiencia do usuario

## Tecnologias principais

- React
- TypeScript
- Vite
- Tailwind CSS
- React Router DOM
- Axios

## Bibliotecas utilizadas

Algumas bibliotecas foram utilizadas para melhorar a experiencia da aplicacao e acelerar o desenvolvimento:

- `react-toastify` para notificacoes visuais
- `react-spinners` para loaders e estados de carregamento
- `reactjs-popup` para modais e interacoes auxiliares
- `@phosphor-icons/react` para icones

## O que este projeto demonstra

Para avaliadores, recrutadores e pessoas nao tecnicas, este projeto mostra principalmente:

- Capacidade de transformar requisitos em uma interface funcional
- Organizacao de uma aplicacao front-end em paginas, componentes e servicos
- Integracao com back-end real
- Preocupacao com fluxo do usuario e feedback visual
- Estruturacao de um CRUD completo com autenticacao

## Como executar o projeto

1. Instale as dependencias:

```bash
npm install
```

2. Crie um arquivo `.env` na raiz com a URL da API:

```env
VITE_API_URL=http://localhost:8080
```

3. Inicie o ambiente de desenvolvimento:

```bash
npm run dev
```

4. Para gerar a versao de producao:

```bash
npm run build
```

## Scripts disponiveis

- `npm run dev` para desenvolvimento local
- `npm run build` para gerar a build de producao
- `npm run preview` para visualizar a build localmente
- `npm run lint` para analise estatica do codigo

## Estrutura geral

```text
src/
  components/
  contexts/
  models/
  pages/
  services/
  utils/
```

## Autor

Desenvolvido por Matheus Lins.
