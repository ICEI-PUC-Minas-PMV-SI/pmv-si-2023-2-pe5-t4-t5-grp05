# Programação de Funcionalidades


## Requisitos Atendidos

As tabelas que se seguem apresentam os requisitos funcionais e não-funcionais que relacionam o escopo do projeto com os artefatos criados:

### Requisitos Funcionais

|ID    | Descrição do Requisito | Prioridade | Artefato Criado |
|------|------------------------|------------|-----------------|
|RF-001| O sistema deve permitir que os usuários se registrem fornecendo um nome de usuário, senha e endereço de e-mail. | ALTA | cadastro.html |
|RF-002| Deve haver validação de dados para garantir que o endereço de e-mail seja único.  | ALTA | cadastro.html |
|RF-003| Os usuários devem poder fazer login usando seu nome de usuário e senha registrados. |ALTA| login.html |
|RF-004| O sistema deve exibir uma lista de animais disponíveis para adoção, incluindo fotos, nomes e descrições. |ALTA| match.html/catálogo.html |
|RF-005| Deve ser possível filtrar os animais por tipo (cães, gatos, etc.). |MÉDIA| chatusuarioParaEmpresa.html|
|RF-006| Os usuários devem poder ver o perfil de animal para dar match. |MÉDIA| match.html |
|RF-007| Cada perfil de animal deve incluir um botão de "Contatar" que permita aos usuários enviar mensagens. |BAIXA| match.html |
|RF-008| Deve haver uma caixa de entrada de mensagens onde os usuários possam acompanhar suas conversas. |BAIXA|chatusuarioParaEmpresa.html|
|RF-009| O sistema deve coletar informações sobre as preferências dos usuários, como tipo de animal desejada. | MÉDIA |chatusuarioParaEmpresa.html|
|RF-0010| Com base nas preferências do usuário, o sistema deve recomendar animais compatíveis para adoção na página home. | MÉDIA |match.html|
|RF-0011| Os usuários podem atualizar suas preferências a qualquer momento. | MÉDIA | chatusuarioParaEmpresa.html |
|RF-0012| A instituição tem que ser capaz de colocar os animais. | ALTA | Upload.html |
## Descrição das estruturas:

## Notícia
|  **Nome**      | **Tipo**          | **Descrição**                             | **Exemplo**                                    |
|:--------------:|-------------------|-------------------------------------------|------------------------------------------------|
| Id             | Numero (Inteiro)  | Identificador único da notícia            | 1                                              |
| Título         | Texto             | Título da notícia                         | Sistemas de Informação PUC Minas é o melhor                                   |
| Conteúdo       | Texto             | Conteúdo da notícia                       | Sistemas de Informação da PUC Minas é eleito o melhor curso do Brasil                            |
| Id do usuário  | Numero (Inteiro)  | Identificador do usuário autor da notícia | 1                                              |

