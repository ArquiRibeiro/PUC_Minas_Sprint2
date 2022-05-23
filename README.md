# PUC Minas - Sprint 2 (Páginas HTML)
## Leonardo Ribeiro Andrade
[Visualizar Site]()
### Páginas Prontas:
- Index (Menu Principal)
- Registro De ONG
- Doar

### Layout
O layout do site é mobile first e responsivo através do uso das Media Queries, onde se criou 3 breakpoints: 576, 768, e 992px. Há também um forte uso de elementos Flex e Grid, ainda que em alguns casos tenha sido redundante a escolha entre um ou outro. Além disso, houve cuidado redobrado para a utilização de tags semânticas para incrementar a qualidade do site.

### Funcionalidades
O site, ainda que incompleto, apresenta algumas funcionalidades, como um mapa Google e lista com busca de cidades na página "doar.html". Todas as funções foram escritas de maneira que sejam genéricas o suficiente para reutilizações futuras.

### Cores
As cores do site ainda não são definitivas, mas utilizou-se cores em tons de caramelo devido a temática do site.

#### Observações:
- Os ícones em formato ".svg" foram obtidos do site [FontAwesome](https://fontawesome.com/)
- As imagens utilizadas NÃO SÃO DE AUTORIA DO GRUPO, mas foram obtidas através dos sites [PixaBay](https://pixabay.com/pt/) e [Pexels](https://www.pexels.com/pt-br/). Os autores das imagens estão presentes numa DIV comentada nos arquivos ".html".
- Foi-se necessário utilizar "onkeyup" ao invés de "onkeypress" para que o caractere digitado dentro do input "LrSearchInput" pudesse ser devidamente processado. Caso contrário, a função será chamada cedo demais.