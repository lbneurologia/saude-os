---
id: meta.std.data-classification
title: Classificacao de dados e fronteira de PHI
owner: quality-officer
status: active
tags: [standards, lgpd, security, phi]
summary: O que pode e o que nunca pode entrar no repositorio.
last_reviewed: 2026-07-19
related: [quality.data-governance]
---
# Classificacao de dados
| Classe | Exemplos | Pode no repo? |
|---|---|---|
| Publico | marca, conteudo de marketing | Sim |
| Interno | processos, SOPs, protocolos | Sim |
| Confidencial | contratos, financeiro | Restrito (acesso) |
| **PHI / dado pessoal** | **prontuario, paciente** | **NUNCA** |

PHI vive em sistemas clinicos (FHIR), nunca em git. Ver `40-quality/data-governance`.
