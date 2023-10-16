<img src='/img/logo.png' alt='logo da empresa' width='150px' heidth='150px'/>

# *FIBONACCI MANAGEMENT SYSTEM*

# PROJETO DE SOFTWARE

## *Stakeholders*
|NOME|CARGO|E-MAIL|
|:---|:---|:---|
|Fernada Gonçalves da Costa|Desenvolvedora-Líder|fernandagoncalvesdacosta9094@gmail.com|
|Wanda Pereira da Costa|Desenvolvedora|pereirawanda131@gmail.com|
|Aline Noemerg Grey|Desenvolvedora|noemerggrey@gmail.com|
|Pedro Noemerg De Andrade|Desenvolvedor|pedronoemerg10@gmail.com|
|Kewrison Luan Caminha Rodrigues|Desenvolvedor|luan.caminha124@gmail.com|
|Pedro Henrique Baltazar da Silva| Desenvolvedor|pedrohenriquebaltazar5@gmail.com| 
>>>>>>> 927f18c418f46e25f9eedcc929c58b4db11c2c25

# Sumário

* [RESUMO DO PROJETO](#resumo-do-projeto)
* [INTRODUÇÃO](#introdução)
  * [PROPÓSITO DESTE DOCUMENTO](#propósito-deste-documento)
  * [ESCOPO DO PROJETO](#escopo-do-projeto)
  * [CONCEPÇÃO DO SISTEMA](#concepção-do-sistema)
  * [CONVENÇÕES, TERMOS E ABRIVEAÇÕES](#convenções-termos-e-abreviações)
* [DESCRIÇÃO GERAL](#descrição-geral)
  * [USUÁRIOS DO SISTEMA](#usuários-do-sistema)
  * [ABRANGÊNCIA E SISTEMAS SIMILARES](#abrangência-e-sistemas-similares)
  * [SUPOSIÇÕES E DEPENDÊNCIAS](#suposições-e-dependências)
* [ESTUDO DE VIABILIDADE](#estudo-de-viabilidade)
  * [VIABILIDADE TÉCNICA](#viabilidade-técnica)
  * [VIABILIDADE ECONÔMICA](#viabilidade-econômica)
  * [VIABILIDADE ORGANIZACIONAL](#viabilidade-organizacional)
* [METODOLOGIA ADOTADA NO DESENVOLVIMENTO](#metodologia-adotada-no-desenvolvimento)
* [REQUISITOS DO SOFTWARE](#requisitos-do-software)
  * [REQUISITOS FUNCIONAIS](#requisitos-funcionais)
  * [REQUISITOS NÃO FUNCIONAIS](#requisitos-não-funcionais)
* [PROTOTIPAGEM](#prototipagem)
* [DIAGRAMA DE CASOS DE USO](#diagrama-de-casos-de-uso)
  * [ESPECIFICAÇÃO DOS CASOS DE USO](#descrição--especificação-dos-casos-de-uso)
* [DIAGRAMA DE CLASSES](#diagrama-de-classes)
* [DIAGRAMA DE SEQUÊNCIAS](#diagrama-de-sequências)
* [ DIAGRAMA DE ATIVIDADES](#diagrama-de-atividades)
* [REFERÊNCIAS](#referências)


# RESUMO DO PROJETO
| ITEM | DESCRIÇÃO|
|:---|:---|
| NOME DO PROJETO | Home's Moti |
| GERENTE DO PROJETO | Fernada Costa |
| PRINCIPAL OBJETIVO | Venda de sovertes para toda a população de forma rapida e pratica, proporcionar a experiencia de estar em um ambiente aconchegante e com diversas opções|
| BENEFÍCIOS ESPERADOS |* Melhor forma de atendimento<br/>* Mais opções de sabores;<br/>* Melhor forma de entrega ao cliente;<br/>*Acessibilidade ao cliente;<br/>* Automatização dos pedidos|
| INÍCIO E TÉRMINO PREVISTOS | 14/03/2023 - 07/12/2023 |

[ [INÍCIO](#fibonacci-management-system) ]

# INTRODUÇÃO

## PROPÓSITO DESTE DOCUMENTO

Este documento destina-se aos clientes, engenheiros, gerentes e demais stakeholders deste projeto. O propósito deste documento é apresentar a descrição dos serviços e funções que o sistema **_Moti_** deve prover, bem como as suas restrições de operação e propriedades gerais, a fim de ilustrar uma descrição detalhada do sistema para um auxílio durante as etapas de análise, projeto e testes. O documento especifica todos os requisitos funcionais e não funcionais do sistema e contém a prototipagem, além de diagramas UML que foram construídos levando-se em conta as funcionalidades identificadas durante a fase de concepção do sistema.

## CONCEPÇÃO DO SISTEMA

A proposta surgiu como um trabalho de fundamento do professor Wagner Ferreira, de uma de suas aulas. Escolhemos o tema de sorveteria online pelo motivo de ser algo que todos temos conhecimentos, e ser um diferencial no ramo dos laticinios. Teriamos diversas opções para desenvolviento, teria uma facil manutenção e atualização.


## CONVENÇÕES, TERMOS E ABREVIAÇÕES

Para evitar interpretações incorretas deste documento, algumas convenções e termos específicos são descritos a seguir:

* EaD: Eaducação a Distância
* Moodle: Ambiente Virtual que hospedará os cursos oferecidos
* Exame Final: Avaliação destinada aos estudantes que obtiveram média anual inferior à 60 pontos

[ [INÍCIO](#fibonacci-management-system) ]

# DESCRIÇÃO GERAL

## ESCOPO DO PROJETO

### NO ESCOPO

O projeto consiste em uma sorveteria online chamada "Home's Moti" temos o melhor atendimento a distância e pode ser de qualquer lugar. Com sabores diversificados e com um preço justo de acordo com o tamanho do seu pedido. A entrega na residência não tem frete. Essa ferramenta pode ser utilizada tanto pelos clientes quanto pelos funcionários. O cliente monta seu próprio sorvete utilizando as ferramentas do aplicativo e o funcionário monta o pedido de acordo com os requisitos mandados. O funcionário confirma o pedido e manda para a residência do cliente. O site é de fácil acesso ao cliente e bem estruturado [requisitos do software](#requisitos-do-software)

### FORA DO ESCOPO

Não fazem parte do escopo do projeto:
* Não trabalhamos com avaliação do pedido e do produto;
* Não temos barra de pesquisa;
* A aplicação não aceita reembolso.

## Usuários do sistema
|USUÁRIO|DESCRIÇÃO|
|:---|:---|
|**Usuário Padrão:**|Realizam as tarefas comuns a todos os usuários, tal como: logar e enviar mensagens. Todos demais usuários estendem as funcionalidades do UsuárioPadrão|
|**Administrador:**|Responsáveis pelo gerenciamento das entidades pertinentes à instituição e pela alocação de outros administradores|
|**Coordenador:**|Responsáveis pela aprovação de disciplinas, turmas e matrículas realizadas pela secretaria do curso, além de ser responsável pela alocação da secretaria|
|**Secretaria:**|Responsáveis pelo cadastramento de disciplinas e turmas, pela alocação de professores e monitores de um curso e matrículas dos alunos|
|**Professor:**|Responsáveis pela criação do programa da disciplina através de ferramentas de planejamento e criação de atividades|
|**Aluno:**|Seguem o programa da disciplina criada pelo professor, tendo como apoio ferramentas de comunicação, tal como: chat e fórum|

## Abrangência e sistemas similares

### Abrangência:

O sistema irá conter ferramentas para construção de um plano de aulas que esteja de acordo com os objetivos e metodologia de uma turma ministrada pelo professor. O professor através de ferramentas (como Chat, Fórum, Base de Documentos) irá montar o programa desta disciplina que deverá ser seguido pelo aluno usuário do sistema. O professor terá a liberdade de criar atividades (textos e questionários) e determinar prazos a serem cumpridos pelos alunos. Serão armazenadas as resoluções dos alunos para serem corrigidas pelo professor posteriormente, gerando estatísticas do desempenho de cada aluno e da turma. O sistema também irá prover o gerenciamento das entidades que compõem a instituição e os usuários do sistema.

Dentre as ferramentas de comunicação do sistema existirão as assíncronas, como Chat, onde poderão ser feitas reuniões, discussões, explicações conjuntas ou qualquer outra atividade de comunicação. O Fórum consiste na ferramenta síncrona usada para os mesmos fins do Chat.

Das ferramentas de planejamento podemos citar:

* **Avaliações e Exercícios:** serão criadas tarefas a serem entregues pelos alunos nos determinados prazos;

* **Anúncios:** espaço para criação de avisos e informes aos alunos de uma determinada turma;

* **Manipulação de Arquivos:** haverá um diretório onde podem ser acumulados arquivos de diversos tipos pelos usuários;

* **Planejamento de Aulas:** planejamento de uma aula estruturada com leituras e exercícios.

### Sistemas similares:

No cenário atual da universidade se encontra um sistema que é responsável por realizar tal tarefa, denominado Virtus, porém o sistema não atende todas as necessidades, não sendo considerado satisfatório pela maioria dos usuários.

No cenário nacional encontram-se três sistemas que se destacam:

**AulaNet:** é um ambiente de software baseado na Web, desenvolvido no Laboratório de Engenharia de Software - LES - do Departamento de Informática da PUC-Rio, para administração, criação, manutenção e participação em cursos à distância.
WebAula: é um produto formado por soluções integradas de gerenciamento de aprendizagem, conhecimento e conteúdos on-line, resultado de uma joint venture entre as empresas Zargon e Poliedro.

**TelEduc:** é um ambiente para a criação, participação e administração de cursos na Web. Ele foi concebido tendo como alvo o processo de formação de professores para informática educativa, baseado na metodologia de formação contextualizada desenvolvida por pesquisadores do Nied (Núcleo de Informática Aplicada à Educação) da Unicamp.

No cenário internacional os sistemas de maior porte são:

**WebCT:** O WebCT é um programa que possibilita a criação de ambientes educacionais na Internet, desenvolvido pela University of British Columbia - Canadá. Ele permite a colocação do conteúdo de um curso na Internet pelo professor e, em seguida, o cadastro os alunos que participarão daquele curso. O objetivo principal é possibilitar a interação entre tais sujeitos através de ferramentas de trabalho em grupo, tais como: fóruns de discussão, chat, palestras on-line, além de facilitar a comunicação professor-aluno, através da publicação de notas e gabaritos de avaliações.

**Blackboard:** é um sistema de autoria extremamente amigável, desenvolvido para ser utilizado por educadores e profissionais interessados em aplicar as novas tecnologias interativas da rede na educação, contribuindo para a metodologia de ensino presencial e potencializando o processo de ensino e aprendizagem a distância.

## Suposições e dependências
O sistema necessita de um servidor web para sua hospedagem.

Os usuários devem utilizar um computador com a seguinte configuração mínima:

* Processador Dual Core 2GHz ou superior
* 2Gb de memória RAM
* 5Gb de armazenamento em disco
* Para uso do sistema é preciso ter instalado o Java SE versão 8 e o MySql versão 8.0.28.

# ESTUDO DE VIABILIDADE

Uma vez definidos a necessidade para o sistema e seus requisitos de negócio, é possível compreender melhor o projeto do sistema proposto para elaborar o estudo de viabilidade com os seguintes destaques:

## Viabilidade Técnica
**Requisitos de Software e Desenvolvimento:** determinar quais funcionalidade são necessárias para o nosso site(Sweet Mochi), por exemplo: exibir o menu, calcular preços, fornecer informações sobre a entrega e etc.

**Design e Usabilidade:** fornecer um design acolhedor e um layout com facilidade na usabilidade do site, certificando que o cliente não terá nenhuma frustração com a sorveteria.

**Cardápio online:** Apresentar de forma clara e atraente o cardápio de sorvetes e outros produtos oferecidos, incluindo descrições, fotos de alta qualidade e preços.

**Sistema de pedidos online:** Implementar um sistema de pedidos online que permita aos clientes escolher seus produtos, personalizá-los e efetuar o pagamento de forma conveniente.

Integração de pagamento seguro: Garantir que o site tenha uma integração segura para processar os pagamentos online, protegendo as informações financeiras dos clientes.
**Integrações:** os pedidos onlines é preciso de uma integração de sistemas de pagamentos como por exemplo o PayPal, também de Redes sociais para usá-las como ferramenta de marketing.

**Localização e Entrega:** a sorveteria oferece serviços de entrega, integra ferramentas de localização para que os clientes possam inserir seus endereços e calcular a taxa de entrega. Planeje também como os pedidos serão rastreados e entregues eficientemente.

**Aspectos Legais e Regulatórios:** Cumpra todas as regulamentações locais, estaduais e nacionais relacionadas à venda de alimentos online, incluindo licenças de alimentos, regulamentos de segurança alimentar e impostos.



## Viabilidade Econômica

**Análise de Custo-Benefício:** Realize uma análise detalhada dos custos envolvidos na criação e operação da sorveteria online, incluindo custos de produção, marketing, manutenção do site, embalagens e logística.

**Custo-benefício aproximado:** Usando o investimento inicial de aproximadamente R$80 mil. 
Destinamos 5 mil reais a aluguel, água, luz e internet.
com a compra de no mínimo 8 freezer de 415 L no valor aproximado de 4 mil.
custo de 6 funcionários com o ganho de 1,800 totalizando 10,800 reais.
10 mil ficarão para complementos e embalagens.
mil reais para ingredientes para sorvete artesanal e 5 mil reais em sorvete industrial.
Até agora usamos 61.800, sobrando 18.200 para imprevistos e custos adicionais de estoque, network e imprevistos. levando em consideração a meta de 300 vendas ao mês o lucro mensal seria aproximadamente de 15 mil ao mês, ressarcindo o custo inicial em menos de 6 meses.
Isso determina a viabilidade de nossa sorveteria com um investimento mínimo.


## Viabilidade Organizacional

Do ponto de vista das pessoas que trabalham na nossa sorveteria (Sweet Home). Espera-se que os funcionários e clientes tenham acesso aos sites ou ao local de maneira compreensível para que até mesmo pessoas que possuem deficiência consigam ter acesso de maneira fácil à comunidade ao todo, com analfabetos digitais que possui dificuldade ao acessar o site ou pessoas com dificuldade em comunicação, por isso o site apresenta baixo risco de rejeição pois tem praticidade em seu uso com software estruturado possuindo atualizações sempre visando em melhorar.


[ [INÍCIO](#fibonacci-management-system) ]

# Metodologia Adotada no Desenvolvimento


**Modelo em Cascata:** Uma abordagem sequencial, onde cada fase do projeto é concluída antes de passar para a próxima. Geralmente é adequada para projetos com requisitos estáveis e bem definidos.

# Requisitos do Software

A especificação dos requisitos deste documento deve seguir as recomendações da norma IEEE Std-830-1998, levando em conta as recomentações do documento de [características dos requisitos](caracteristicas_requisitos.md).

## Requisitos Funcionais

A tabela a seguir contém a relação dos Requisitos Funcionais elicitados, com as colunas: identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
:---|:---|:---|
|RF-001 |Sistema de cadastro de usuários |Essa função irá direcionar os clientes para eles cadastrarem no site e realizarem seus pedidos com suas informações pessoais |
|RF-002 | Sistema para entrada sem usuario | Existe momentos que o cliente quer fazer um pedido simples e rapido sem um dadastro e ele poderá com essa função acessar o site de forma facil e rápida |
|RF-003 |Carrinho de compras |Deve permitir que os clientes adicionem sorvetes ao carrinho de compras, visualizem o resumo do pedido, modifiquem as quantidades e removam itens indesejados |
|RF-004 |Catálogo com os nossos produtos | Servir como cardapio, contendo nossos diversos produtos que compoem o sorvete perfeito para cada cliente |
|RF-005 | Sistema de Self-service | Serve para que o cliente monte seu própio sorvete, colocando itens a mais no seu sorvete e montando da forma que lhe caiba bem |
|RF-006 | Sistema de entrega | Na finalização da compra o cliente preeencherá uma barra colando os requisitos do endereço, para que o entregue o sorvete no endereço que foi solicitado |
|RF-007 | Sistema de Timing | Quando o cliente finalizar o seu pedido, irá começar um cronometro desde o momento em que seu pedido foi encaminhado e será enviado uma notificação e quando o produto ficar pronto e outra quando o produto estiver a caminho |
|RF-008 | Recuperação de cadastro  | No momento em que o cliente não relembra os dados de seu cadastro para refazer login, ele poderá tentar recuperar usando o email que foi cadastrado anteriormente |
|RF-009 | Sorveteria física  | O cliente poderá tomar o sorvete na sorveteria física ou fazer seu pedido na loja online mas buscar seu pedido na loja física |
|RF-010 | Sistema de  Promoções  |  a sorveteria terá promoções  de  feriados importantes, ex: dia das mães, dia dos pais e etc. |




## Requisitos Não Funcionais
A tabela a seguir contém a relação com os Requisitos Não Funcionais identificados, contendo identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
|:---|:---|:---|
|RNF-001 | INTEROPERABILIDADE | O sistema deve estar ligado com outros sistemas que possibilitam o pagamento, como: paypal, google pay, pix e mercado pago.|
|RNF-002 | PORTABILIDADE | O sistema deve rodar nos principais navegadores: Chrome, Firefox, Opera, Safari e também deve ser suportável nas versões mais recentes de Android e IOS.|
|RNF-003 | DESEMPENHO | Deve carregar cada página com um tempo máximo de 3 segundos.|
|RNF-004 | IMPLEMENTAÇÃO | O sistema deve estar disponível em navegadores e para download em computadores e smartphones.|
|RNF-005 | DISPONIBILIDADE | O sistema deve estar indisponível enquanto o estabelecimento estiver fechado.|
|RNF-006 | ESPAÇO | Para download, será necessário um espaço mínimo de 675Mb.|
|RNF-007 | ÉTICO | O sistema deve tratar os dados de cada usuário apenas para finalidade de venda dos produtos desejados.|
|RNF-008 | INTERFACE SIMPLES |  O sistema deve conter uma interface de fácil visualização e navegação.|
|RNF-009 | PRIVACIDADE | O sistema deve proteger os dados de seus clientes de acordo com o que a lei determina.|
|RNF-010 | INTEROPERABILIDADE NO LOGON | Permitir que usuário possa criar seu cadastro através de outros sites, como google e facebook.|


[ [INÍCIO](#fibonacci-management-system) ]


# Prototipagem

[Protótipo Sorveteria Moti's Sweet Home](https://www.figma.com/file/DvGAQNCjLqoI3tZqaDpeAO/Moti's-Sorveteria?type=design&node-id=0%3A1&mode=design&t=OgwfCDHpTxQGFcUR-1)

![Imagem do Protótipo](/img/tela1.png)

[ [INÍCIO](#fibonacci-management-system) ]


# Diagrama de Casos de Uso


![Diagrama de Casos de Uso](/img/use_case_placas.png)

## Descrição / Especificação dos Casos de Uso

### UC-01 - Cadastrar Professor

|UC-01 - Cadastrar Professor|           
|:---|
|**Descrição/Objetivo:** Permite a inclusão de novos professores no Sistema|
|**Atores: Administrador**|
|**Pré-condições:** O usuário precisa estar cadastrado e logado|
|**Pós-condições:** Será apresentada uma mensagem confirmando a realização do cadastro|
|**FLUXO PRINCIPAL / BÁSICO:**|
|1. O usuário seleciona a opção cadastrar professor|
|2. Os dados do professor são inseridos|
|3. O usuário clica em salvar|
|4. Um novo ID é gerado |
|5. É apresentada uma mensagem confirmando a realização do cadastro|
|**FLUXOS ALTERNATIVOS / EXCESSÕES:** |
|**A1: Campo obrigatório não preenchido** |
|1. Uma mensagem será apresentada para o usuário, informando que existe(m) campos obrigatórios que não foram preenchidos |
|2. O cursor será posicionado no primeiro campo obrigatório que não foi preenchido |
|**A2: Data de nascimento inválida** |
|1. Uma mensagem será apresentada para o usuário, informando que a data informáda não é válida|
|2. O cursor será posicionado para o campo data|


## Matriz de Rastreabilidade


| Requisito | Selecionar Cliente | Cadastro do Produto | Implementado no site | Fora do site | Integrado ao app mobile | Integrado ao sistema de banco de dados | Efetuar venda |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RF-001 - Cadastro de Usuários | X | X | X |  | X | X | X |
| RF-002 - Entrada sem Usuário |  |  |  |  | X |  |  |
| RF-003 - Carrinho de Compras |  | X | X |  | X | X | X |
| RF-004 - Catálogo de Produtos |  | X | X |  | X | X | X |
| RF-005 - Sistema de Self-service |  | X | X |  | X |  | X |
| RF-006 - Sistema de Entrega |  | X | X | X |  | X | X |
| RF-007 - Sistema de Timing |  | X |  | X | X |  | X |
| RF-008 - Recuperação de Cadastro | X |  |  |  | X | X |  |
| RF-009 - Sorveteria Física |  | X | X | X |  |  |  |
| RF-010 - Sistema de Promoções |  |  |  | X | X | X | X |



[ [INÍCIO](#fibonacci-management-system) ]

# Diagrama de Classes

![Diagrama de Classes](/img/DiagramaDeClasses.png)

# Diagrama de Sequências

[ [Pedro B](/img/OIi.png) ]

# Diagrama de Atividades


# REFERÊNCIAS

Esta subseção apresenta as referências aos documentos que utilizamos no auxílio à construção deste documento.
* [UML](https://www.omg.org/spec/UML/2.5/About-UML/)
* [Práticas para Especificação de Requisitos IEEE-830](https://ieeexplore.ieee.org/document/720574)
