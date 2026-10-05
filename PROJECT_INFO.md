# Informações do projeto

`netflixapi` é uma aplicação frontend inspirada em um catálogo de streaming. Ela consulta listas de filmes e séries de diferentes categorias na API do The Movie Database (TMDB), em português (`pt-BR`), e exibe seus cartazes.

## Tecnologias

- React 17 e JavaScript
- Create React App (`react-scripts` 5)
- API REST do TMDB, acessada com `fetch`

## Como executar

Com Node.js e npm instalados, na raiz do projeto:

```bash
npm install
npm start
```

O servidor de desenvolvimento fica disponível em `http://localhost:3000`.

Scripts disponíveis:

- `npm start` — inicia o servidor de desenvolvimento.
- `npm run build` — gera a versão de produção em `build/`.
- `npm test` — inicia o executor de testes interativo do Create React App.

## Arquivos principais

- `src/App.js` — carrega as categorias e monta a página.
- `src/Tmdb.js` — consulta as listas de conteúdo da API do TMDB.
- `src/components/MovieRow.js` — renderiza uma categoria e seus cartazes.
- `src/App.css` — estilos da aplicação.
- `src/index.js` — ponto de entrada que monta o React na página.
- `package.json` — dependências e scripts npm.
