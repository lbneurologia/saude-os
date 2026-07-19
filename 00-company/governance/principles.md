---
id: company.principles
title: Princípios Inegociáveis (Leadership Principles)
owner: ceo
status: active
tags: [company, governance, principles, reference]
summary: Os 13 princípios que governam toda decisão, e a hierarquia de desempate em caso de conflito.
last_reviewed: 2026-07-19
related: [company.governance, company.adr.0003]
---

# Princípios Inegociáveis

Fonte canônica. Toda decisão, documento, protocolo, código ou agente de IA deve
respeitá-los. Referencie por `id` — não recopie.

1. **Patient Obsession** — toda decisão deve melhorar a experiência do paciente.
2. **Scientific Excellence** — recomendações clínicas com fundamentação científica atualizada.
3. **Evidence Based Medicine** — jamais práticas sem respaldo científico adequado.
4. **Ethics First** — nunca soluções incompatíveis com ética médica ou legislação.
5. **Long Term Thinking** — priorizar o sustentável no longo prazo (horizonte 20 anos).
6. **Operational Excellence** — eficiência sem reduzir qualidade.
7. **Continuous Improvement** — todo processo pode ser melhorado (PDCA).
8. **Technology First** — sempre avaliar como a tecnologia simplifica processos.
9. **AI First** — sempre considerar IA como ferramenta estratégica.
10. **Single Source of Truth** — cada informação tem um único local oficial.
11. **Documentation First** — tudo deve ser documentado; nada vive só em conversas.
12. **Automation by Default** — toda tarefa repetitiva é candidata à automação.
13. **Data Driven Decisions** — toda decisão importante usa indicadores.

## Hierarquia de precedência (desempate)

Os princípios podem colidir (ex.: *AI First / Automation by Default* vs *Ethics
First / Evidence Based Medicine*). Em conflito, vale esta ordem — a de cima vence:

1. **Segurança do paciente** (Patient Obsession aplicado a dano)
2. **Ética e legalidade** (Ethics First, CFM, LGPD)
3. **Evidência científica** (Evidence Based, Scientific Excellence)
4. **Excelência operacional e sustentabilidade** (Operational Excellence, Long Term)
5. **Automação e IA** (Technology First, AI First, Automation by Default)

> Regra de ouro em saúde: eficiência, automação e IA **nunca** sobrepõem
> segurança, ética ou evidência. IA em contexto clínico é sempre
> **human-in-the-loop** (ver `20-platform/ai`).
