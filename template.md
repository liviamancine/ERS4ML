# Explicability Requirements Specification (ERS) document template for based Machine Learning system (ML)
## ERS4ML

Version 0.1
Prepared by Lívia <author>

Table of Contents
=================
  * [Revision History](#revision-history)
  * [Explicability Requirements Specification (ERS) document](#ERS-document)
  * 1 [Introduction](#1-introduction)
   * 1.1 [Document Purpose](#11-purpose)
   * 1.2 [Product Scope](#12-scope)
   * 1.3 [Stakeholders](#13-stakeholders)
  * 2 [Product Overview](#2-product-overview)
   * 2.1 [Product Functions](#21-product-function)
   * 2.2 [Product Perspective](#22-product-perpective)  
   * 2.3 [Product Constraints](#23-product-constraints)
   * 2.4 [User Characteristics](#24-user-characteristics)
  * 3 [Decision Point Requirements of Machine Learning Models](#3-decision-point-requirements-of-machine-learning-models)
   * 3.1 [Requisitos de Contexto do Componente de AM](#31-requisitos-de-contexto-do-componente-de-AM)
   * 3.2 [Requisitos do Processo de Seleção e Preparação dos Dados](#32-requisitos-do-processo-de-selecao-e-preparacao-dos-dados)
   * 3.3 [Requisitos de Modelagem de AM](#33-requisitos-de-modelagem-de-am)
       

## Revision History

| Name | Date    | Reason For Changes  | Version   |
| ---- | ------- | ------------------- | --------- |
|      |         |                     |           |
|      |         |                     |           |
|      |         |                     |           |

## Explicability Requirements Specification (ERS) document

> Este documento define a especificação do requesito de explicabilidade para sistemas baseados em Aprendizado de Máquina (AM), seguindo as diretrizes ISO/IEC/IEEE 29148:2011. A especificação deste requisito não-funcional considera regulamentações e diretrizes internacionais e nacionais sobre a Inteligência Artificial (IA) para saúde, incluindo recomendações da Organização Mundial da Saúde (OMS), o Projeto de Lei n. 2338/2023, que regulamenta o uso da IA no Brasil, e o estudo sobre IA na saúde do Núcleo de Informação e Coordenação do Ponto BR (NIC.br).
Neste documento, a explicabilidade é utilizada para alcançar o aspecto de transparência.
A organização dos itens informativos, como a sequência e a estrutura das seções, poderá ser adaptada conforme as políticas de documentação específicas do projeto.

## 1. Introduction

> Esta seção deve fornecer uma visão geral do componente de Aprendizado de Máquina (AM).

### 1.1 Document Purpose

Descreva a proposta da ERS4ML e seu público-alvo. 

### 1.2 Product Scope

Explique a função do componente de AM, incluindo sua finalidade específica e influência na tomada de decisão pelos algoritmos de AM. Apresente se o componente de AM faz parte de um sistema maior ou é subsistema independente. 
Forneça uma breve descrição do componente de AM que está sendo especificado, abordando sua finalidade, os principais benefícios esperados, bem como seus objetivos e metas relevantes. Relacione esses objetivos e metas corporativas ou estratégias de negócios, explicando como o componente contribui para atingir esses resultados. Se já existe um documento de visão e escopo separado, inclua apenas a referência a ele, evitando duplicação de conteúdo.

### 1.3 Stakeholders

Explique como os stakeholders serão influênciados por este sistema, incluindo os impactos esperados em suas atividades, responsabilidades e tomadas de decisão realizada pelo componentes de AM.

## 2. Product Overview

> Esta seção deve descrever os fatores gerais que afetam o produto e seus requisitos. Esta seção não declara requisitos específicos.

### 2.1 Product Functions

Resuma as principais funções que o produto deve executar ou permitir que o usuário execute, considerando apenas as funções realizadas pelos algoritmos de AM. Os detalhes serão fornecidos na Seção 3, então inclua aqui apenas um resumo de alto nível (como uma lista com marcadores). Organize as funções para que sejam compreensíveis por qualquer leitor do ERSML.

### 2.2 Product perspective

Descreva se o produto de AM é um componente de um sistema maior que oferece uma funcionalidade nova, substitui certos sistemas ou funcionalidades existentes, ou se é um produto novo e independente. Se o produto fizer parte de um produto maior, identifique as interfaces entre o produto descrito neste ERSML e o sistema maior. A inclusão de um diagrama simples mostrando os principais componentes do sistema geral, as interconexões de subsistemas e interfaces externas pode ser útil.

###  2.3 [Product Constraints]

Em construção...

### 2.4 User Characteristics

Identifique as diferentes classes de usuários que provalvemente utilizarão este componente de AM. Diferencie as classes com base na frequência de uso, subconjunto de funções utilizadas, conhecimento técnico, nível de segurança ou privilégio, formação educacional ou experiência. Descreva as características pertinentes de cada classe de usuário, destacando aquelas que podem ter requisitos específicos. Distinga as classes de usuários mais críticas para o produto daquelas que são de menor prioridade. Exemplos de classes de usuários incluem: profissional médico, gestores hospitalares, reguladores, partes afetadas, como os pacientes. 

## 3. Decision Point Requirements of Machine Learning Models

> Esta seção especifica os requisitos do componente de AM em um nível de detalhe suficiente para permitir que os engenheiro projetem um componente de AM explicável, que atenda ao objetivo de transparência.

> Os requisitos específicos devem:
* Ser identificáveis de forma única
* Declarar o assunto do requisito (por exemplo, sistema, software, banco de dados, etc.) e o que deve ser feito
* Opcionalmente, declarar condições e restrições, se houver
* Descrever cada entrada (estímulo) para componente de AM, cada saída (resposta) da tomada de decisão e todas as funções que o componente de AM executa em resposta a uma entrada ou em apoio a uma saída
* Ser verificável (por exemplo, permitir comprovação de que o requisito foi atendido para a satisfação do cliente ou órgão regulador)
* Estar em conformidade com a sintaxe, palavras-chave e termos acordados


### 3.1 Requisitos de Contexto do Componente de AM

> Descrever o problema que o sistema de Aprendizado de Máquina (AM) irá resolver:
* Contexto do sistema de AM: descrição clara do ambiente e das condições em que o sistema de AM foi concebido para funcionar
* Embasamento científico: comprovação de que as abordagens dos modelos de AM são generalizáveis e se aplicam de forma confiável às evidências clínicas disponíveis
* Impacto na decisão clínica: explicar como as saídas do sistema podem influenciar ou apoiar as decisões médicas, identificando o tipo de suporte fornecido para as partes interessadas
* Limitações: indicar quais os cenários o modelo pode ter desempenho restrito

### 3.2 Requisitos do Processo de Seleção e Preparação dos Dados

> Descrever a seleção e o tratamento de conjuntos de dados de treinamento usados no processo de desenvolvimento:
* Fontes de Dados utilizadas: especificar quais fontes de dados clínicas ou outras bases foram utilizadas para treinar o modelo de AM, com justificativas para a escolha de cada uma
* Construção dos dados para treinamento: descrever como os dados foram processados, incluindo técnicas de limpeza e pré-processamento para garantir a consistência e qualidade dos dados
* Integração dos dados: explicar o processo de unificação de dados provenientes de diferentes fontes, descrevendo métodos de consolidação, resolução de inconsistências e tratamento de duplicidades
* Descrição da base de dados (final) para treinamento: fornecer uma visão geral da base de dados final, incluindo as variáveis principais, distribuição e representatividade dos dados, além de informações sobre o balanceamento das classes, se aplicável.

### 3.3 Requisitos de Modelagem de AM

> Descrever a modelagem do processo de tomada de decisão:
* Modelos de AM utilizados: identificar os modelos de AM empregados no sistema (ex. redes neurais, árvores de decisão), especificando versões, parâmetros principais e justificativas para a escolha
* Etapas de teste e validação do treinamento: descrever as métricas utilizadas (ex. precisão, sensibilidade, especificidade) e os critérios de aceitação
* Ajustes e otimização dos modelos: explicar o processo de ajuste e otimização, incluindo técnicas de ajuste de hiperparâmetros, abordagem de cross-validation e outros métodos utilizados para melhorar o desempenho do modelo
* Limitação: descrever limitações conhecidas dos modelos que possam influenciar os resultados

