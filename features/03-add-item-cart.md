## Funcionalidade.
**Adicionar item ao carrinho de compras.**

## User Story.
Como cliente,<br>
Quero adicionar produtos ao meu carrinho de compras,<br>
Para poder revisar minha seleção antes de finalizar a compra.<br>

## Cenários de teste.

<table>
  <thead>
    <tr>
      <th>Cenários de teste</th>
      <th>Execução</th>
      <th>Status</th>
      <th>Bug</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <strong>Cenário:</strong> verificar possibilidade de adicionar 0 itens selecionados.<br>
        <strong>Dado</strong> que estou na página de um produto, <br>
        <strong>E</strong> a quantidade do item selecionado é 0, <br>
        <strong>Quando</strong> clico no botão “Add to Cart”, <br>
        <strong>Então</strong> nada acontece e nenhum item é adicionado ao carrinho.</strong>
      </td>
      <td>Manual</td>
      <td>Aprovado</td>
      <td></td>
    </tr>
    <tr>
      <td>
        <strong>Cenário:</strong> adicionar um novo item.<br>
        <strong>Dado</strong> que estou na página de um produto, <br>
        <strong>E</strong> a quantidade selecionada do item é maior que 0, <br>
        <strong>Quando</strong> clico no botão “Add to Cart”, <br>
        <strong>Então</strong> a quantidade selecionada do item deve ser adicionada ao carrinho.
        <strong>E</strong> o valor total deve ser calculado como o preço unitário multiplicado pela quantidade selecionada.
      </td>
      <td>Manual</td>
      <td>Aprovado</td>
      <td></td>
    </tr>
    <tr>
      <td>
        <strong>Cenário:</strong> adicionar item existente.<br>
        <strong>Dado</strong> que estou na página de um produto, <br>
        <strong>E</strong> o carrinho de compras já contém esse item, <br>
        <strong>E</strong> a quantidade selecionada do item é maior que 0, <br>
        <strong>Quando</strong> clico no botão “Add to Cart”, <br>
        <strong>Então</strong> a quantidade selecionada do item deve ser acrescentada ao mesmo item existente no carrinho, <br>
        <strong>E</strong> o valor total do item no carrinho deve ser atualizado para refletir o preço unitário multiplicado pela nova quantidade.
      </td>
      <td>Manual</td>
      <td>Aprovado</td>
      <td></td>
    </tr>
    <tr>
      <td>
        <strong>Cenário:</strong> navegar na aplicação com item no carrinho.<br>
        <strong>Dado</strong> que existe um item adicionado ao carrinho, <br>
        <strong>Quando</strong> navego entre as páginas da aplicação, <br>
        <strong>Então</strong> o item adicionado deve permanecer no carrinho.
      </td>
      <td>Manual</td>
      <td>Reprovado</td>
      <td><a href="../bugs/snkrs-1/snkrs-1.md"><span style="white-space: nowrap;">SNKRS-1</span></a></td>
    </tr>
    <tr>
      <td>
        <strong>Cenário:</strong> atualizar página com item no carrinho.<br>
        <strong>Dado</strong> que existe um item adicionado ao carrinho, <br>
        <strong>Quando</strong> atualizo a página, <br>
        <strong>Então</strong> o item adicionado deve permanecer no carrinho.
      </td>
      <td>Manual</td>
      <td>Reprovado</td>
      <td><a href="../bugs/snkrs-2/snkrs-2.md"><span style="white-space: nowrap;">SNKRS-2</span></a></td>
    </tr>
  </tbody>
</table>