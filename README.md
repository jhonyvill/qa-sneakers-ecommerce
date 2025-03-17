# qa-sneakers-ecommerce

Esta página é destinada ao mapeamento das funcionalidades e à criação de casos de teste para a aplicação web [Sneakers E-commerce Product Page](jvs-sneakers-product-page.netlify.app).

Sneakers é uma adaptação à aplicação front-end que desenvolvi em [resolução ao desafio](https://github.com/jhonyvill/sneakers-ecommerce) proposto por Frontend Mentor. Trata-se de uma página de produto que permite aos usuários realizarem algumas ações, como adicionar itens ao carrinho de compras, excluir itens do carrinho e visualizar imagens do produto, sendo adicionados na adaptação alguns comportamentos inesperados para representação de bugs.

Nesta página documentei o mapeamento das funcionalidades disponíveis na aplicação, os casos de testes correspondentes à cada funcionalidade, bem como informações inerentes à execução, como status do caso de teste, modo de execução e bug report. 

O objetivo principal desta página é aplicar e consolidar os conhecimentos adquiridos a respeito da criação e documentação de testes, simulando situações reais do dia a dia em projetos software.

Inicialmente o documento foi criado no Confluence, com criação de bug report no Jira, caso prefira a visualização da documentação através destas páginas, [clique aqui](https://jvs-dev.atlassian.net/l/cp/wTBKNSKF).

## Autor

- Linkedin - [Jhony Vill da Silva](www.linkedin.com/in/jhonyvill).

## Índice.

- Funcionalidades
    - Seletor de quantidade de um produto.
        - [Selecionar a quantidade de um produto.](./features/01-select-quantity-item.md)
    - Carrinho de compras.
        - [Visualizar carrinho de compras.](./features/02-view-cart.md)
        - [Adicionar item.](./features/03-add-item-cart.md)
        - [Realizar checkout.](./features/04-checkout-cart.md)
        - [Deletar item.](./features/05-remove-item-cart.md)
    - Imagens do produto.
        - [Alterar imagem em destaque na página de produto.](./features/06-change-featured-image.md)
        - [Visualizar imagens em modal de tela cheia.](./features/07-view-images-modal.md)
        - [Alterar imagem em destaque no modal de tela cheia.](./features/08-change-image-modal.md)
        - [Fechar visualização de imagens em tela cheia.](./features/09-close-images-modal.md)
    - Navegação entre páginas.
        - [Redirecionar para página inicial através da logo “Sneakers”.](./features/10-redirect-homepage-logo.md)