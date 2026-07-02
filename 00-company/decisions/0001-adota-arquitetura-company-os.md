---
id: company.adr.0001
title: 0001 - Adota arquitetura Company OS
owner: chief-systems-architect
status: active
tags: [adr, architecture]
summary: Decisao fundadora da arquitetura do repositorio.
last_reviewed: 2026-07-02
related: [company.adr.0002, root.readme]
---
# 0001 - Adota arquitetura Company OS
- **Status:** accepted
- **Data:** 2026-07-02
- **Decisores:** CEO, Chief Systems Architect

## Contexto
Necessidade de um Sistema Operacional de empresa de saude, escalavel por 20 anos,
para multiplas clinicas, pesquisa, ensino, IA e expansao nacional.

## Decisao
Adotar arquitetura hibrida: base horizontal enxuta + dominios verticais (DDD)
autocontidos, governados pela lei do lar unico, com documentacao viva, ADRs (MADR),
Diataxis, C4 e catalogo legivel por maquina.

## Consequencias
- (+) Escala sem reorganizar; onboarding rapido; pronto para agentes de IA.
- (-) Exige disciplina de frontmatter e enforcement por CI.
