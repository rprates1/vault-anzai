---
tipo: alias_collection
categoria: hidraulica
company_id: 24710665-1440-4ec1-9e33-560dfdf35490
---

# Aliases — Hidráulica

## tubo

```yaml
alias: tubo
display: tubo
must_have:
  - tubo
must_not_have: []
peso: 1.0
```

## cano (sinônimo popular de tubo)

```yaml
alias: cano
display: cano (tubo)
must_have:
  - "(cano|tubo)"
must_not_have: []
peso: 1.0
```

## torneira

```yaml
alias: torneira
display: torneira
must_have:
  - torneira
must_not_have: []
peso: 1.0
```

## chuveiro

```yaml
alias: chuveiro
display: chuveiro
must_have:
  - chuveiro
must_not_have: []
peso: 1.0
```

## registro (hidráulico)

```yaml
alias: registro
display: registro hidráulico
must_have:
  - registro
must_not_have:
  - cartorio
  - civil
  - rg
peso: 1.0
observacao: registro hidráulico; exclui registro civil/RG
```

## joelho (conexão)

```yaml
alias: joelho
display: joelho hidráulico
must_have:
  - joelho
must_not_have:
  - ortopedico
  - joelheira
peso: 1.0
observacao: conexão hidráulica; exclui joelheira ortopédica
```

## luva (conexão)

```yaml
alias: luva
display: luva hidráulica
must_have:
  - luva
must_not_have:
  - procedimento
  - nitrilica
  - "latex descart"
  - cirurgica
  - epi
peso: 1.0
observacao: conexão hidráulica; exclui luva EPI/descartável
```

## cola PVC

```yaml
alias: cola pvc
display: cola PVC
must_have:
  - cola
  - pvc
must_not_have: []
peso: 1.0
```

## caixa d'água

```yaml
alias: caixa dagua
display: caixa d'água
must_have:
  - caixa
  - "(agua|d'agua|dagua)"
must_not_have: []
peso: 1.0
```

## conexão

```yaml
alias: conexao
display: conexão
must_have:
  - conex
must_not_have: []
peso: 1.0
```
