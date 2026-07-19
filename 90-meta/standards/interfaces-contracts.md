---
id: meta.std.interfaces
title: Contratos entre dominios (interfaces versionadas)
owner: cto
status: active
tags: [standards, ddd, contracts, api]
summary: Dominios so se comunicam por contratos versionados, como APIs publicas.
last_reviewed: 2026-07-19
related: [meta.std.naming]
---
# Contratos de interface
Inspirado em disciplina de API (Stripe). Um dominio nunca acessa o miolo de outro;
ele consome um **contrato** publicado em `<dominio>/interfaces/`.

Cada contrato tem:
- **nome e versao** (`patient-referral.v1.md`);
- **schema** (campos, tipos) — JSON Schema / FHIR quando aplicavel;
- **produtor e consumidores**;
- **changelog** e politica de retrocompatibilidade (breaking = nova versao).
