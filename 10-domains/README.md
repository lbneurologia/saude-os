---
id: domains.readme
title: Domains — dominios de negocio (DDD)
owner: chief-systems-architect
status: active
tags: [domains, ddd]
summary: Verticais autocontidos. Missao tripartite: assistencia, pesquisa, ensino.
last_reviewed: 2026-07-19
related: [domain.clinical-care, meta.tpl.domain]
---
# 10-domains
Cada dominio e um **vertical autocontido** e segue o mesmo template
(`90-meta/templates/domain-README.md`). Interagem apenas por `interfaces/`.

## Classificacao (DDD)
- **Core:** clinical-care, patient-experience, research, academy
- **Supporting:** access-scheduling, billing-revenue, diagnostics-exams, telehealth, pharmacy
- **Generic:** people, facilities

`clinical-care` esta **totalmente instanciado** como referencia. Os demais sao sementes.
