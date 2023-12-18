# Testes

# Teste de Software


## Plano de Testes de Software


**Caso de Teste** | **CT01 **
 :--------------: | ------------
**Procedimento**  | 1) Usuário informa nome, sobrenome, email, senha e clica no botão "Continuar".<br>2) A aplicação verifica se os dados são válidos e informa ao usuário caso não sejam.
**Requisitos associados** | RF-001 RF-002
**Resultado esperado** | Prosseguir para a parte 2 do cadastro.
**Dados de entrada** | Inserção de dados válidos no formulário de cadastro.
**Resultado obtido** | Sucesso.
 :--------------: | ------------
 **Procedimento**  | 2) Usuário informa email e senha e clica no botão "Continuar".<br>2) A aplicação verifica se os dados são válidos e informa ao usuário caso não sejam.
**Requisitos associados** | RF-003
**Resultado esperado** | Entrar no site.
**Dados de entrada** | Inserção de dados válidos no formulário de cadastro.
**Resultado obtido** | Sucesso.
 :--------------: | ------------
**Procedimento**  | 3) Deve ser possível filtrar os animais por tipo (cães, gatos ou ambos).<br>2) A aplicação troca as preferências do usuário.
**Requisitos associados** | RF-005
**Resultado esperado** | Escolha de preferência.
**Dados de entrada** | Inserção de preferência.
**Resultado obtido** | Sucesso.
 :--------------: | ------------
 **Procedimento**  | 4) Deve haver uma caixa de entrada de mensagens onde os usuários possam acompanhar suas conversas.<br>2) A aplicação permite falar com a instituição.
**Requisitos associados** | RF-008
**Resultado esperado** | Falar com a instituição.
**Dados de entrada** | Inserção de mensagens.
**Resultado obtido** | Sucesso.
:--------------: | ------------
 **Procedimento**  | 5) Deve haver uma página para upload.<br>2) A aplicação permite a instituição a colocar os animais.
**Requisitos associados** | RF-0012
**Resultado esperado** | Fazer upload dos animais.
**Dados de entrada** | Inserção de animais.
**Resultado obtido** | Sucesso.




## Registro dos Testes de Software

O vídeo com as demonstrações está em ![Video](docs/Video.zip)

|                                 |*TC-01 - Criar uma conta                                        |
|---|---|
|Requisito Associado | RF-002 - Usuários não autenticados podem se cadastrar para criar uma conta e serem autenticados.|
|Link do vídeo do teste realizado: | ![Video](docs/Video.zip)| 

|                                |*TC-02 - Efetuar Login (usuário autenticado)                                         |
|---|---|
|Requisito Associado | RF-003 - Usuários não autenticados podem se cadastrar para criar uma conta e serem autenticados.|
|Link do vídeo do teste realizado: |  ![Video](docs/Video.zip) | 

|                                |*TC-03 - Filtrar animais                                        |
|---|---|
|Requisito Associado | RF-005 - Usuários poderão filtrar os animais por tipo.|
|Link do vídeo do teste realizado: |  ![Video](docs/Video.zip) | 

|                                |*TC-04 - Comunicar/chat                                        |
|---|---|
|Requisito Associado | RF-008 - Usuários devem ser capzes de comunicar com a instituição.|
|Link do vídeo do teste realizado: |  ![Video](docs/Video.zip) | 

|                                |*TC-05 - Upload                                         |
|---|---|
|Requisito Associado | RF-0012 - A instituição deve ser capaz de colocar os animais.|
|Link do vídeo do teste realizado: |  ![Video](docs/Video.zip) | 



## Avaliação dos Testes de Software

 Por utilizar ferramentas do novo Javascript disponível e atualizado dos novos browsers o site talvez não seja capaz de rodar em todos os dispositivos. Precisamos melhorar a experiência do usuário e sua permanência no site melhorando as características dos pets fazendo com o o pet mais indicado para a pessoa seja encontrado com mais facilidade. Também é necessário expandir a aplicação fazendo com que seja possivel concentrar mais organizações e também melhorar os parametros de segurança pois os atuais não são o suficiente.



# Testes de Usabilidade

O objetivo do Plano de Testes de Usabilidade é obter informações quanto à expectativa dos usuários em relação à  funcionalidade da aplicação de forma geral.

Para tanto, elaboramos quatro cenários, cada um baseado na definição apresentada sobre as histórias dos usuários, definido na etapa das especificações do projeto.

Foram convidadas quatro pessoas que os perfis se encaixassem nas definições das histórias apresentadas na documentação, visando averiguar os seguintes indicadores:

Taxa de sucesso: responde se o usuário conseguiu ou não executar a tarefa proposta;

Satisfação subjetiva: responde como o usuário avalia o sistema com relação à execução da tarefa proposta, conforme a seguinte escala:

1. Péssimo; 
2. Ruim; 
3. Regular; 
4. Bom; 
5. Ótimo.

Tempo para conclusão da tarefa: em segundos, e em comparação com o tempo utilizado quando um especialista (um desenvolvedor) realiza a mesma tarefa.

Objetivando respeitar as diretrizes da Lei Geral de Proteção de Dados, as informações pessoais dos usuários que participaram do teste não foram coletadas, tendo em vista a ausência de Termo de Consentimento Livre e Esclarecido.


Apresente os cenários de testes utilizados na realização dos testes de usabilidade da sua aplicação. Escolha cenários de testes que demonstrem as principais histórias de usuário sendo realizadas. Neste tópico o grupo deve detalhar quais funcionalidades avaliadas, o grupo de usuários que foi escolhido para participar do teste e as ferramentas utilizadas.



## Cenários de Teste de Usabilidade

| Nº do Cenário | Descrição do cenário |
|---------------|----------------------|
| 1             | Você é uma pessoa que deseja adotar um bichinho. Encontre no site um cachorro da personalidade que você desejar. |
| 2             | Você é uma pessoa que deseja ter um gato. Encontre no site um gato. |



## Registro de Testes de Usabilidade

Cenário 1: Você é uma pessoa que deseja adotar um bichinho. Encontre no site um cachorro da personalidade que você desejar.

| Usuário | Taxa de sucesso | Satisfação subjetiva | Tempo para conclusão do cenário |
|---------|-----------------|----------------------|---------------------------------|
| 1       | SIM             | 5                    | 32 segundos                  |
| 2       | SIM             | 5                    | 38 segundos                  |
| 3       | SIM             | 5                    | 26 segundos                  |
|  |  |  |  |
| **Média**     | 100%           | 5                | 32 segundos                           |
| **Tempo para conclusão pelo especialista** | SIM | 5 |9 segundos |


    

Cenário 2:  Você é uma pessoa que deseja ter um gato. Encontre no site um gato.

| Usuário | Taxa de sucesso | Satisfação subjetiva | Tempo para conclusão do cenário |
|---------|-----------------|----------------------|---------------------------------|
| 1       | SIM             | 5                    | 40 segundos                          |
| 2       | SIM             | 5                    | 38 segundos                          |
| 3       | SIM             | 5                    | 32 segundos                          |
|  |  |  |  |
| **Média**     | 100%           | 5                | 0 segundos                           |
| **Tempo para conclusão pelo especialista** | SIM | 5 | 36 segundos |


   A página principal poderia ser melhor para acessar.



## Avaliação dos Testes de Usabilidade


Tomando como base os resultados obtidos, foi possível verificar que a aplicação web apresenta bons resultados quanto à taxa de sucesso na interação dos usuários, tendo em vista que os cenários propostos foram concluídos com sucesso.

Além disso, a aplicação obteve também uma elevada satisfação subjetiva dos usuários no momento que realizavam os cenários propostos. Prova são as médias das avaliações em cada um dos cenários, que variou entre 4 (bom) e 5 (ótimo).

Com relação ao tempo para conclusão de cada tarefa/cenário, notamos discrepância entre a média de tempo dos usuários e o tempo do especialista/desenvolvedor em todos os cenários. Tal discrepância, em certa medida, é esperada, tendo em vista que o desenvolvedor já tem prévio conhecimento de toda a interface da aplicação, do posicionamento dos elementos, lógica de organização das páginas, etc.

Contudo, tendo em vista que a diferença foi relevante (por exemplo,  segundos — média usuários — contra 32 segundos — especialista — no cenário um), e ainda os comentários feitos por alguns usuários, entendemos haver oportunidades de melhoria na usabilidade da aplicação.



