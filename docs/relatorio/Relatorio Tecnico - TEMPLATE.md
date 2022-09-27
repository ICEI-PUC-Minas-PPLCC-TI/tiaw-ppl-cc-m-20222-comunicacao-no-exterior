# Informações do Projeto
`TÍTULO DO PROJETO`  

Lang.Lab

`CURSO` 

Ciência da Computação - PUCMINAS Unidade Praça da Liberdade

## Participantes

Os membros do grupo são: 
- André Fazito Morais
- Gabriel Sanches Rezende
- Ji Xinyi
- Lucas Viana Ferreira
- Sophia Damasceno Satuf
- Yurajyánay Correia Andaluz

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
  - [Personas](#personas)
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

Atualmente, com a crescente globalização, viagens internacionais se tornam cada vez mais comuns e acessíveis, com isso, mostra-se necessário o conhecimento de diversas línguas e culturas para fins comunicativos. Com isto em mente, escolas de todo o planeta adotam o ensino de línguas em suas grades. Porém, é nítida a rigidez no método de ensino, gerando grande insatisfação em estudantes. 

Sendo assim, é nítida a necessidade de adoção de metodologias modernas e flexíveis para aprendizagem eficaz e que não desgasta estudantes de línguas. Portanto, este trabalho visará a solução desta demanda a partir de conhecimentos de desenvolvimento de Interfaces e Aplicações Web.

## Problema

Após realizadas as entrevistas qualitativas, o grupo pôde notar a dificuldade na eficácia e regularidade de estudos de línguas estrangeiras, que atendam demandas atuais de aprendizagem. Foi percebido o fato de que existem diversas dificuldades e motivos para aprender línguas.

## Objetivos

O projeto visa auxiliar e orientar todos os indivíduos com a aprendizagem de idiomas, de forma a manter o foco e a consistência, tornando a experiência mais leve e eficaz. Assim, o produto será centrado na integração entre usuários, garantindo a prática de línguas em comunidade.
Especificamente, será relevante citar:
- Confecção de perfis individuais e customizáveis por cada usuário;
- Permitir interação entre usuários, com chat privado, compartilhamento de agendas e recomendações de mídias em línguas;
- Integração de artigos simples, rápidos e lúdicos na língua estrangeira para o acompanhamento do aprendizado;
- Permitir aos usuários confeccionar suas próprias rotinas flexíveis;
- Adicionar um sistema de recompensas para aumentar a motivação dos usuários;

## Justificativa

De acordo com o artigo “Dificuldades de aprendizagem da língua Inglesa no I Ciclo do Ensino Secundário: 7ª, 8ª e 9ª classe”, de Alberto Mahula Francisco, as principais causas de desinteresse e/ou dificuldade no aprendizado de idiomas são a ansiedade no momento das aulas, falta de motivação e maus hábitos.
  
O autor Marcos Venicio Esper, em seu relato de pesquisa “Crianças com deficiência e aprendizagem de línguas estrangeiras: contribuições e reflexões”, afirma que interação imediata e caráter ativo e interativo no processo de ensino é extremamente importante para manter o caráter dinâmico, acessibilidade e diversidade no aprendizado.
  
Com isso, vemos a necessidade de efetivar meios de ensino que sejam mais flexíveis e que possam  instruir e auxiliar no aprendizado do aluno de forma menos maçante. É de suma importância que o grupo tenha em mente os aspectos citados para desenvolver uma aplicação web que amenizará as dores dos estudantes de idiomas.

## Público-Alvo

Em decorrência das entrevistas realizadas pelo grupo, o público-alvo do projeto se baseia em jovens adultos, em sua maioria universitários com interesse em aprender idiomas de uma forma mais lúdica e menos cansativa. Porém, o design do produto deverá ser pensado de forma inclusiva, possibilitando assim a acessibilidade de diversas faixas etárias.
 
# Especificações do Projeto

Após realizadas as entrevistas qualitativas abrangindo a faixa etária do público-alvo, com estudantes universitários, pode-se observar os principais obstáculos a serem superados para a efetivação leve e divertida da aprendizagem de línguas. Dessa forma, foram confeccionadas personas e especificados requisitos e histórias de usuários.

## Personas 

As personas confeccionadas, suas dores e necessidades são representadas nas figuras a seguir:





## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Felipe  | Aesenvolver a minha língua inglesa, para que eu possa trabalhar em uma multinacional           | Poder trabalhar em uma multinacional e sanar meu interesse pessoal               |
|Débora       | Aprender o básico das línguas de alguns determinados países                 | Poder conhecer o mundo |
|Luísa       | Aprender idiomas de forma mais descontraída                 | Absorver melhor conhecimentos e de forma menos desgastante. |



## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O site deve conter um sistema de sign up/login | ALTA | 
|RF-002| O site deve ter uma página de perfil do usuário   | ALTA |
|RF-003| O site deve ter uma página contendo informações sobre o projeto e grupo   | MÉDIA |
|RF-004| O site deve conter um sistema de botões para escolher o idioma desejado para a aprendizagem/consulta   | ALTA |
|RF-005| O site deve conter tópicos de vocabulário para determinadas situações/ambientes   | MÉDIA |
|RF-006| O site deve ter um sistema de recompensa para o usuário   | MÉDIA |
|RF-007| O site deve ter recomendações de mídias (Filmes, Séries, Livros, Músicas...) de cada língua   | MÉDIA |
|RF-008| O site deve dar liberdade do usuário de definir sua rotina   | ALTA |
|RF-009| o site deve conter artigos rápidos e divertidos de cada língua   | MÉDIA |
|RF-010| O site deve possuir uma agenda para registrar o estudo de cada dia do usuário   | BAIXA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O site deve ser responsivo | MÉDIA | 
|RNF-002| Deve ser utilizado o git para versionamento do projeto | ALTA | 
|RNF-003| O site deve utilizar da Stack HTML, CSS e JS para construção | MÉDIA | 


## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |

# Projeto de Interface

Com funções interativas, baseado em design intuitivo e divertido, a interface do projeto se baseará em telas de Index, Cadastro, Login, Sobre, Seleção de Línguas, Seleção de Categorias, Tela de Categorias e Artigos, e Perfil de Usuário.

## User Flow

![Exemplo de UserFlow](images/userflow.jpg)


## Wireframes

### Tela Inicial:

![Exemplo de Wireframe](images/wireframe-example.png)

### Cadastro:

![Exemplo de Wireframe](images/wireframe-example.png)

### Login:

![Exemplo de Wireframe](images/wireframe-example.png)

### Seleção de Línguas:

![Exemplo de Wireframe](images/wireframe-example.png)

### Seleção de Categorias:

![Exemplo de Wireframe](images/wireframe-example.png)

### Template de Categorias/Artigos:

![Exemplo de Wireframe](images/wireframe-example.png)

### Perfil:

![Exemplo de Wireframe](images/wireframe-example.png)

# Metodologia

Ao iniciar um novo projeto é necessário medir, de alguma forma, o nível de compromisso que é demandado de cada indivíduo, ou de um time. Com isso em mente, a equipe se baseou no modelo de trabalho do Scrum, para não somente conseguir visualizar uma lista de requisitos, mas também atribuir, distribuir e planejar configurações de designação de tarefas que priorizasse não somente agilidade, mas o melhor aproveitamento dos talentos de cada membro da equipe.

 A equipe buscou adaptar o Scrum porque acredita que ajustes são necessários ao se entrar em contato com um modelo novo, mas também por acreditar que o Scrum pode ser potencializado ao ser visto como uma ferramenta que trabalha em favor da equipe. Dessa forma, algumas cerimônias do Scrum, como planejamento e revisão da sprint, foram priorizadas em detrimento de outras, como as “daily”. 
 
Apesar de não ter realizado uma “daily” diariamente, como sugere o Scrum, a equipe buscou manter um canal de comunicação aberto, claro e sincero, visando como resultado alinhamento do andamento do projeto, das tarefas individuais, trocas de ideias e eventuais tarefas que poderiam em situação de dependência com outras. Para nosso alinhamento e comunicação utilizamos Discord, Whatsapp e Trello.

 No whatsapp realizamos trocas rápidas de alinhamento, no Discord fizemos reuniões virtuais para executar tarefas e discutir ideias, e no Trello estabelecemos nosso backlog. Ainda no Trello utilizamos um template de quadro Kanban para traduzir os “materiais entregáveis”, que foram passados pelo professor, para tarefas objetivas e executáveis no backlog. Distribuímos as tarefas às pessoas a quem elas fossem atribuídas, o que era previamente acordado em equipe. E por fim, definimos a dificuldade de cada tarefa usando um sistema de código baseado em cores. Para definir dificuldade utilizamos alguns critérios, dentre eles: data de entrega, esforço e tempo.

## Divisão de Papéis

André Fazito Morais - Processo de Design Thinking.

Gabriel Sanches Rezende - Processo de Design Thinking, Documentação do Projeto, Repositório GitHub.

Ji Xinyi - Processo de Design Thinking, Documentação do Projeto.

Lucas Viana Ferreira - Processo de Design Thinking, Documentação do Projeto, Apresentação.

Sophia Damasceno Satuf - Processo de Design Thinking, Documentação do Projeto.

Yurajyánay Correia Andaluz - Processo de Design Thinking, Documentação do Projeto, Apresentação.


## Ferramentas

| Ambiente  | Plataforma              |Link de Acesso |
|-----------|-------------------------|---------------|
|Processo de Design Thinkgin  | Miro |  https://miro.com/app/board/uXjVPT6fBs0=/ | 
|Repositório de código | GitHub | https://github.com/orgs/ICEI-PUC-Minas-PPLCC-TI/teams/comunicacao-no-exterior | 
|Hospedagem do site | Heroku |  https://herokuapp.com | 
|Protótipo Interativo | Figma | https://www.figma.com/proto/s2AlOPvbXY4UcJ9m20rTKL/Untitled?node-id=0%3A1 | 
|Editor de Código | Visual Studio Code | https://code.visualstudio.com/ | 
|Organização Kanban | Trello | https://trello.com/b/RgZd5b5s/quadro-kanban | 
|Comunicação/Reuniões | Discord | https://discord.com/ | 


## Controle de Versão

 A ferramenta de controle de versão adotada no projeto foi o
 [Git](https://git-scm.com/), sendo que o [Github](https://github.com)
 foi utilizado para hospedagem do repositório `upstream`.
 
 O projeto segue a seguinte convenção para o nome de branchs:

- `master`: versão estável já testada do software
- `unstable`: versão já testada do software, porém instável
- `testing`: versão em testes do software
- `dev`: versão de desenvolvimento do software
 
Quanto à gerência de issues, o projeto adota a seguinte convenção para
etiquetas:

- `bugfix`: uma funcionalidade encontra-se com problemas
- `enhancement`: uma funcionalidade precisa ser melhorada
- `feature`: uma nova funcionalidade precisa ser introduzida

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

http://pepsic.bvsalud.org/scielo.php?script=sci_arttext&pid=S1415-69542021000100003#:~:text=Adquirir%20uma%20segunda%20l%C3%ADngua%2C%20historicamente,o%20professor%2C%20memorizar%20vocabul%C3%A1rio)

https://www.webartigos.com/artigos/dificuldades-de-aprendizagem-da-lingua-inglesa-no-i-ciclo-do-ensino-secundario-7a-8a-e-9a-classe/169609

> Inclua todas as referências (livros, artigos, sites, etc) utilizados
> no desenvolvimento do trabalho.
> 
> **Links Úteis**:
> - [Formato ABNT](https://www.normastecnicas.com/abnt/trabalhos-academicos/referencias/)
> - [Referências Bibliográficas da ABNT](https://comunidade.rockcontent.com/referencia-bibliografica-abnt/)
