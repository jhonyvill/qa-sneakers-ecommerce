## Funcionalidade.
**Selecionar a quantidade de um produto.**

## User Story.
Como cliente,<br>
Quero poder selecionar a quantidade de um mesmo produto,<br>
Para poder adicionar múltiplas unidades do mesmo produto ao carrinho de compras.<br>

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
                <strong>Dado</strong> que estou na página de um produto,<br>
                <strong>Quando</strong> clico no botão com o símbolo “+” no seletor de quantidade,<br>
                <strong>Então</strong> a quantidade selecionada do produto é aumentada em 1.<br>
            </td>
            <td>Manual</td>
            <td>Aprovado</td>
            <td></td>
        </tr>
        <tr>
            <td>
                <strong>Dado</strong> que estou na página de um produto,<br>
                <strong>E</strong> a quantidade selecionada do produto é igual a 10,<br>
                <strong>Quando</strong> clico no botão com o símbolo “+” no seletor de quantidade,<br>
                <strong>Então</strong> nada acontece e a quantidade selecionada permanece 10.<br>
            </td>
            <td>Manual</td>
            <td>Aprovado</td>
            <td></td>
        </tr>
        </tr>
        <tr>
            <td>
                <strong>Dado</strong> que estou na página de um produto,<br>
                <strong>E</strong> a quantidade selecionada do produto é maior que 0,<br>
                <strong>Quando</strong> clico no botão com o símbolo “-” no seletor de quantidade,<br>
                <strong>Então</strong> a quantidade selecionada do produto é reduzida em 1.<br>
            </td>
            <td>Manual</td>
            <td>Aprovado</td>
            <td></td>
        </tr>
        </tr>
        <tr>
            <td>
                <strong>Dado</strong> que estou na página de um produto,<br>
                <strong>E</strong> a quantidade selecionada do produto é igual a 0,<br>
                <strong>Quando</strong> clico no botão com o símbolo “-” no seletor de quantidade,<br>
                <strong>Então</strong> nada acontece e a quantidade selecionada permanece 0.<br>
            </td>
            <td>Manual</td>
            <td>Aprovado</td>
            <td></td>
        </tr>
    </tbody>
</table>