---
id: meta.tpl.domain
title: Template de README de dominio
owner: chief-systems-architect
status: active
tags: [template, ddd, domain]
summary: Estrutura repetivel de todo dominio em 10-domains.
last_reviewed: 2026-07-02
related: [domain.clinical-care]
---
# <Nome do dominio>
Descricao curta. Tipo (core|supporting|generic). Dono.

## Estrutura interna (repetivel)
- `language/` linguagem ubiqua · `model/` entidades e fluxos
- `policies/` regras · `protocols/` (clinico) · `procedures/` SOPs
- `interfaces/` contratos versionados · `metrics/` KPIs · `decisions/` ADRs

## Regras
- Interage com outros dominios so via `interfaces/`.
- Dono unico. Sem pastas vazias.
