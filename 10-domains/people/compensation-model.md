---
id: people.compensation
title: Modelo de Remuneração Médica
owner: people-lead
status: active
tags: [people, compensation, ethics]
summary: Fee-for-service simples na abertura; camada variável adiada até haver dados.
last_reviewed: 2026-07-19
related: [company.business-model, company.adr.0005]
---

# Modelo de Remuneração Médica

Princípio: **simplicidade primeiro; complexidade só quando gerar valor.**
O médico é **parceiro estratégico** da plataforma — não empregado, não mero prestador.

## Na abertura (dia 1) — REPASSE FIXO

**Decidido: valor FIXO por consulta realizada** (não percentual).

Racional:
1. **Justo com o médico** — o trabalho é idêntico se o paciente é Clube ou não; o
   desconto do programa de fidelização é custo da clínica, não do médico.
2. **Alinhado à estratégia** — com repasse fixo, a clínica só ganha mais sendo mais
   eficiente e ocupando melhor a agenda. É o modelo "lucro por eficiência".
3. **Simples e transparente** — um número.

### Regra de ouro (a que faz o fixo funcionar)

> **Preço mínimo do portfólio ≥ repasse fixo + margem mínima da clínica.**

A complexidade sai da remuneração e vai para o **preço**, que a clínica controla.
Com margem mínima de R$ 40:

| Cenário | Repasse fixo | Particular R$250 | Preço Clube | Clínica no Clube | Médico a 4 cons./h |
|---|---|---|---|---|---|
| **A (recomendado)** | **R$ 110** | clínica R$ 140 | **R$ 150** | **R$ 40** | **R$ 440/h** |
| B | R$ 130 | clínica R$ 120 | R$ 180 | R$ 50 | R$ 520/h |
| C | R$ 150 | (particular R$ 280) | R$ 200 | R$ 50 | R$ 600/h |

**Consequência crítica:** respeitada a regra, **nenhuma transação fica negativa**.
O membro do Clube que consulta muito rende menos que um particular, mas **nunca
gera prejuízo**. Isso valida a tese do Clube (ver `initiative.2026.onda-1.financeiro`).

### Competitividade para o médico
O que importa ao médico é o ganho **por hora e por mês**, não por consulta:
4 consultas/h × R$110 = **R$ 440/h**; 6h × 20 dias = ~480 consultas = **~R$ 52,8k/mês**.
A proposta não é "pago mais por consulta" — é **"pago bem e garanto agenda cheia,
sem burocracia"**. Esse é o argumento de recrutamento (ver pool dos cooperados no SIR).

### Política de retorno (definir antes da abertura)
Se o retorno for gratuito ao paciente **e** remunerado ao médico, a clínica paga sem faturar.
Exemplo: 40% das consultas geram retorno a R$50 de repasse →
custo efetivo = R$110 + (0,4 × R$50) = **R$130** → margem no Clube cai de R$40 para R$20.

**Recomendado:** retorno com **repasse reduzido** e **janela definida** (ex.: 30 dias),
com o preço da primeira consulta calibrado para absorvê-lo.

### Guard-rails
- **Nenhum pagamento ao médico por exame ou procedimento solicitado** — elimina
  demanda induzida. Pedido segue protocolo e é auditado (ADR 0005).
- **Laudos de exames já estão inclusos nos comodatos** — não pagar médico em duplicidade.
- Retenção inicial vem da **plataforma** (agenda cheia + zero burocracia), não de bônus.

### A definir
- Valor fixo **único** ou **por especialidade** (começar com 1–2 valores, nunca 5).
- Valor do repasse de retorno.

## Fase 2 (quando houver dados)
Camada variável de **qualidade e experiência** — NPS, retenção, adesão a protocolo,
pontualidade — nunca vinculada a volume de procedimentos. Programas longitudinais
poderão ter componente fixo de coordenação (retainer).

## Pergunta permanente
"Como o médico ganha mais sem aumentar o preço?" -> ocupação alta, no-show mínimo,
burocracia zero, demanda dos programas, fluxo regional. Ver `company.business-model`.
