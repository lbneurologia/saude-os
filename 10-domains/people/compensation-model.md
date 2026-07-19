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

### Política de retorno — DECIDIDA
**Retorno sem custo ao paciente em até 30 dias, sem repasse adicional ao médico.**

Consequência contratual: **o repasse remunera um EPISÓDIO DE CUIDADO**
(1ª consulta + retorno em 30 dias), **não uma visita**. Isso deve estar explícito
no contrato do médico — caso contrário o profissional percebe trabalho não
remunerado e a promessa de "parceiro" é queimada.

**Ganho real do médico** (com 40% de taxa de retorno): ~2,9 episódios/hora →
**~R$ 314/h** (e não os R$440/h de um cenário sem retorno). Este é o número honesto
para a conversa de recrutamento.

**O custo do retorno não é caixa — é agenda.** Com 40% de retorno, ~29% da
capacidade de sala gera zero receita. A métrica passa a ser **contribuição por slot**:

| Serviço | Contribuição | Slots consumidos | Contribuição/slot |
|---|---|---|---|
| Especialidade particular | R$ 140 | 1,4 | R$ 100 |
| Especialidade Clube | R$ 40 | 1,4 | R$ 29 |

**Mitigação (Lean):** usar **slot de retorno mais curto** (ex.: 15 min vs 30 min da
primeira consulta) reduz o consumo de 1,4 para ~1,2 slots e eleva a contribuição
por slot para ~R$ 117.

### Guard-rails
- **Nenhum pagamento ao médico por exame ou procedimento solicitado** — elimina
  demanda induzida. Pedido segue protocolo e é auditado (ADR 0005).
- **Laudos de exames já estão inclusos nos comodatos** — não pagar médico em duplicidade.
- Retenção inicial vem da **plataforma** (agenda cheia + zero burocracia), não de bônus.

## Tabela vigente (decidida 2026-07-19)

| Serviço | Particular | Clube | Repasse fixo | Clínica particular | Clínica Clube |
|---|---|---|---|---|---|
| **Especialidades médicas** | R$ 250 | R$ 150 | **R$ 110** | R$ 140 | **R$ 40** |
| **Nutrição** | R$ 160 | R$ 110* | **R$ 70** | R$ 90 | **R$ 40** |

\* preço Clube da nutrição **proposto**, pendente de confirmação.

**Por que nutrição tem repasse próprio:** com repasse único de R$110, a consulta de
nutrição no Clube ficaria **negativa** (R$110 de preço − R$110 de repasse). Dois
valores de repasse mantêm a regra de ouro (margem mínima de R$40) em todos os casos.

Dois números apenas — a simplicidade é preservada.

### A definir
- Confirmar o preço Clube da nutrição (proposto: R$ 110).
- Reavaliar os valores quando houver dados reais de taxa de retorno e ocupação.

## Fase 2 (quando houver dados)
Camada variável de **qualidade e experiência** — NPS, retenção, adesão a protocolo,
pontualidade — nunca vinculada a volume de procedimentos. Programas longitudinais
poderão ter componente fixo de coordenação (retainer).

## Pergunta permanente
"Como o médico ganha mais sem aumentar o preço?" -> ocupação alta, no-show mínimo,
burocracia zero, demanda dos programas, fluxo regional. Ver `company.business-model`.
