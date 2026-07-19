---
id: initiative.2026.onda-1.financeiro
title: Plano financeiro de lançamento (capital R$400k)
owner: cfo
status: active
tags: [initiative, finance, unit-economics, reference]
summary: Alocação de capital, custo fixo, ponto de equilíbrio e economia do Clube de assinatura.
last_reviewed: 2026-07-03
related: [initiative.2026.onda-1-fundacao, company.business-model, company.adr.0005]
---

# Plano financeiro de lançamento

**Capital total disponível: R$ 400.000** (CAPEX + reserva de OPEX).
**Abertura-alvo: 01/2027.**

> Todos os valores são **premissas de planejamento**. Substituir por orçamentos
> reais de Uberlândia antes de comprometer capital.

## Alocação de capital — dois cenários

| Item | Enxuto (imóvel já adaptado) | Confortável (obra pesada) |
|---|---|---|
| Reforma/adequação | R$ 40–60k | R$ 150–250k |
| Mobiliário e ambientação | R$ 40k | R$ 60k |
| TI, rede, telefonia | R$ 20k | R$ 30k |
| Equipamentos próprios (macas, esfigmo, balança) | R$ 15k | R$ 25k |
| ECG / MAPA / Holter | **R$ 0 (comodato)** | R$ 0 |
| Marca, site, identidade | R$ 15k | R$ 30k |
| Abertura legal, licenças, consultoria sanitária | R$ 10k | R$ 20k |
| Marketing pré-lançamento | R$ 15k | R$ 30k |
| **CAPEX total** | **~R$ 155k** | **~R$ 275k** |
| Reserva OPEX (6 meses) | ~R$ 192k | ~R$ 240k |
| **TOTAL** | **~R$ 347k ✅** | **~R$ 515k ❌** |

**Decisão forçada:** priorizar **imóvel já com layout clínico** (ex-clínica, com
histórico de licença sanitária). Reduz obra **e** encurta o processo na Vigilância —
duplo ganho de capital e de prazo.

## Custo fixo mensal (cenário enxuto)

| Item | Faixa |
|---|---|
| Aluguel + condomínio + IPTU (~150–200 m², 4 consultórios) | R$ 8–14k |
| Equipe administrativa (2 recepção + 1 técnico) | R$ 11–13k |
| Sistemas (EMR, CRM, WhatsApp API, telefonia, assinatura) | R$ 1,5–3k |
| Bioimpedância (comodato ilimitado) | R$ 0,75k |
| Contabilidade | R$ 1,2–2k |
| Utilidades, limpeza, materiais | R$ 3–5k |
| Marketing recorrente | R$ 3–8k |
| **Total fixo** | **~R$ 29–45k/mês** (planejar R$ 32k) |

**Vantagem estrutural:** o médico é **FFS = custo variável**. Não há folha médica fixa.
Isso derruba o ponto de equilíbrio e protege o caixa em meses fracos.

## Ponto de equilíbrio

Com contribuição de ~R$ 100/consulta (preço cheio, após repasse ao médico):
**~300–350 consultas/mês (≈16–18/dia)** cobrem o custo fixo, **antes** da margem de exames.
Com 5 especialidades = 3–4 consultas/dia por especialidade. **Alcançável.**

## Clube de assinatura — R$ 39,90/mês

Modelo: sem gratuidades caras; direito a pagar menos (consulta R$ 150 vs R$ 250,
exames 30–40% off, bioimpedância trimestral inclusa).

**O que está correto:** não há risco de sinistralidade — o paciente sempre paga o
custo do que consome. O risco catastrófico de plano de saúde **não existe aqui**.

**Riscos reais identificados:**
1. **Alto utilizador.** Mensalidade anual = R$ 478,80. Desconto de R$ 100/consulta
   → o Clube cobre até **~4,8 consultas/ano**. Crônicos fazem 6–8 → linha de
   consultas fica negativa, compensada apenas pela margem de exames.
2. **De quem sai o desconto?** Se o repasse ao médico for **valor fixo**, na consulta
   de R$ 150 a clínica pode ficar com ~zero.
   → **Recomendação: repasse percentual**, dividindo o desconto entre clínica e médico.
3. **Canibalização:** paciente que pagaria R$ 250 migra para R$ 150.

**Controles obrigatórios:**
- KPI **margem de contribuição por assinante** acompanhado desde o mês 1.
- **Taxa de conversão em exames (attach rate)** — é o motor de lucro do Clube.
- **Guard-rail ético (ADR 0005):** exame só por indicação de protocolo, com auditoria.
  O lucro cresce com exames; o controle impede que isso vire demanda induzida.

## Produtos adicionais recomendados (alta margem, baixo CAPEX)

| # | Produto | Racional | CAPEX |
|---|---|---|---|
| 1 | **Check-up executivo B2B** | Uberlândia é polo corporativo; preenche agenda ociosa; recorrente | ~zero |
| 2 | **Programa de emagrecimento/metabólico** | Bioimpedância ilimitada = **custo marginal zero**; alta recorrência | zero |
| 3 | **Polissonografia domiciliar (apneia)** | Sinergia neuro + cardio + obesidade | comodato |
| 4 | **Ergometria** | Cardio, check-up, pré-operatório | comodato |
| 5 | **Espirometria** | Baixo custo, minutos, clínica/família | R$ 8–15k |
| 6 | **Telemedicina de seguimento** | Custo marginal ~zero; captura catchment de 2–3 mi | ~zero |

> **Insight:** a bioimpedância ilimitada (R$750/mês) tem custo marginal **zero**.
> Todo produto construído sobre ela é margem quase pura.

## Verificações pendentes
- Termos dos **comodatos** (ECG/MAPA/Holter): mensalidade fixa, custo por exame ou volume mínimo?
- Orçamentos reais: aluguel, reforma, salários em Uberlândia.
- Definir **modelo de repasse** ao médico (percentual recomendado).
