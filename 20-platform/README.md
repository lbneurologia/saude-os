---
id: platform.readme
title: Platform — tecnologia, dados e IA
owner: cto
status: active
tags: [platform, engineering, clean-architecture]
summary: Especificacoes, catalogo, dados, IA e infra. Codigo de produto vive em repos proprios.
last_reviewed: 2026-07-19
related: [company.adr.0002]
---
# 20-platform
Plano tecnico. Guarda **especificacoes, catalogo, dados, IA e infra** — nao o
codigo-fonte dos produtos, que vive em repositorios proprios catalogados aqui.
- `catalog/` servicos e sistemas · `apps/` e `services/` specs
- `data/` plataforma de dados (FHIR, dashboards) · `ai/` agentes/prompts/evals
- `infra/` infraestrutura como codigo · `shared/` design system e libs
Regra Clean Architecture: dependencias apontam para dentro. PHI nunca no repo.
