## Funcionalidade.
**Navegação através do menu.**

## User Story.
Como cliente,<br>
Quero navegar pelas opções do menu,<br>
Para acessar facilmente diferentes seções do site.<br>

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
                <strong>Cenário:</strong> navegar entre as páginas clicando nas opções do menu de navegação.<br>
                <strong>Dado</strong> que estou na página inicial, <br>
                <strong>Quando</strong> clico em uma das opções do menu de navegação, <br>
                <strong>Então</strong> devo ser redirecionado para a página correspondente, <br>
                <strong>E</strong> deve ser acrescentada a identificação da página após a URL base.<br>
            </td>
            <td>Manual</td>
            <td>Reprovado</td>
            <td><a href="../bugs/snkrs-3/snkrs-3.md"><span style="white-space: nowrap;">SNKRS-3</span></a><br>
            <a href="../bugs/snkrs-4/snkrs-4.md"><span style="white-space: nowrap;">SNKRS-4</span></a> <br>
            <a href="../bugs/snkrs-5/snkrs-5.md"><span style="white-space: nowrap;">SNKRS-5</span></a><br>
            <a href="../bugs/snkrs-6/snkrs-6.md"><span style="white-space: nowrap;">SNKRS-6</span></a><br>
            <a href="../bugs/snkrs-7/snkrs-7.md"><span style="white-space: nowrap;">SNKRS-7</span></a>
            </td>
        </tr>
        <tr>
            <td>
                <strong>Cenário:</strong> clicar na opção de menu correspondente à página atual.<br>
                <strong>Dado</strong> que estou em qualquer página da aplicação, <br>
                <strong>Quando</strong> clico na opção de menu referente à própria página que estou, <br>
                <strong>Então</strong> nada acontece e devo permanecer na página que estou. <br>
            </td>
            <td>Manual</td>
            <td>Aprovado</td>
            <td></td>
        </tr>
    </tbody>
</table>