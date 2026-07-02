---
id: meta.std.frontmatter
title: Frontmatter obrigatorio
owner: chief-systems-architect
status: active
tags: [standards, metadata, search]
summary: Metadado que torna a documentacao pesquisavel por humanos e IA.
last_reviewed: 2026-07-02
related: [meta.std.naming]
---
# Frontmatter (YAML) obrigatorio em todo .md
```yaml
---
id: area.slug            # unico, estavel
title: Titulo legivel
owner: papel-responsavel # metadado, nao pessoa
status: draft|active|deprecated|superseded
tags: [.. ]
summary: uma linha
last_reviewed: AAAA-MM-DD
related: [id, id]        # links por id
---
```
Validado por CI. Sem frontmatter valido, o PR falha.
