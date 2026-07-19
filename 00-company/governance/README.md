---
id: company.governance
title: Governança — Conselho Executivo Permanente
owner: ceo
status: active
tags: [company, governance, decision-making, explanation]
summary: Modelo de decisão da empresa — o Conselho Executivo, as lentes obrigatórias e o protocolo de raciocínio.
last_reviewed: 2026-07-19
related: [company.principles, company.strategy, company.adr.0003, meta.readme]
---

# Governança — Conselho Executivo Permanente

Este documento é a **fonte canônica** do modelo de decisão da empresa. Toda
decisão relevante é analisada por um **Conselho Executivo** de múltiplas lentes,
documentada (ADR) e rastreável. É um **modelo operacional de decisão** — a
estrutura societária/legal é assunto separado (a definir em `governance/`).

## Lentes obrigatórias do Conselho
Toda decisão relevante é avaliada sob estas perspectivas antes de recomendação:

| Papel | Lente |
|---|---|
| CEO | estratégia, visão de longo prazo, crescimento |
| COO | operações, eficiência, processos |
| CFO | sustentabilidade financeira, rentabilidade |
| CMO | marketing, posicionamento, crescimento |
| CIO | tecnologia, arquitetura, inovação |
| CTO | engenharia de software e IA |
| Diretor Médico | medicina baseada em evidências, qualidade assistencial |
| Diretor Científico | pesquisa, ensino, atualização científica |
| Diretor de Experiência do Paciente | hospitalidade, fidelização, atendimento premium |
| Diretor Jurídico | CFM, LGPD, ética, compliance |
| Diretor de Qualidade | ONA, JCI, ISO 9001, melhoria contínua, risco |
| Diretor de BI | indicadores, análise de dados, decisão orientada a dados |

## Protocolo de raciocínio (obrigatório antes de executar)
1. Analisar o problema.
2. Identificar impactos em todas as áreas.
3. Avaliar riscos · 4. custos · 5. benefícios · 6. escalabilidade.
7. Riscos jurídicos · 8. riscos operacionais · 9. impactos ao paciente.
10. Só então recomendar.

## Conflitos e trade-offs
Quando lentes ou princípios colidem, o Conselho **explicita o trade-off** e aplica
a **hierarquia de precedência** definida em [`principles.md`](principles.md):

> segurança do paciente → ética/legal → evidência científica → excelência
> operacional → automação/IA.

Eficiência, automação e IA **nunca** sobrepõem segurança do paciente, ética ou
evidência. Alinhado a Mayo Clinic / JCI.

## Rastreabilidade
- Decisão relevante → **ADR (MADR)** perto do contexto, indexado em `90-meta/adr-index`.
- Mudança estrutural (novo diretório de topo, mover estrutura) → **exige ADR**.
- Padrões de documentação: **não duplicados aqui** — vivem em `90-meta/standards`.
