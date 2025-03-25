## Funcionalidade.
**Visualizar ações de perfil de usuário.**

## User Story.
Como cliente,<br>
Quero visualizar as informações do meu perfil,<br>
Para verificar e confirmar meus dados pessoais e informações de conta.<br>

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
                <strong>Cenário:</strong> verificar abertura do modal de informações do usuário ao clicar na miniatura de imagem de perfil.<br>
                <strong>Dado</strong> que estou autenticado, <br>
                <strong>Quando</strong> clico na miniatura de imagem do perfil, <br>
                <strong>Então</strong> um modal deve ser exibida, <br>
                <strong>E</strong> devo ver a opção “Ver informações de perfil”, <br>
                <strong>E</strong> devo ver a opção “Sair”. <br>
            </td>
            <td>Manual</td>
            <td>Reprovado</td>
            <td><a href="../bugs/snkrs-8/snkrs-8.md"><span style="white-space: nowrap;">SNKRS-8</span></a></td>
        </tr>
        <tr>
            <td>
                <strong>Cenário:</strong> fechar modal de informações do usuário com clique na miniatura de imagem de perfil.<br>
                <strong>Dado</strong> que estou autenticado, <br>
                <strong>E</strong> estou com o modal de perfil de usuário aberta, <br>
                <strong>Quando</strong> clico na miniatura de imagem do perfil, <br>
                <strong>Então</strong> o modal fecha. <br>
            </td>
            <td>Manual</td>
            <td>Aprovado</td>
            <td></td>
        </tr>
    </tbody>
</table>