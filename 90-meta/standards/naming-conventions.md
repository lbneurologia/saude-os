---
id: meta.std.naming
title: Convencoes de nomenclatura
owner: chief-systems-architect
status: active
tags: [standards, naming]
summary: Nomes previsiveis para humanos e IA.
last_reviewed: 2026-07-19
related: [meta.std.frontmatter]
---
# Nomenclatura
- Pastas e arquivos em `kebab-case`, sem espacos/acentos.
- Registros datados: prefixo ISO `AAAA-MM-DD-titulo.md`.
- Contratos de interface: `nome.vN.md` (versao explicita).
- IDs no frontmatter: `area.subarea.slug` (estaveis, nunca reciclados).
- Areas de topo com prefixo numerico (`00`, `10`...) para ordenacao determinista.
