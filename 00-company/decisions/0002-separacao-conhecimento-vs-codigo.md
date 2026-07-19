---
id: company.adr.0002
title: 0002 - Separacao conhecimento vs codigo de produto
owner: cto
status: active
tags: [adr, architecture, scalability]
summary: Este repo guarda conhecimento e especificacoes; codigo vive em repos proprios.
last_reviewed: 2026-07-19
related: [company.adr.0001, platform.readme]
---
# 0002 - Separacao conhecimento vs codigo de produto
- **Status:** accepted
- **Data:** 2026-07-19
- **Decisores:** CTO, Chief Systems Architect

## Contexto
Misturar handbook, QMS e codigo de producao que toca paciente num unico repo cria
risco de acesso, blast radius e problemas de escala (revisao Amazon/Mayo/Stripe).

## Decisao
Company OS (este repo) = conhecimento, governanca e especificacoes.
Codigo executavel vive em repositorios de produto proprios, apenas CATALOGADOS em
`20-platform/catalog` e `90-meta/catalog`.

## Consequencias
- (+) Seguranca, escala, ownership limpo, controle de acesso por plano.
- (-) Exige manter o catalogo sincronizado (automatizavel).
