---
id: domain.clinical-care.iface.patient-referral.v1
title: Contrato - Encaminhamento de paciente v1
owner: clinical-director
status: active
tags: [contract, interface, fhir]
summary: Contrato de encaminhamento entre clinical-care e outros dominios.
last_reviewed: 2026-07-19
related: [domain.access-scheduling, domain.diagnostics-exams]
---
# patient-referral.v1
- **Produtor:** clinical-care · **Consumidores:** access-scheduling, diagnostics-exams
## Schema (conceitual, alinhado a FHIR ServiceRequest — sem PHI aqui)
| Campo | Tipo | Obrigatorio |
|---|---|---|
| referral_id | string | sim |
| specialty | code | sim |
| priority | enum(routine,urgent) | sim |
| reason_code | code (SNOMED/CID) | sim |
## Changelog
- v1 (2026-07-19): versao inicial.
