# Blog Pessoal

Aplicação web de blog pessoal desenvolvida para oferecer uma experiência simples de navegação, autenticação e gerenciamento de conteúdo.

O projeto foi construído com foco em organização visual, fluxo de uso claro e integração com API para cadastro, listagem, edição e exclusão de dados.

## Sobre o projeto

Este projeto representa o front-end de uma plataforma de blog onde o usuário pode acessar sua conta, visualizar postagens, cadastrar novos temas e administrar o próprio conteúdo.

Mais do que uma interface, ele demonstra a construção de uma aplicação completa no lado do cliente, com formulários, rotas, autenticação e comunicação com serviços externos.

## O que pode ser feito na aplicação

- Entrar na plataforma com autenticação de usuário
- Criar uma nova conta
- Visualizar postagens cadastradas
- Criar, editar e excluir postagens
- Criar, editar e excluir temas
- Acessar a página de perfil
- Receber mensagens visuais de sucesso, erro e carregamento durante as ações

## Destaques do projeto

- Navegação organizada entre as principais áreas da aplicação
- Estrutura baseada em componentes reutilizáveis
- Integração com API para operações de cadastro, consulta, atualização e exclusão
- Controle de autenticação para liberar ou restringir o acesso a determinadas telas
- Feedback visual para melhorar a experiência do usuário

## Tecnologias principais

- React
- TypeScript
- Vite
- Tailwind CSS
- React Router DOM
- Axios

## Bibliotecas utilizadas

Algumas bibliotecas foram utilizadas para melhorar a experiência da aplicação e acelerar o desenvolvimento:

- `react-toastify` para notificações visuais
- `react-spinners` para loaders e estados de carregamento
- `reactjs-popup` para modais e interações auxiliares
- `@phosphor-icons/react` para ícones

## O que este projeto demonstra

Para avaliadores, recrutadores e pessoas não técnicas, este projeto mostra principalmente:

- Capacidade de transformar requisitos em uma interface funcional
- Organização de uma aplicação front-end em páginas, componentes e serviços
- Integração com back-end real
- Preocupação com fluxo do usuário e feedback visual
- Estruturação de um CRUD completo com autenticação

## Como executar o projeto

1. Instale as dependências:

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

4. Para gerar a versão de producão:

```bash
npm run build
```

## Scripts disponiveis

- `npm run dev` para desenvolvimento local
- `npm run build` para gerar a build de producão
- `npm run preview` para visualizar a build localmente
- `npm run lint` para análise estática do codigo

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
