---
id: root.readme
title: Sistema Operacional da Empresa (Company OS)
owner: chief-systems-architect
status: active
tags: [start-here, overview]
summary: Mapa-mestre do Company OS. Comece aqui.
last_reviewed: 2026-07-19
related: [root.company, meta.readme]
---

# Company OS — START HERE

Este repositório é o **Sistema Operacional** da empresa de saúde: processos,
documentação, governança, especificações e inteligência — orientado por
Documentação Viva, DDD e melhoria contínua.

> **Lei constitucional:** cada conceito tem **um único lar canônico**.
> Todo o resto **referencia** — nunca copia.

## Dois planos
- **Este repo (Company OS):** conhecimento, governança e especificações.
- **Repos de produto:** o código executável vive em repositórios próprios,
  apenas **catalogados** em `20-platform/catalog` e `90-meta/catalog`.

## Missão tripartite (sistema de saúde acadêmico)
Assistência (`clinical-care`) · Pesquisa (`research`) · Ensino (`academy`).

## Áreas de topo
| Área | Papel | Tipo |
|---|---|---|
| `00-company` | estratégia, governança, marca, cultura, decisões | permanente |
| `10-domains` | domínios de negócio (verticais DDD autocontidos) | permanente |
| `20-platform` | especificações, catálogo, dados, IA, infra | permanente |
| `30-operations` | value streams, standard work, rede de unidades | permanente |
| `40-quality` | QMS, LGPD, data-governance, segurança, acreditação | permanente |
| `50-growth` | marketing, relacionamento, expansão | permanente |
| `70-initiatives` | projetos e experimentos temporários | temporário |
| `90-meta` | padrões, templates, glossário, catálogo, ADRs | permanente |
| `_archive` | material aposentado (imutável) | congelado |

## Como navegar
1. Leia este README e o `COMPANY.yaml` (manifesto legível por máquina).
2. Padrões e templates: `90-meta/standards` e `90-meta/templates`.
3. Um domínio: `10-domains/<x>/README.md` (todos seguem o mesmo template).
4. Decisões: `00-company/decisions` e índice em `90-meta/adr-index`.

## Renomear a empresa
O nome está isolado em `COMPANY.yaml` (campo `name`) e neste README. Renomeie a
pasta raiz e ajuste esse campo — nada mais depende do nome.
