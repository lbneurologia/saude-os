---
id: root.agents
title: Regras globais para Agentes de IA
owner: chief-systems-architect
status: active
tags: [ai, governance, agents]
summary: Como agentes de IA devem operar no Company OS.
last_reviewed: 2026-07-19
related: [root.company, meta.readme]
---

# Regras para Agentes de IA

Projetado para **dezenas de agentes trabalhando em paralelo** sem colisao.

## Antes de agir
1. Leia `COMPANY.yaml` e o `README.md`/`domain.yaml` da area onde vai atuar.
2. Respeite a **lei do lar unico**: nao duplique; referencie por `id`.
3. Consulte `90-meta/standards` (nomes, frontmatter, contratos).

## Fronteiras
- Atue **dentro de um unico dominio/area por tarefa** (ver `writable_paths` no
  `domain.yaml`). Isso minimiza conflito de merge.
- **Nunca** grave dado de paciente (PHI). Fronteira em `40-quality/data-governance`.
- Mudanca **estrutural** (nova area/dominio, mudanca de padrao) exige **ADR** aprovado.

## Entregas
- Todo `.md` novo leva frontmatter completo (`90-meta/standards/frontmatter.md`).
- Contratos entre dominios sao versionados (`90-meta/standards/interfaces-contracts.md`).
- Commits em Conventional Commits.
