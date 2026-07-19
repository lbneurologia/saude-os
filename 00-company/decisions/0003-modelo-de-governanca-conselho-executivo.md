---
id: company.adr.0003
title: 0003 - Modelo de governança (Conselho Executivo Permanente)
owner: ceo
status: active
tags: [adr, governance, principles]
summary: Adota o Conselho Executivo, os 13 princípios inegociáveis e a hierarquia de precedência como governança vinculante.
last_reviewed: 2026-07-19
related: [company.governance, company.principles, company.adr.0001]
---

# 0003 - Modelo de governança (Conselho Executivo Permanente)
- **Status:** accepted
- **Data:** 2026-07-19
- **Decisores:** Conselho Executivo (CEO, COO, CFO, CMO, CIO, CTO, Diretores)

## Contexto
Foi estabelecido um charter definindo que a empresa opera por um Conselho
Executivo multidisciplinar, sob 13 princípios inegociáveis, com raciocínio em 10
passos e documentação como fonte única. Manter isso apenas em conversa violaria
os próprios princípios #10 (Single Source of Truth) e #11 (Documentation First).

## Decisão
Adotar como governança **vinculante**, documentada em:
- `00-company/governance/README.md` — Conselho Executivo, lentes e protocolo de raciocínio;
- `00-company/governance/principles.md` — 13 princípios + **hierarquia de precedência**.

Toda decisão relevante é registrada como ADR (MADR) e indexada em `90-meta/adr-index`.
Padrões de documentação **não são duplicados** — permanecem em `90-meta/standards`.

## Melhoria sobre o solicitado
Adicionada uma **hierarquia de precedência** para desempate entre princípios em
conflito (segurança do paciente → ética/legal → evidência → operação → automação/IA),
pois os 13 princípios podem colidir (ex.: *AI First* vs *Evidence Based Medicine*).
Justificativa: em saúde, eficiência/automação/IA nunca sobrepõem segurança, ética
ou evidência — alinhado a Mayo Clinic / JCI. IA clínica é sempre human-in-the-loop.

## Consequências
- (+) Governança rastreável, princípios acionáveis, conflitos resolvíveis.
- (+) Agentes de IA e humanos operam sob as mesmas regras (roster em `90-meta/catalog/agents.yaml`).
- (-) Exige disciplina: toda decisão relevante vira ADR; enforcement por CI recomendado.
