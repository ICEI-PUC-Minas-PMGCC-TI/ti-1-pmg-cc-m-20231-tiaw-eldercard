# Informações do Projeto

`TÍTULO DO PROJETO`  

Elder Card

`CURSO` 

Ciências da Computação PUC Minas

## Participantes

 Os membros do grupo são: 

- André Lemos Menezes
- Bernardo Ribeiro Godinho
- Edson Pimenta de Almeida
- Gustavo Vinicius Elias Souza Silva
- Patrick Junio Pereira de Oliveira
- Tales Rocha Moreira

# Estrutura do Documento

- [Informações do Projeto](#informações-do-projeto)
  - [Participantes](#participantes)
- [Estrutura do Documento](#estrutura-do-documento)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
  - [Justificativa](#justificativa)
  - [Público-Alvo](#público-alvo)
- [Especificações do Projeto](#especificações-do-projeto)
  - [Personas, Empatia e Proposta de Valor](#personas-empatia-e-proposta-de-valor)
  - [Histórias de Usuários](#histórias-de-usuários)
  - [Requisitos](#requisitos)
    - [Requisitos Funcionais](#requisitos-funcionais)
    - [Requisitos não Funcionais](#requisitos-não-funcionais)
  - [Restrições](#restrições)
- [Projeto de Interface](#projeto-de-interface)
  - [User Flow](#user-flow)
  - [Wireframes](#wireframes)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)
  - [Controle de Versão](#controle-de-versão)
- [**############## SPRINT 1 ACABA AQUI #############**](#-sprint-1-acaba-aqui-)
- [Projeto da Solução](#projeto-da-solução)
  - [Tecnologias Utilizadas](#tecnologias-utilizadas)
  - [Arquitetura da solução](#arquitetura-da-solução)
- [Avaliação da Aplicação](#avaliação-da-aplicação)
  - [Plano de Testes](#plano-de-testes)
  - [Ferramentas de Testes (Opcional)](#ferramentas-de-testes-opcional)
  - [Registros de Testes](#registros-de-testes)
- [Referências](#referências)


# Introdução

Contemporaneamente, verifica-se que com o grande avanço da tecnologia no cenário mundial, existem pessoas com dificuldade no seu uso, em sua maioria idosos. Nesse sentido, atualmente um dos maiores meios de inclusão social, comunicação,acesso à informação e entretenimento, ocorre pelo uso de dispositivos inteligentes como celulares, notebooks, TVs etc.., e as pessoas que têm dificuldade em seu uso, tendem a ter uma piora em sua qualidade de vida.

Paralelamente, o uso de dispositivos inteligentes pode trazer uma série de benefícios aos idosos. Em primeiro lugar, esses dispositivos podem melhorar sua comunicação, permitindo que eles se conectem com familiares, amigos e outras pessoas com maior facilidade. Além disso, esses dispositivos podem oferecer acesso a informações importantes, como notícias, serviços de saúde e informações de transporte, facilitando a vida cotidiana e mantendo os idosos atualizados sobre o que está acontecendo ao seu redor. Outro benefício é a possibilidade de maior autonomia e independência, tendo acesso a aplicativos e recursos que facilitam o gerenciamento de suas finanças, o planejamento de suas atividades diárias, e até mesmo a assistência em casos de emergência. Isso pode permitir que eles continuem a viver de forma independente e com qualidade de vida, mesmo com limitações físicas ou mobilidade reduzida.

Logo, é de extrema urgência a criação de um WebApp que instrua os idosos a utilizar esses dispositivos inteligentes de forma que seu uso seja uma ferramenta valiosa para que eles possam usufruir de uma melhor qualidade de vida.


## Problema

De acordo com o que foi dito, o problema a ser solucionado com este trabalho é a dificuldade do uso de aparelhos inteligentes por idosos.

## Objetivos

O objetivo geral deste projeto é criar um WebApp com funcionalidades práticas que auxiliem idosos no aprendizado de novas tecnologias em aparelhos inteligentes, de forma a obter uma melhoria substancial em sua qualidade de vida.

Em objetivos específicos, podemos salientar:
 - Criar vídeos simples e fáceis de acessar para cada app e suas funcionalidades.
 - Aplicar uma assistência virtual caso a dúvida persista. 
 - Organizar QR codes  interativos.
 - Demonstrar usabilidade simplificada para fácil entendimento das funcionalidades do site.
 - Esquematizar textos grandes para facilitar a leitura de informações.
 - Propor exercícios de aprendizado.
 - Articular tutoriais explicando cada funcionalidade do nosso webApp.
 - Definir login para acompanhar o progresso do aprendizado.
 - Demonstrar conquistas para cada atividade aprendida.

## Justificativa

Segundo pesquisa desenvolvida por Taiuni Marquine Raymundo na Faculdade de Medicina de Ribeirão Preto (FMRP), foi realizado um estudo com 100 pessoas com +65 anos, e verificou-se que 24% dessas pessoas têm medo de utilizar aparelhos inteligentes, e 40% têm receio quanto a danificar os aparelhos tecnológicos.

Além disso, resultados dessa pesquisa demonstram que é possível superar o medo ao utilizar aparelhos inteligentes, em que quando as pessoas realizaram um curso de inclusão digital notou-se que elas ficaram mais motivadas em aprender sobre as novas tecnologias.

## Público-Alvo

Ainda que muitas pessoas possam se beneficiar com as instruções de aprendizagem do WebApp, o objetivo pensado nesse projeto está nos idosos que sentem dificuldade de se incluírem no meio digital.

Portanto, foi estabelecido como público alvo, homens e mulheres com mais de 65 anos que sentem necessidade de se comunicar, utilizar serviços de transporte, navegar na internet livremente e se entreterem, através de dispositivos e apps smart.


# Especificações do Projeto

O esclarecimento exato do nosso problema assim como os tópicos importantes a serem tratados foram definidos através da participação de prováveis usuários usando de entrevistas e observações. Dessa forma, tais conclusões foram levantadas por meio da elaboração de personas e experiências de usuários.

## Personas, Empatia e Proposta de Valor

As personas elaboradas ao longo do processo de conhecimento do problema são apresentadas a seguir:

Persona 1:

![persona 1](images/persona1.PNG)

Proposta de Valor:

![proposta de valor 1](images/proposta1.PNG)

Persona 2:

![persona 2](images/persona2.PNG)

Proposta de Valor:

![proposta de valor 2](images/proposta2.PNG)

Persona 3:

![persona 3](images/persona3.PNG)

Proposta de Valor:

![proposta de valor 3](images/proposta3.PNG)

## Histórias de Usuários



|EU COMO... `PERSONA`| QUERO/DESEJO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Vera Silveira | Comunicar de forma simples e rápida com filhos e netos. | Não ser isolada da família. |
|Vera Silveira | Utilizar, na sua total funcionalidade, o app do banco. | Conseguir realizar suas transações sem ter que pedir ajuda a terceiros. |
|José Carlos da Cruz |Acompanhar as principais e mais relevantes fatos que estão acontecendo no mundo através das notícias. |Se manter atualizado no que diz respeito às atualidades. |
|José Carlos da Cruz |Baixar livros em pdf com qualidade e ter a capacidade de lê-los com facilidade. |Adaptar seu hobbie preferido ao mundo moderno e suas tecnologias. |
|Josiane Alves |Usar apps como uber, moovit com facilidade. |Não perder tempo consultando colegas de trabalho. |

## Requisitos do Projeto

O escopo funcional do projeto é definido por meio dos requisitos funcionais que descrevem as possibilidades interação dos usuários, bem como os requisitos não funcionais que descrevem os aspectos que o sistema deverá apresentar de maneira geral. Estes requisitos são apresentados a seguir.

### Requisitos Funcionais

A tabela a seguir apresenta os requisitos do projeto, identificando a prioridade em que os mesmos devem ser entregues.


| ID    | Descrição do Requisito  | Prioridade |
|--------------------|---------------------------|----------------|
|RF-01  | O principal meio de entrar no site, será por um QR code, que virá num cartão, para facilitar a entrada do usuário no site, e evitar de que o idoso tenha que pesquisar no navegador. | ALTA |
|RF-02  | O site deve ser o mais compreensivo possível, com letras grandes e com linguagem simples, para melhor entendimento do usuário acima de 70 anos.| ALTA |
|RF-03  | O site deve conter sempre ícones dos aplicativos que terão tutoriais, para melhor compreensão. | ALTA | 
|RF-04| O site deve oferecer um menu simples, com opções na parte superior da tela, que permita escolher o dispositivo desejado (celular, notebook, ou TV(de inicio estes dispositivos))   | ALTA |
|RF-05| O site deve oferecer uma barra de pesquisa para que o usuário possa pesquisar uma informação direto se não quiser acessar o Menu. | MÉDIA | 
|RF-06| O site deverá ser responsivo permitindo a visualização em um celular de forma adequada   | ALTA |
|RF-07| O site deve permitir o compartilhamento dos tutoriais e instruções de uso dos apps visualizadas em plataformas de redes sociais | ALTA | 
|RF-08| O site deve permitir salvar tutoriais preferidas, pois os usuários estão em uma faixa etária onde precisam de um uso mais simples   | ALTA |
|RF-09| O site deve disponibilizar um tipo de assistência virtual caso a dúvida persista. | MÉDIA | 
|RF-10| O site deve conter um ChatBot para responder as dúvidas diretas dos usuários   | BAIXA |
|RF-11| O site deve exibir comentários abaixo da página de tutoriais, para que outros usuários possam responder seu comentário, respondendo assim eventuais dúvidas   | ALTA |
|RF-12| O site deve conter um ChatBot para responder o usuário   | BAIXA |


### Requisitos não Funcionais

A tabela a seguir apresenta os requisitos não funcionais que o projeto deverá atender.

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-01| O site deve ser publicado em um ambiente acessível publicamente na Internet (Replit, GitHub Pages, Heroku) | ALTA | 
|RNF-02| O site deve ter bom nível de contraste entre os elementos da tela em conformidade. |  MÉDIA |
|RNF-03|O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Microsoft Edge) |  ALTA | 

## Restrições

As questões que limitam a execução desse projeto e que se configuram como obrigações claras para o desenvolvimento do projeto em questão são apresentadas na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|RE-01| O projeto deverá ser entregue no final do semestre letivo, não podendo extrapolar a data de 12/07/2023. |
|RE-02| O aplicativo deve se restringir às tecnologias básicas da Web no Frontend.|
|RE-03| A equipe não pode subcontratar o desenvolvimento do trabalho.|

# FIZ
# Projeto de Interface

......  COLOQUE AQUI O SEU TEXTO DE INTRODUÇÃO ......

> Apresente as principais interfaces da solução. Discuta como 
> foram elaboradas de forma a atender os requisitos funcionais, não
> funcionais e histórias de usuário abordados nas [Especificações do
> Projeto](#especificações-do-projeto).

## User Flow

......  INCLUA AQUI O DIAGRAMA COM O FLUXO DO USUÁRIO NA APLICAÇÃO ......

> Fluxo de usuário (User Flow) é uma técnica que permite ao desenvolvedor
> mapear todo fluxo de telas do site ou app. Essa técnica funciona
> para alinhar os caminhos e as possíveis ações que o usuário pode
> fazer junto com os membros de sua equipe.
>
> **Links Úteis**:
> - [User Flow: O Quê É e Como Fazer?](https://medium.com/7bits/fluxo-de-usu%C3%A1rio-user-flow-o-que-%C3%A9-como-fazer-79d965872534)
> - [User Flow vs Site Maps](http://designr.com.br/sitemap-e-user-flow-quais-as-diferencas-e-quando-usar-cada-um/)
> - [Top 25 User Flow Tools & Templates for Smooth](https://www.mockplus.com/blog/post/user-flow-tools)
>
> **Exemplo**:
> 
> ![Exemplo de UserFlow](images/userflow.jpg)


## Wireframes

......  INCLUA AQUI OS WIREFRAMES DAS TELAS DA APLICAÇÃO COM UM BREVE DESCRITIVO ......

> Wireframes são protótipos das telas da aplicação usados em design de interface para sugerir a
> estrutura de um site web e seu relacionamentos entre suas
> páginas. Um wireframe web é uma ilustração semelhante ao
> layout de elementos fundamentais na interface.
> 
> **Links Úteis**:
> - [Ferramentas de Wireframes](https://rockcontent.com/blog/wireframes/)
> - [Figma](https://www.figma.com/)
> - [Adobe XD](https://www.adobe.com/br/products/xd.html#scroll)
> - [MarvelApp](https://marvelapp.com/developers/documentation/tutorials/)
> 
> **Exemplo**:
> 
> ![Exemplo de Wireframe](images/wireframe-example.png)

# FIZ

# Metodologia

......  COLOQUE AQUI O SEU TEXTO ......

> Nesta parte do documento, você deve apresentar a metodologia 
> adotada pelo grupo, descrevendo o processo de trabalho baseado nas metodologias ágeis, 
> a divisão de papéis e tarefas, as ferramentas empregadas e como foi realizada a
> gestão de configuração do projeto via GitHub.
>
> Coloque detalhes sobre o processo de Design Thinking e a implementação do Framework Scrum seguido
> pelo grupo. O grupo poderá fazer uso de ferramentas on-line para acompanhar
> o andamento do projeto, a execução das tarefas e o status de desenvolvimento
> da solução.
> 
> **Links Úteis**:
> - [Tutorial Trello](https://trello.com/b/8AygzjUA/tutorial-trello)
> - [Gestão ágil de projetos com o Trello](https://www.youtube.com/watch?v=1o9BOMAKBRE)
> - [Gerência de projetos - Trello com Scrum](https://www.youtube.com/watch?v=DHLA8X_ujwo)
> - [Tutorial Slack](https://slack.com/intl/en-br/)

## Divisão de Papéis

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente a divisão de papéis e tarefas entre os membros do grupo.
>
> **Links Úteis**:
> - [11 Passos Essenciais para Implantar Scrum no seu Projeto](https://mindmaster.com.br/scrum-11-passos/)
> - [Scrum em 9 minutos](https://www.youtube.com/watch?v=XfvQWnRgxG0)


## Ferramentas

......  COLOQUE AQUI O SEU TEXTO - SIGA O EXEMPLO DA TABELA ABAIXO  ......

| Ambiente  | Plataforma              |Link de Acesso |
|-----------|-------------------------|---------------|
|Processo de Design Thinkgin  | Miro |  https://miro.com/XXXXXXX | 
|Repositório de código | GitHub | https://github.com/XXXXXXX | 
|Hospedagem do site | Heroku |  https://XXXXXXX.herokuapp.com | 
|Protótipo Interativo | MavelApp ou Figma | https://figma.com/XXXXXXX | 

>
> Liste as ferramentas empregadas no desenvolvimento do
> projeto, justificando a escolha delas, sempre que possível.
> 
> As ferramentas empregadas no projeto são:
> 
> - Editor de código.
> - Ferramentas de comunicação
> - Ferramentas de diagramação
> - Plataforma de hospedagem
> 
> O editor de código foi escolhido porque ele possui uma integração com o
> sistema de versão. As ferramentas de comunicação utilizadas possuem
> integração semelhante e por isso foram selecionadas. Por fim, para criar
> diagramas utilizamos essa ferramenta por melhor captar as
> necessidades da nossa solução.
> 
> **Links Úteis - Hospedagem**:
> - [Getting Started with Heroku](https://devcenter.heroku.com/start)
> - [Crie seu Site com o HostGator](https://www.hostgator.com.br/como-publicar-seu-site)
> - [GoDady](https://br.godaddy.com/how-to)
> - [GitHub Pages](https://pages.github.com/)

## Controle de Versão

......  COLOQUE AQUI O SEU TEXTO ......

> Discuta como a configuração do projeto foi feita na ferramenta de
> versionamento escolhida. Exponha como a gerência de tags, merges,
> commits e branchs é realizada. Discuta como a gerência de issues foi
> realizada.
> A ferramenta de controle de versão adotada no projeto foi o
> [Git](https://git-scm.com/), sendo que o [Github](https://github.com)
> foi utilizado para hospedagem do repositório `upstream`.
> 
> O projeto segue a seguinte convenção para o nome de branchs:
> 
> - `master`: versão estável já testada do software
> - `unstable`: versão já testada do software, porém instável
> - `testing`: versão em testes do software
> - `dev`: versão de desenvolvimento do software
> 
> Quanto à gerência de issues, o projeto adota a seguinte convenção para
> etiquetas:
> 
> - `bugfix`: uma funcionalidade encontra-se com problemas
> - `enhancement`: uma funcionalidade precisa ser melhorada
> - `feature`: uma nova funcionalidade precisa ser introduzida
>
> **Links Úteis**:
> - [Tutorial GitHub](https://guides.github.com/activities/hello-world/)
> - [Git e Github](https://www.youtube.com/playlist?list=PLHz_AreHm4dm7ZULPAmadvNhH6vk9oNZA)
> - [5 Git Workflows & Branching Strategy to deliver better code](https://zepel.io/blog/5-git-workflows-to-improve-development/)
>
> **Exemplo - GitHub Feature Branch Workflow**:
>
> ![Exemplo de Wireframe](images/Github-Workflow.png)

# **############## SPRINT 1 ACABA AQUI #############**


# Projeto da Solução

......  COLOQUE AQUI O SEU TEXTO ......

## Tecnologias Utilizadas

......  COLOQUE AQUI O SEU TEXTO ......

> Descreva aqui qual(is) tecnologias você vai usar para resolver o seu
> problema, ou seja, implementar a sua solução. Liste todas as
> tecnologias envolvidas, linguagens a serem utilizadas, serviços web,
> frameworks, bibliotecas, IDEs de desenvolvimento, e ferramentas.
> Apresente também uma figura explicando como as tecnologias estão
> relacionadas ou como uma interação do usuário com o sistema vai ser
> conduzida, por onde ela passa até retornar uma resposta ao usuário.
> 
> Inclua os diagramas de User Flow, esboços criados pelo grupo
> (stoyboards), além dos protótipos de telas (wireframes). Descreva cada
> item textualmente comentando e complementando o que está apresentado
> nas imagens.

## Arquitetura da solução

......  COLOQUE AQUI O SEU TEXTO E O DIAGRAMA DE ARQUITETURA .......

> Inclua um diagrama da solução e descreva os módulos e as tecnologias
> que fazem parte da solução. Discorra sobre o diagrama.
> 
> **Exemplo do diagrama de Arquitetura**:
> 
> ![Exemplo de Arquitetura](images/arquitetura-exemplo.png)


# Avaliação da Aplicação

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente os cenários de testes utilizados na realização dos testes da
> sua aplicação. Escolha cenários de testes que demonstrem os requisitos
> sendo satisfeitos.

## Plano de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Enumere quais cenários de testes foram selecionados para teste. Neste
> tópico o grupo deve detalhar quais funcionalidades avaliadas, o grupo
> de usuários que foi escolhido para participar do teste e as
> ferramentas utilizadas.
> 
> **Links Úteis**:
> - [IBM - Criação e Geração de Planos de Teste](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Práticas e Técnicas de Testes Ágeis](http://assiste.serpro.gov.br/serproagil/Apresenta/slides.pdf)
> -  [Teste de Software: Conceitos e tipos de testes](https://blog.onedaytesting.com.br/teste-de-software/)

## Ferramentas de Testes (Opcional)

......  COLOQUE AQUI O SEU TEXTO ......

> Comente sobre as ferramentas de testes utilizadas.
> 
> **Links Úteis**:
> - [Ferramentas de Test para Java Script](https://geekflare.com/javascript-unit-testing/)
> - [UX Tools](https://uxdesign.cc/ux-user-research-and-user-testing-tools-2d339d379dc7)

## Registros de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Discorra sobre os resultados do teste. Ressaltando pontos fortes e
> fracos identificados na solução. Comente como o grupo pretende atacar
> esses pontos nas próximas iterações. Apresente as falhas detectadas e
> as melhorias geradas a partir dos resultados obtidos nos testes.


# Referências

......  COLOQUE AQUI O SEU TEXTO ......

> Inclua todas as referências (livros, artigos, sites, etc) utilizados
> no desenvolvimento do trabalho.
> 
> **Links Úteis**:
> - [Formato ABNT](https://www.normastecnicas.com/abnt/trabalhos-academicos/referencias/)
> - [Referências Bibliográficas da ABNT](https://comunidade.rockcontent.com/referencia-bibliografica-abnt/)
