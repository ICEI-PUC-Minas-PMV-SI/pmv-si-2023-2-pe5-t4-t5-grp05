# Especificações do Projeto

A adoção de animais é importante não só para a diminuição do número de animais abandonados, mas também para a qualidade de vida dos tutores. Uma das dificuldades que os adotantes enfrentam é ter acesso aos animais, pensando nisso iremos desenvolver uma plataforma que permita ao usuário ter acesso a uma lista de animais para possível adoção mediante ao cadastro do usuário. 
A plataforma permitirá ao usuário filtrar os animais desejados, entre cães e gatos. Ao usuário será apresentada uma lista de animais, de acordo com suas especificações, onde será possível ver fotos e ler sobre detalhes sobre o animal desejado. A plataforma permitirá atendimento via contato direto com os responsáveis pelo resgate do animal para que seja tirada dúvidas e para que a adoção seja realizada. A plataforma permitirá ainda que a organização obtenha relatórios sobre as preferências dos usuários. A plataforma será desenvolvida usando HTML, CSS e JavaScript.


## Personas

Roberto e Flávia são recém casados e acabaram de comprar um apartamento. Ambos são funcionários públicos e não possuem filhos. Buscam um cachorro pequeno como animal de companhia. O animal deve ser de pequeno porte devido às dimensões do apartamento. 

A família Silva é uma família formada por pai, mãe, um filho e uma filha. Como moram em casa procuram um cachorro de grande porte para cuidar do terreno e fazer companhia para o seu outro cachorro. 

Helena é uma profissional liberal de 35 anos, solteira, que acabou de se mudar para uma grande cidade e se sente sozinha. Está à procura de um gato para lhe fazer companhia e sente que a adoção é o melhor caminho já que entende que existe muita crueldade nos criadores. 

Mario, 32, e Luiza, 30, acabaram de ter um filho. Moram em uma casa com pouco espaço e procuram um animal para fazer companhia tanto para Luiza que trabalha em casa quanto para a criança, ambos acreditam que é benéfico para as crianças terem contato com animais desde cedo. 


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
|RF-005| Deve ser possível filtrar os animais por tipo (cães, gatos, etc.). |MÉDIA||
|RF-006| Os usuários devem poder clicar em um perfil de animal para obter mais detalhes. |MÉDIA||
|RF-007| Cada perfil de animal deve incluir um botão de "Contatar" que permita aos usuários enviar mensagens. |BAIXA||
|RF-008| Deve haver uma caixa de entrada de mensagens onde os usuários possam acompanhar suas conversas. |BAIXA||
|RF-009| O sistema deve coletar informações sobre as preferências dos usuários, como tipo de animal desejada. | MÉDIA ||
|RF-0010| Com base nas preferências do usuário, o sistema deve recomendar animais compatíveis para adoção na página inicial. | MÉDIA ||
|RF-0011| Os usuários podem atualizar suas preferências a qualquer momento. | MÉDIA ||



### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| A interface de registro deve ser intuitiva e de fácil uso para garantir que os usuários possam se inscrever sem dificuldade. | ALTA ||
|RNF-002| O sistema deve armazenar os dados do usuários. | ALTA ||
|RNF-003| As imagens dos animais devem ser otimizadas para carregamento rápido. | MÉDIA ||
|RNF-004| O algoritmo de recomendação deve ser eficiente e fornecer resultados relevantes. | MÉDIA ||
|RNF-005| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA ||



## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|R-001|  O projeto deverá ser entregue até o final do semestre, isso pode limitar o escopo do projeto e afetar a quantidade de recursos.|
|R-002|  Restrições de determinadas tecnologias ou plataformas devido a considerações técnicas ou de segurança.|
|R-003|  A disponibilidade do pessoal.|

