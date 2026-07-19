---
id: domain.clinical-care
title: Clinical Care — assistencia clinica
owner: clinical-director
status: active
tags: [domain, core, clinical]
summary: O ato medico: protocolos baseados em evidencias, seguranca e desfechos.
last_reviewed: 2026-07-19
related: [domains.readme, quality.clinical-safety]
---
# Clinical Care (dominio de referencia)
Tipo: **core** · Dono: **clinical-director**

Coracao clinico da empresa. Define **o que** e **como** da pratica medica,
baseada em evidencias. Nao contem PHI. O software que apoia vive em `20-platform`.

## Estrutura
`language/` `model/` `policies/` `protocols/` `procedures/` `interfaces/`
`metrics/` `decisions/` `specialties/`

## Regras
- Toda conduta clinica e um **protocolo versionado** com nivel de evidencia (GRADE).
- Mudanca de conduta = nova versao + aprovacao clinica (medico-legal).
- Comunicacao com outros dominios so por `interfaces/`.
