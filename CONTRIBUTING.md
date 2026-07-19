---
id: root.contributing
title: Como contribuir e regras de organizacao
owner: chief-systems-architect
status: active
tags: [governance, contributing]
summary: Regras que mantem o Company OS organizado por decadas.
last_reviewed: 2026-07-19
related: [root.readme, meta.readme]
---

# Contribuindo

## Regras inviolaveis
1. **Um lar canonico por conceito.** Duplicou? Errado. Referencie por `id`.
2. **Pastas = capacidades. Donos = metadado.** Nao codifique o organograma em nomes de pasta.
3. **Topo e conjunto fechado.** Nova area de topo exige ADR aprovado.
4. **Todo dominio segue o template** em `90-meta/templates/domain-README.md`.
5. **Sem pastas vazias.** Toda pasta nasce com README-indice.
6. **PHI nunca entra no repo.**

## Nomes e docs
- `kebab-case`, sem espacos/acentos; registros com prefixo ISO (`2026-07-19-...`).
- Frontmatter obrigatorio; categorizacao Diataxis; diagramas em C4.

## Fluxo
Proposta -> PR -> revisao (CODEOWNERS) -> merge. Mudancas estruturais -> ADR.
