# Graph Report - cftvpro-cpz  (2026-07-12)

## Corpus Check
- 3 files · ~29,520 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 33 nodes · 30 edges · 6 communities (5 shown, 1 thin omitted)
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `8b6110f6`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- [[_COMMUNITY_manifest.json|manifest.json]]
- [[_COMMUNITY_sw.js|sw.js]]
- [[_COMMUNITY_CFTVPro — Manual de Uso|CFTVPro — Manual de Uso]]
- [[_COMMUNITY_Passo a passo — Gerar um orçamento|Passo a passo — Gerar um orçamento]]
- [[_COMMUNITY_Histórico de propostas|Histórico de propostas]]
- [[_COMMUNITY_Exportar proposta|Exportar proposta]]

## God Nodes (most connected - your core abstractions)
1. `CFTVPro — Manual de Uso` - 10 edges
2. `Passo a passo — Gerar um orçamento` - 7 edges
3. `Exportar proposta` - 3 edges
4. `Histórico de propostas` - 3 edges
5. `short_name` - 1 edges
6. `start_url` - 1 edges
7. `display` - 1 edges
8. `background_color` - 1 edges
9. `theme_color` - 1 edges
10. `orientation` - 1 edges

## Surprising Connections (you probably didn't know these)
- None detected - all connections are within the same source files.

## Import Cycles
- None detected.

## Communities (6 total, 1 thin omitted)

### Community 0 - "manifest.json"
Cohesion: 0.20
Nodes (9): background_color, description, display, icons, name, orientation, short_name, start_url (+1 more)

### Community 2 - "CFTVPro — Manual de Uso"
Cohesion: 0.25
Nodes (7): Catálogo de produtos, CFTVPro — Manual de Uso, Dúvidas ou problemas, Formas de pagamento, Indicador de margem (uso interno), Instalação no celular (recomendado), Novo orçamento

### Community 3 - "Passo a passo — Gerar um orçamento"
Cohesion: 0.29
Nodes (7): 1. Tipo de projeto, 2. Adicionar equipamentos, 3. Adicionar infraestrutura, 4. Dias de trabalho, 5. Dificuldade, 6. Desconto, Passo a passo — Gerar um orçamento

### Community 4 - "Histórico de propostas"
Cohesion: 0.67
Nodes (3): Backup, Estatísticas, Histórico de propostas

### Community 5 - "Exportar proposta"
Cohesion: 0.67
Nodes (3): Excel (.xlsx), Exportar proposta, PDF

## Knowledge Gaps
- **26 isolated node(s):** `name`, `short_name`, `description`, `start_url`, `display` (+21 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **1 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `CFTVPro — Manual de Uso` connect `CFTVPro — Manual de Uso` to `Passo a passo — Gerar um orçamento`, `Histórico de propostas`, `Exportar proposta`?**
  _High betweenness centrality (0.329) - this node is a cross-community bridge._
- **Why does `Passo a passo — Gerar um orçamento` connect `Passo a passo — Gerar um orçamento` to `CFTVPro — Manual de Uso`?**
  _High betweenness centrality (0.200) - this node is a cross-community bridge._
- **Why does `Exportar proposta` connect `Exportar proposta` to `CFTVPro — Manual de Uso`?**
  _High betweenness centrality (0.075) - this node is a cross-community bridge._
- **What connects `name`, `short_name`, `description` to the rest of the system?**
  _26 weakly-connected nodes found - possible documentation gaps or missing edges._