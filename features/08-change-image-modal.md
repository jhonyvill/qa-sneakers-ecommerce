## Funcionalidade.
**Alterar imagem em destaque no modal de tela cheia.**

## User Story.
Como cliente,<br>
Quero alternar entre diferentes imagens de um produto,<br>
Para visualizar o produto de diferentes ângulos ou variações antes de tomar uma decisão.<br>

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
                <strong>Dado</strong> que estou no modal de visualização de imagens em tela cheia, <br>
                <strong>Quando</strong> clico na miniatura de imagem diferente da imagem que está em destaque, <br>
                <strong>Então</strong> a imagem clicada passa a ser a imagem em destaque, <br>
                <strong>E</strong> a miniatura da imagem clicada fica ofuscada. <br>
            </td>
            <td>Manual</td>
            <td>Aprovado</td>
            <td></td>
        </tr>
        <tr>
            <td>
                <strong>Dado</strong> que estou no modal de visualização de imagens em tela cheia, <br>
                <strong>Quando</strong> clico nas setas de navegação entre imagens, <br>
                <strong>Então</strong> a imagem em destaque deve ser alterada para a próxima ou anterior. <br>
            </td>
            <td>Manual</td>
            <td>Aprovado</td>
            <td></td>
        </tr>
        <tr>
            <td>
                <strong>Dado</strong> que estou no modal de visualização de imagens em tela cheia, <br>
                <strong>E</strong> a primeira imagem está em destaque, <br>
                <strong>Quando</strong> clico na seta de imagem anterior, <br>
                <strong>Então</strong> nada acontece e a imagem destacada permanece a mesma. <br>
            </td>
            <td>Manual</td>
            <td>Aprovado</td>
            <td></td>
        </tr>
        <tr>
            <td>
                <strong>Dado</strong> que estou no modal de visualização de imagens em tela cheia, <br>
                <strong>E</strong> a última imagem está em destaque, <br>
                <strong>Quando</strong> clico na seta de próxima imagem, <br>
                <strong>Então</strong> nada acontece e a imagem destacada permanece a mesma. <br>
            </td>
            <td>Manual</td>
            <td>Aprovado</td>
            <td></td>
        </tr>
    </tbody>
</table>