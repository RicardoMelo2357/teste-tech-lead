# Teste Prático para Tech Lead.

Este repositório foi criado com intuito de disponibilizar os pré-requisitos e o teste prático para se tornar um Tech Lead.

# Introdução.

Desenvolva um back-end e um front-end que contemple as atividades citadas abaixo.

Objetivo deste teste é avaliar questões como modelagem, aplicação de técnicas e conceitos de programação design patterns, organização, capricho e boas praticas.

# Requisitos.

* HTML 5
* JavaScript
* GitHub
* .NET
* ORACLE
* Entity FrameWork
* ADO .NET
* WCF.

# Atividade proposta.

Criar um projeto onde o back-end seja separado do front-end, ficando a criterio do desenvolvedor construir uma comunicação entre os 2 projetos.

Para o back-end: 

Criar um pequeno sistema de TMS (sistema de gerenciamento de transporte), onde seja possível fazer uma viagem. O sistema deverá contemplar as seguintes funcionalidades: 

* Carga  
O sistema deverá permitir criar uma carga, onde que para cada carga deva ter os seguintes campos: código da carga, peso, produto, quantidade origem e destino.
O código da carga deverá ser único, tendo sempre o prefixo de CA no começo de seu código, por exemplo : CA00001. 
O peso da carga deverá ser em KG ou Toneladas, caso o peso passe de 1000 KG, converter para toneladas, sendo exibido para o usuário 1 ton.  

* Motorista 
O Sistema deverá permitir que seja criado um motorista, onde para tal será necessário os seguintes campos: 
Nome, CPF, Tipo de Habilitação (A, B, C, D ou E). 

* Rota
O sistema deve permitir a criação das rotas de um ponto A ao ponto B.  

* Veículo. 
O sistema deverá também permitir a criação de um veículo. Onde seja possível identificar o modelo, placa e ano.  

* Criar viagem 
Para se criar uma viagem, o sistema deve utilizar as informações anteriores.

Todas as funcionalidades descritas anteriormente deverá contemplar o CRUD e também os status (disponível ou ultilizado). Ao criar a viagem efetuar as devidas validações, onde só será possível criar ao compor uma viagem com todas as funcionalidades disponíveis.



Para o Front-end: 

Já front end, o sistema deverá ter uma tela para cada funcionalidade descrita anteriormente, onde para cada tela, será necessário contemplar o crud, ter status e validações. 

# Critérios de avaliação

Caso o projeto entregue seja enviado com todos os critérios acima, serão levados em consideração também os seguintes conhecimentos:

Entendimento de design patterns, Orientação a Objeto e outros conceitos relacionados.
Uso de controle de versão.
Ferramentas utilizadas.
Reuso do código.
Comentários.
Organização do código.
Testes.

# Processo de submissão

O código deve ser disponibilidade no Git Hub com instruções de como rodar o projeto detalhadamente.
