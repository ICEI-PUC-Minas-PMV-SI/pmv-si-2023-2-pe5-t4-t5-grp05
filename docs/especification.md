# Especificações do Projeto

A adoção de animais é importante não só para a diminuição do número de animais abandonados, mas também para a qualidade de vida dos tutores. Uma das dificuldades que os adotantes enfrentam é ter acesso aos animais, pensando nisso iremos desenvolver uma plataforma que permita ao usuário ter acesso a uma lista de animais para possível adoção mediante ao cadastro do usuário. 
O site permitirá ao usuário filtrar os animais desejados, entre cães e gatos. Ao usuário será apresentada uma lista de animais, de acordo com suas especificações, onde será possível ver fotos e ler sobre detalhes sobre o animal desejado. O site permitirá atendimento via contato direto com os responsáveis pelo resgate do animal para que seja tirada dúvidas e para que a adoção seja realizada. O site permitirá ainda que a organização obtenha relatórios sobre as preferências dos usuários. A plataforma será desenvolvida usando HTML, CSS e JavaScript.


## Personas

Marcela é estudante e acabou de se mudar  para um apartamento. Ela busca um cachorro pequeno como animal de companhia. O animal deve ser de pequeno porte devido às dimensões do apartamento.

Juliana é casada e tem uma filha. Como mora em casa com sua família, ela procura um casal de cachorros para cuidar do terreno e fazer companhia para a sua filha, já que o casal acredita que é benéfico para a criança ter contato com animais desde cedo.

Eduardo é um profissional liberal de 27 anos, solteiro, que acabou de se mudar para uma grande cidade e se sente sozinho. Está à procura de um gato para lhe fazer companhia e sente que a adoção é o melhor caminho já que entende que existe muita crueldade nos criadores.

Tiago e sua esposa moram em uma casa grande e procuram tanto cachorros quantos gatos para adotarem.


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
| Roberto e Flávia   | Cachorro pequeno                   | Tamanho do apartamento                 |
| Família Silva      | Cachorro grande                    | Cuidar do terreno                      |
| Helena             | Gato                               | Companhia                              |
| Mario e Luiza      | Animal pequeno                     | Companhia                              |


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade | Responsável |
|------|-----------------------------------------|----| ----|
|RF-001| O sistema deve permitir que os usuários se registrem fornecendo um nome de usuário, senha e endereço de e-mail. | ALTA |  |
|RF-002| Deve haver validação de dados para garantir que o endereço de e-mail seja único.  | ALTA | |
|RF-003| Os usuários devem poder fazer login usando seu nome de usuário e senha registrados. |ALTA||
|RF-004| O sistema deve exibir uma lista de animais disponíveis para adoção, incluindo fotos, nomes e descrições. |ALTA||
|RF-005| Deve ser possível filtrar os animais por tipo (cães e gatos). |MÉDIA||
|RF-006| Cada perfil de animal deve incluir um botão de "Contatar" que permita aos usuários enviar mensagens. |BAIXA||
|RF-007| Deve haver uma caixa de entrada de mensagens onde os usuários possam acompanhar suas conversas. |BAIXA||
|RF-008| O sistema deve coletar informações sobre as preferências dos usuários, como tipo de animal desejado. | MÉDIA ||
|RF-009| Com base nas preferências do usuário, o sistema deve recomendar animais compatíveis para adoção na página inicial. | MÉDIA ||
|RF-0010| Os usuários podem atualizar suas preferências a qualquer momento. | MÉDIA ||




### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| A interface de registro deve ser intuitiva e de fácil uso para garantir que os usuários possam se inscrever sem dificuldade. | ALTA ||
|RNF-002| O sistema deve armazenar os dados do usuários. | ALTA ||
|RNF-003| As imagens dos animais devem ser otimizadas para carregamento rápido. | MÉDIA ||
|RNF-004| O algoritmo de recomendação deve ser eficiente e fornecer resultados relevantes. | MÉDIA ||




## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|R-001|  O projeto deverá ser entregue até o final do semestre, isso pode limitar o escopo do projeto e afetar a quantidade de recursos.|
|R-002|  Restrições de determinadas tecnologias ou plataformas devido a considerações técnicas ou de segurança.|
|R-003|  A disponibilidade do pessoal.|

