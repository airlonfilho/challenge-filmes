# Introdução

O objetivo do desafio proposto é testar seu nível como desenvolvedor frontend. Este desafio deve ser feito apenas por você. Você poderá escolher entre utilizar ou não bibliotecas para auxiliar seu desenvolvimento, caso deseje utilizar, recomendo a que já conhecemos, Angular Material.

## O desafio

Para o desafio, iremos utilizar a API de filmes [themoviedb](https://developers.themoviedb.org/3/getting-started/introduction), você será responsável por criar uma listagem dos filmes mais populares do dia, consultando o endpoint  [`GET /movie/popular`](https://developers.themoviedb.org/3/movies/get-popular-movies) para realizar a listagem. Ao clicar em um item dessa listagem, outra página com os detalhes do filme escolhido deve ser exibida. Para acessar mais detalhes sobre o filme, você pode consultar o endpoint [`GET /movie/{movie_id}`](https://developers.themoviedb.org/3/movies/get-movie-details).

Siga o [layout do figma](https://www.figma.com/file/7O2kK5EYSFgyqNeWQyjWB3/Teste-Front-End-Homem-de-Ferro?t=LoiQ7RuDxtzH1pnj-1). Não há necessidade de ser pixel perfect mas respeite a composição, fontes e cores.

## Requisitos funcionais

* [ ] O usuário deve ter acesso a uma listagem dos filmes mais populares do dia

* [ ] O usuário deve conseguir paginar a lista para encontrar novos filmes

* [ ] O usuário deve ter acesso a uma outra página com detalhes sobre o filme, ao clicar em um item na listagem

* [ ] A página com detalhes de um filme deve possuir uma rota própria e estar preparada para ser indexada em mecanismos de pesquisa


## Requisitos não funcionais

* [ ] O app deverá ser criado usando [Angular](https://angular.io/)

* [ ] Na raiz do projeto, será necessário incluir um arquivo `README.md` com as instruções para construir seu projeto localmente. Opcionalmente você pode detalhar as razões pelas escolhas de ferramentas e técnicas aplicadas ao desafio.

* [ ] O app deverá se comportar da mesma forma na última versão estável dos seguintes browsers: Chrome, Firefox, Edge

* [ ] O app deverá ser responsivo

## Extras

Temos insights que nos levam a acreditar que os usuários dessa lista costumam ter uma experiência melhor se conseguirem criar um filtro usando seus gêneros favoritos. Portanto, você também poderá criar filtros de filmes por gênero nessa listagem. Note que um novo endpoint deverá ser consultado para obter uma lista dos possíveis gêneros a serem filtrados, [`GET /genre/movie/list`](https://developers.themoviedb.org/3/genres/get-movie-list).

* [ ] O usuário deve conseguir filtrar os filmes listados por gênero, com a possibilidade de usar mais de um gênero
* [ ] O usuário deve conseguir remover filtros e a listagem deve ser atualizada de acordo com o filtro removido
* [ ] O usuário deve conseguir voltar para a página de listagem de filmes com os filtros ainda ativos

## Critérios de avaliação

- Boas práticas de desenvolvimento como: html semântico, componentização, design patterns, clean code
- Domínio das ferramentas e linguagens que compõe um app de frontend moderno
- Documentação: explicação para construir o app localmente, histórico e workflow de git

## Entrega

Para realizar a entrega do desafio, você deverá upar o projeto no gitlab ou github, fica a seu critério e enviar uma mensagem no teams avisando que terminou o projeto juntamente com o link de acesso.

Não se esqueça de criar um arquivo `README.md` contendo as instruções para construir o app localmente.

## Dúvidas

Caso haja qualquer dúvida sobre o teste, pode me chamar no teams que irei ajudar assim que possível.

---
Obrigado e bom desafio!
