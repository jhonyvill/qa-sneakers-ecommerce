## Funcionalidade.
**Visualizar carrinho de compras.**

## User Story.
Como cliente,<br>
Quero poder visualizar o carrinho de compras,<br>
Para visualizar os itens adicionados e revisar as quantidades e valores antes de concluir a compra.<br>

## Casos de teste.

<table>
  <thead>
    <tr>
      <th>Casos de teste</th>
      <th>Execução</th>
      <th>Status</th>
      <th>Bug</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <strong>Dado</strong> que estou em qualquer página da aplicação, <br>
        <strong>E</strong> não adicionei itens ao carrinho, <br>
        <strong>Quando</strong> clico no ícone de carrinho de compras, <br>
        <strong>Então</strong> devo ver um modal com o título <strong>“Cart”</strong> <br>
        <strong>E</strong> a mensagem <strong>“Your cart is empty.”</strong>.
      </td>
      <td>Manual</td>
      <td>Aprovado</td>
      <td></td>
      <td>
        <strong>Dado</strong> que estou com o carrinho de compras aberto, <br>
        <strong>Quando</strong> clico no ícone de carrinho de compras, <br>
        <strong>Então</strong> o modal de carrinho de compras deve fechar. <br>
      </td>
      <td>Manual</td>
      <td>Aprovado</td>
      <td></td>
      <td>
        <strong>Dado</strong> que estou com o carrinho de compras aberto, <br>
        <strong>Quando</strong> clico fora do modal, <br>
        <strong>Então</strong> o modal de carrinho de compras deve fechar. <br>
      </td>
      <td>Manual</td>
      <td>Aprovado</td>
      <td></td>
    </tr>
    </tbody>
</table>