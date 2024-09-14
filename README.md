# Vue Store

Este é o meu primeiro projeto usando **VueJS 2**. Ele é uma aplicação simples que simula uma loja online. O objetivo é listar produtos, visualizar detalhes e adicionar produtos ao carrinho. Tudo foi implementado sem componentes do Vue, usando apenas a estrutura básica.

## Funcionalidades

- Listagem de produtos (usando dados da Fake Store API)
- Visualização dos detalhes de um produto
- Adicionar e remover produtos do carrinho de compras
- Exibir o total de produtos no carrinho
- Exibir o preço total dos itens no carrinho

## Tecnologias Utilizadas

- **VueJS 2** (sem componentes)
- **Bootstrap 5** para o layout e componentes visuais
- **Fake Store API** para simular os produtos

## Como Usar

1. Clone o repositório ou faça o download do projeto.
2. Abra o arquivo `index.html` em seu navegador utilizando a extensão Live Server.
3. A aplicação carregará os produtos automaticamente da [Fake Store API](https://fakestoreapi.com/).
4. Clique nos produtos para ver os detalhes e adicioná-los ao carrinho.
5. O carrinho pode ser visualizado no ícone no topo da página.

## Dependências

- **Bootstrap 5.3**: Utilizado para estilização e responsividade.
- **Vue.js 2**: Framework JavaScript para criar a interface reativa.

## Estrutura do Projeto

- **index.html**: O arquivo principal onde todo o código Vue e HTML está concentrado.
- **src/vue.js**: Arquivo com o Vue.js incluído.
- **Fake Store API**: Os produtos são carregados dinamicamente desta API.