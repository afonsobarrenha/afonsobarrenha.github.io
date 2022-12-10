---
layout: post
title:  "Arquitetura - C4 Model - Structurizr"
date:   2022-12-10 10:10:00 -0300
categories: jekyll update
---
Evoluindo no tema de Desenhos de Arquitetura, irei montar uma POC quanto ao [Structurizr](https://structurizr.com/), usando a [CLI](https://github.com/structurizr/cli/blob/master/docs/getting-started.md) da ferramenta para criação de Diagramas como Código.

Infelizmente as documentações da [DSL](https://github.com/structurizr/dsl/blob/master/docs/language-reference.md) e do [CLI](https://github.com/structurizr/cli/blob/master/docs/getting-started.md) do Structurizr são confusas e faltam muitos exemplos. Mas por ser uma ferramenta simples, consegui fazer a configuração e a criação de workspaces extendendoum workspace principal, o que irá ajudar muito em nossa tarefa de manter a Arquitetura de Software de plataformas.

O [resultado final](https://github.com/afonsobarrenha/structurizr/blob/main/gsp-workspace.dsl) ficou muito bom, e tenho certeza que vale a pena extender essa tarefa para todos os demais Arquitetos.

Como comparativo, procurei outras ferramentas de Diagrama como Código, como a [PlantUML](https://github.com/plantuml-stdlib/C4-PlantUML) e a [Mermaid](https://mermaid-js.github.io/mermaid/#/), mas ambas são mais complexas de se manter doo que a Structurizr.