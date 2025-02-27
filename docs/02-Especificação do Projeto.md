# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

Pedro Paulo tem 26 anos, é arquiteto recém-formado e autônomo. Pensa em se desenvolver profissionalmente através de um mestrado fora do país, pois adora viajar, é solteiro e sempre quis fazer um intercâmbio. Está buscando uma agência que o ajude a encontrar universidades na Europa que aceitem alunos estrangeiros.

Enumere e detalhe as personas da sua solução. Para tanto, baseie-se tanto nos documentos disponibilizados na disciplina e/ou nos seguintes links:

> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes ideais que sua solução almeja.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Modelagem do Processo de Negócio 

### Análise da Situação Atual

Apresente aqui os problemas existentes que viabilizam sua proposta. Apresente o modelo do sistema como ele funciona hoje. Caso sua proposta seja inovadora e não existam processos claramente definidos, apresente como as tarefas que o seu sistema pretende implementar são executadas atualmente, mesmo que não se utilize tecnologia computacional. 

### Descrição Geral da Proposta

Apresente aqui uma descrição da sua proposta abordando seus limites e suas ligações com as estratégias e objetivos do negócio. Apresente aqui as oportunidades de melhorias.

### Processo 1 – NOME DO PROCESSO

Apresente aqui o nome e as oportunidades de melhorias para o processo 1. Em seguida, apresente o modelo do processo 1, descrito no padrão BPMN. 

![Processo 1](img/02-bpmn-proc1.png)

### Processo 2 – NOME DO PROCESSO

Apresente aqui o nome e as oportunidades de melhorias para o processo 2. Em seguida, apresente o modelo do processo 2, descrito no padrão BPMN.

![Processo 2](img/02-bpmn-proc2.png)

## Indicadores de Desempenho

Apresente aqui os principais indicadores de desempenho e algumas metas para o processo. Atenção: as informações necessárias para gerar os indicadores devem estar contempladas no diagrama de classe. Colocar no mínimo 5 indicadores. 

Usar o seguinte modelo: 

![Indicadores de Desempenho](img/02-indic-desemp.png)
Obs.: todas as informações para gerar os indicadores devem estar no diagrama de classe a ser apresentado a posteriori. 

## Requisitos

As tabelas a seguir apresentam uma descrição detalhada dos **requisitos funcionais** e **não funcionais** que definem o escopo do projeto:

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O aplicativo deve permitir que os usuários realizem login com e-mail e senha. | ALTA |
|RF-002| O aplicativo deve possibilitar a recuperação de senha. | ALTA |
|RF-003| O aplicativo deve permitir que os usuários se cadastrem fornecendo nome, e-mail e senha. | ALTA |
|RF-004| O aplicativo deve permitir que os usuários editem seu perfil (nome, foto, senha). | MÉDIA |
|RF-005| O aplicativo deve permitir que os usuários adicionem ganhos e despesas, informando valor, data, categoria e descrição. | ALTA |
|RF-006| O aplicativo deve permitir a criação e edição de categorias para transações (ex: alimentação, transporte). | ALTA |
|RF-007| O aplicativo deve exibir um extrato financeiro com todas as transações do usuário. | ALTA |
|RF-008| O aplicativo deve permitir filtrar transações por categoria, data ou valor. | MÉDIA |
|RF-009| O aplicativo deve gerar gráficos simples de gastos por categoria e evolução mensal. | ALTA |
|RF-010| O aplicativo deve permitir que os usuários definam metas financeiras e acompanhem o progresso. | BAIXA |
|RF-011| O aplicativo deve permitir a criação de grupos para divisão de despesas. | ALTA |
|RF-012| O aplicativo deve permitir que os usuários adicionem despesas ao grupo, informando valor, descrição e divisão entre participantes. | ALTA |
|RF-013| O aplicativo deve calcular automaticamente o saldo de cada participante do grupo. | ALTA |
|RF-014| O aplicativo deve permitir que os usuários marquem despesas como "pagas". | ALTA |
|RF-015| O aplicativo deve exibir um histórico de despesas do grupo. | MÉDIA |
|RF-016| O aplicativo deve permitir que os usuários escolham a moeda. | BAIXA |

### Requisitos não Funcionais

| ID      | Descrição do Requisito | Prioridade |  
|---------|------------------------------------------------------------|----------|  
| RNF-001 | O aplicativo deve ser compatível com dispositivos Android e iOS. | ALTA |  
| RNF-002 | O aplicativo deve ter uma interface simples e intuitiva, seguindo boas práticas de UX/UI. | ALTA |  
| RNF-003 | O sistema deverá ter um ótimo desempenho para lidar com vários usuários de uma única vez. | ALTA |  
| RNF-004 | (Número corrigido) A aplicação deve seguir protocolos de segurança, garantindo a proteção dos dados coletados. | ALTA |  
| RNF-005 | O aplicativo deve ser desenvolvido usando React Native para o front-end e Node.js para o back-end. | ALTA |  
| RNF-006 | (Número corrigido) O aplicativo deve ser testado em dispositivos móveis de baixo e alto desempenho. | MÉDIA |  

## Restrições

O projeto está **restrito** pelos itens apresentados na tabela a seguir:

| ID  | Restrição |  
|----|---------------------------------------------------------------|  
| 01 | O projeto deve ser entregue até o final do semestre. |  
| 02 | O front-end deve ser desenvolvido em React Native. |  
| 03 | O back-end deve ser implementado utilizando Node.js. |  
| 04 | O desenvolvimento deve ser feito com ferramentas gratuitas ou de licença acadêmica. |  
| 05 | O código deve seguir boas práticas de programação e ser bem documentado. |  
| 06 | A equipe deve colaborar ativamente em todas as etapas do projeto. |  
| 07 | O aplicativo deve estar em conformidade com a LGPD. |  
| 08 | Todo o código deve ser disponibilizado em um repositório no GitHub. |  
| 09 | O aplicativo deve funcionar offline para visualização de dados, mas requer conexão à internet para sincronização. |  

## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)

# Matriz de Rastreabilidade

A matriz de rastreabilidade é uma ferramenta usada para facilitar a visualização dos relacionamento entre requisitos e outros artefatos ou objetos, permitindo a rastreabilidade entre os requisitos e os objetivos de negócio. 

A matriz deve contemplar todos os elementos relevantes que fazem parte do sistema, conforme a figura meramente ilustrativa apresentada a seguir.

!### Matriz de Relacionamento REQ.

| Relacionamento REQ. | StakeHolder | RF-001 | RF-002 | RF-003 | RF-004 | RF-005 | RF-006 | RF-007 | RF-008 | RF-009 | RF-010 | RF-011 | RF-012 | RF-013 | RF-014 | RF-015 | RF-016 |
|---------------------|-------------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|
| **Stakeholder**      |             |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x   |
| **RF-001**           |             |        |   x    |   x    |   x    |   x    |   x    |   x    |        |        |        |        |        |        |        |        |       |
| **RF-002**           |             |   x    |        |   x    |   x    |   x    |   x    |   x    |   x    |        |        |        |        |        |        |        |       |
| **RF-003**           |             |   x    |   x    |        |   x    |   x    |   x    |   x    |        |        |        |        |        |        |        |        |       |
| **RF-004**           |             |   x    |   x    |   x    |        |   x    |   x    |   x    |        |        |        |        |        |        |        |        |       |
| **RF-005**           |             |   x    |   x    |   x    |   x    |        |   x    |        |   x    |   x    |        |        |        |        |        |        |       |
| **RF-006**           |             |   x    |   x    |   x    |   x    |   x    |        |        |        |        |        |        |        |        |        |        |       |
| **RF-007**           |             |   x    |   x    |   x    |   x    |   x    |   x    |        |        |   x    |        |        |        |        |        |        |       |
| **RF-008**           |             |   x    |   x    |   x    |   x    |   x    |   x    |   x    |        |        |        |        |        |        |        |        |       |
| **RF-009**           |             |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |        |        |        |        |        |        |        |       |
| **RF-010**           |             |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |        |        |        |        |        |        |       |
| **RF-011**           |             |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |        |        |        |        |        |       |
| **RF-012**           |             |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |        |        |        |        |       |
| **RF-013**           |             |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |        |        |        |       |
| **RF-014**           |             |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |        |        |       |
| **RF-015**           |             |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |        |       |
| **RF-016**           |             |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |   x    |       |


> **Links Úteis**:
> - [Artigo Engenharia de Software 13 - Rastreabilidade](https://www.devmedia.com.br/artigo-engenharia-de-software-13-rastreabilidade/12822/)
> - [Verificação da rastreabilidade de requisitos usando a integração do IBM Rational RequisitePro e do IBM ClearQuest Test Manager](https://developer.ibm.com/br/tutorials/requirementstraceabilityverificationusingrrpandcctm/)
> - [IBM Engineering Lifecycle Optimization – Publishing](https://www.ibm.com/br-pt/products/engineering-lifecycle-optimization/publishing/)


# Gerenciamento de Projeto

De acordo com o PMBoK v6 as dez áreas que constituem os pilares para gerenciar projetos, e que caracterizam a multidisciplinaridade envolvida, são: Integração, Escopo, Cronograma (Tempo), Custos, Qualidade, Recursos, Comunicações, Riscos, Aquisições, Partes Interessadas. Para desenvolver projetos um profissional deve se preocupar em gerenciar todas essas dez áreas. Elas se complementam e se relacionam, de tal forma que não se deve apenas examinar uma área de forma estanque. É preciso considerar, por exemplo, que as áreas de Escopo, Cronograma e Custos estão muito relacionadas. Assim, se eu amplio o escopo de um projeto eu posso afetar seu cronograma e seus custos.

## Gerenciamento de Tempo

Com diagramas bem organizados que permitem gerenciar o tempo nos projetos, o gerente de projetos agenda e coordena tarefas dentro de um projeto para estimar o tempo necessário de conclusão.

![Diagrama de rede simplificado notação francesa (método francês)](img/02-diagrama-rede-simplificado.png)

O gráfico de Gantt ou diagrama de Gantt também é uma ferramenta visual utilizada para controlar e gerenciar o cronograma de atividades de um projeto. Com ele, é possível listar tudo que precisa ser feito para colocar o projeto em prática, dividir em atividades e estimar o tempo necessário para executá-las.

![Gráfico de Gantt](img/02-grafico-gantt.png)

## Gerenciamento de Equipe

O gerenciamento adequado de tarefas contribuirá para que o projeto alcance altos níveis de produtividade. Por isso, é fundamental que ocorra a gestão de tarefas e de pessoas, de modo que os times envolvidos no projeto possam ser facilmente gerenciados. 

![Simple Project Timeline](img/02-project-timeline.png)

## Gestão de Orçamento

O processo de determinar o orçamento do projeto é uma tarefa que depende, além dos produtos (saídas) dos processos anteriores do gerenciamento de custos, também de produtos oferecidos por outros processos de gerenciamento, como o escopo e o tempo.

![Orçamento](img/02-orcamento.png)
