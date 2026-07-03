---
id: platform.ai
title: Platform — IA e agentes especializados
owner: cto
status: active
tags: [platform, ai, agents, governance]
summary: Casa da IA: registro de agentes, specs, prompts, evals e guard-rails. Human-in-the-loop no clínico.
last_reviewed: 2026-07-02
related: [platform.readme, root.agents, company.principles, meta.catalog.agents]
---

# IA e agentes especializados

Projetado para **dezenas de agentes trabalhando em paralelo** sem colisão, cada um
atuando num vertical com fronteiras declaradas.

## Registro (fonte canônica)
O roster de agentes vive em [`90-meta/catalog/agents.yaml`](../../90-meta/catalog/agents.yaml)
(Celina, Marketing, SEO, Google Ads, Pesquisa, Protocolos, Financeiro, RH,
Jurídico, BI, Atendimento, CRM, Operações, Growth).

## Estrutura de cada agente
Cada agente ganha uma pasta `agents/<id>/` com:
- `spec.md` — objetivo, escopo, área/domínio, entradas/saídas, guard-rails;
- `prompts/` — prompts versionados;
- `evals/` — casos de avaliação e critérios de qualidade.

## Guard-rails inegociáveis
- **Human-in-the-loop obrigatório** em qualquer contexto clínico.
- **Nenhum agente grava PHI** (ver `40-quality/data-governance`).
- Todo agente respeita os [Princípios](../../00-company/governance/principles.md) e a hierarquia de precedência.
- Regras globais de agentes: [`AGENTS.md`](../../AGENTS.md) na raiz.
