---
layout: default
title: Processos
description: Aqui você pode visualizar como nós funcionamos!
---

# Processos

Processos de software são conjuntos de atividades uniformizadas a serem aplicadas sistematicamente que se encontram agrupadas em fases, cada uma das quais com os seus intervenientes com responsabilidades, que possui diversas entradas e produz diversas saídas. Isto é, define quem faz o quê, quando e como para atingir um certo objetivo.

A NoPark, visando a busca contínua por qualidade em seus projetos, define os sequintes processos abaixo:


## Iniciação

O processo de Iniciação tem o objetivo de recepcionar as demandas existentes de uma RFP ("Request for Proposal”, um documento de proposta para a contratação ou aquisição de um produto ou serviço.) aberta, analisá-las, produzir um modelo de negócio e um termo de abertura para o projeto.

![Processo de Iniciação](https://beatrizacbs.github.io/nopark/assets/images/iniciacao.svg)

### Atividades

#### Receber RFP

Receber do cliente uma ou mais RFP's (Request for Proposal).

- Entrada: 
  - RFP

#### Analisar RFP

Estabelecer juntamente com o cliente critérios relevantes do sistema a ser desenvolvido, como limitações, escopo, custo e tempo.

- Entrada: 
  - RFP
- Atores: 
  - Time?

#### Propor alterações junto ao cliente

Caso o projeto proposto pelo cliente seja inviável para execução pela equipe, faz-se reunião com o cliente para propor alterações sobre o escopo do projeto.

- Entrada: 
  - RFP
- Saída:
  - RFP
- Atores: 
  - Time?

#### Planejar modelo de negócio

Utilizar das técnicas de Lean para planejar de forma mais acertiva o modelo de negócios referente ao projeto.

- Entrada: 
  - Guia do Modelo CANVAS
- Saída: 
  - Modelo CANVAS
- Atores: 
  - Time?

#### Produzir Termo de Abertura

Produzir o termo de abertura de projeto e apresentar ao cliente para que o mesmo possa assinar e oficializar a inicialização das atividades.

- Entrada: 
  - Template de Termo de Abertura
- Saída: 
  - Termo de Abertura
- Atores: 
  - Time?

* * *

## Planejamento

No processo de planejamento encontrasse toda a estrutura e etapas de planejamento, para que o projeto esteja bem definido e validado entre os atores responsáveis e a organização. 

![Processo de Planejamento](https://beatrizacbs.github.io/nopark/assets/images/planejamento.svg)

### Atividades

#### Elicitar Requisitos

Traduzir as necessidades da RFP em requisitos bem definidos.

- Entrada: 
  - RFP
  - Template de Documento de Requisitos
- Saída: 
  - Documento de Requisitos 
- Atores: 
  - Time? 

#### Análisar os Requisitos Elicitados

Os requisitos devem ser analisados em busca de melhorias.

- Entrada: 
  - Documento de Requisitos
- Atores: 
  - Time? 

#### Definir a Arquitetura

Com base nas necessidades definidas no Documento de Requisitos, deve ser definida a arquitetura dos serviços a serem desenvolvidos. 

- Entrada: 
  - Documento de Requisitos
  - Modelo de Documento de Requisitos
- Saída: 
  - Documento Arquitetural
- Atores: 
  - Time?

#### Elaborar o Plano de Testes

Através das necessidades e critérios definidos pela NoPark, devem ser identificadas as técnicas específicas a serem empregadas para cada caso de teste.

- Entrada: 
  - Modelo de Plano de Testes
- Saída: 
  - Plano de Testes
- Atores: 
  - Time?

#### Elaborar o Mapeamento dos Riscos

Com base na identificação dos riscos internos e externos é feito um mapeamento dos mesmos em uma tabela de exposição.

- Entrada: 
  - Template da Tabela de exposição
- Saída: 
  - Tabela de exposição
- Atores: 
  - Time?

#### Definir o Product Backlog

Utilizando os artefatos de base fornecidos pelo cliente e definidos até o momento e estruturar um Product Backlog em User Stories. 

- Entrada: 
  - RFP
  - Documento de Requisitos	
- Saída: 
  - Product Backlog (User Stories)
- Atores: 
  - Time?

#### Priorizar User Stories

Após a finalização das etapas anteriores e tendo em mão o product backlog em formato de User stories, é feito um momento para priorização das mesmas, afim de definir quais são as que possuem uma complexidade e/ou criticidade maior para o desenvolvimento.

- Entrada: 
  - Product Backlog (User Stories não priorizadas)
- Saída: 
  - User Stories priorizadas	
- Atores: 
  - Time?

#### Elaborar o Plano de Projeto

Elaboração de todo o plano para a execução, controle, monitoramento, e entrega do produto, analisando recursos, pessoas, tempo, custo e fazendo as devidas alocações com base em todos os artefatos existentes.

- Entrada: 
  - Documento de Requisitos
  - Documento Arquitetural
  - Plano de Testes
  - Modelo de Plano de Projeto
- Saída: 
  - Plano de Projeto	
- Atores: 
  - Time?

#### Reunião de KickOff com o time

Momento de alinhamento da equipe, apresentando o plano de projeto com todas as suas seções.

- Entrada: 
  - Plano de Projeto	
- Atores: 
  - Time

* * *

## Execução

Na fase de implementação, o Time estará focado no desenvolvimento da sprint. Quando todas as sprints do ciclo do projeto forem finalizadas, será possível fazer as próximas fases de entrega e encerramento do projeto.

![Processo de Execução](https://beatrizacbs.github.io/nopark/assets/images/execucao.svg)

### Atividades

#### Definição da Visão do Projeto

Definir a direção do Projeto e os objetivos a serem alcançados no encerramento dele.

- Saída: 
  - Visão do Projeto	
- Atores: 
  - Time?

#### Definição da Visão da Sprint

Definir a direção da Sprint e os objetivos a serem alcançados no encerramento dessa.

- Saída: 
  - Visão da Sprint	
- Atores: 
  - Time?

#### Definir Backlog da Sprint

Com base no Product Backlog já priorizado, é feito um momento para definição do Backlog da Sprint atual. 

- Entrada: 
  - Product Backlog (User Stories priorizadas)
- Saída: 
  - Sprint Backlog	
- Atores: 
  - Time?

#### Executar tarefas da Sprint

Codificar e criar as funcionalidades definidas no planejamento.
	
- Atores: 
  - Time

#### Executar Testes

A cada funcionalidade nova desenvolvida deve ser executado um conjunto de testes, estes, definidos no plano de testes e ao fim deve ser gerado um relatório para acompanhamento. 

- Entrada: 
  - Plano de Testes
- Saída: 
  - Relatório dos Testes	
- Atores: 
  - Time

#### Incrementar Produto

O código fonte é atualizado no repositório, e uma nova versão do produto é gerada através de uma pull request. 

- Entrada: 
  - Código/Feature desenvolvido
- Saída: 
  - Pull Request	
- Atores: 
  - Time

#### Sprint Review

Avaliação das funcionalidade entregues com os objetivos da sprint, também levantando os problemas e situações que ocorreram na sprint, o foco é procurar solucioná-los para melhorar o ciclo para a próxima Sprint.

- Entrada: 
  - Atividades concluídas
- Saída: 
  - Lições aprendidas 
  - Release da aplicação	
- Atores: 
  - Time

#### Deploy final da Aplicação

Realizar o Deploy da versão estável da aplicação para o ambiente de produção. 

- Entrada: 
  - Releases da aplicação
- Saída: 
  - Versão estável da aplicação	
- Atores: 
  - Time

#### Retrospectiva do Projeto

Na Retrospectiva, o Time relata sobre problemas, situação que ocorreram durante a sprint, o foco é procurar sempre melhorar o processo.

- Saída: 
  - Melhorias identificadas no processo	
  - Lições aprendidas
- Atores: 
  - Time

* * *

## Encerramento

É a fase onde todos os requisitos serão concluídos, formalizando assim a conclusão do projeto e delimitando a entrega final do produto.

![Processo de Encerramento](https://beatrizacbs.github.io/nopark/assets/images/encerramento.svg)

### Atividades

#### Marcar Reunião com o Cliente

Negociar data com o cliente para realização de reunião.

- Atores: 
  - Time?

#### Reunião de Apresentação das Features Desenvolvidas

Apresentar ao cliente as features desenvolvidas no projeto.

- Atores: 
  - Time

#### Encerrar o Projeto

Formalizar a entrega do produto junto ao cliente acompanhado de toda a documentação do projeto.

- Entrada: 
  - Termo de Aceite 
  - Artefatos do Projeto
- Saída: 
  - Termo de Aceite
- Atores: 
  - Time






