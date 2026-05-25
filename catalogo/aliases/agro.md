---
tipo: alias_collection
categoria: agro_pet
company_id: 24710665-1440-4ec1-9e33-560dfdf35490
---

# Aliases — Agro / Pet / Vet

## ração

```yaml
alias: racao
display: ração
must_have:
  - racao
must_not_have: []
peso: 1.0
```

## ração para cachorro

```yaml
alias: racao cachorro
display: ração para cachorro
must_have:
  - racao
must_not_have:
  - gato
  - felin
  - equin
  - aves
  - bovino
peso: 1.0
observacao: ração canina; filtra gato/equino/aves/bovino
```

## ração para gato

```yaml
alias: racao gato
display: ração para gato
must_have:
  - racao
  - gat
must_not_have:
  - cao
  - cachorro
  - canin
peso: 1.0
observacao: ração felina; filtra cão/cachorro
```

## ração para cães (sinônimo)

```yaml
alias: racao caes
display: ração para cães
must_have:
  - racao
must_not_have:
  - gato
  - felin
  - equin
  - aves
peso: 1.0
```

## ração para cão (sinônimo)

```yaml
alias: racao cao
display: ração para cão
must_have:
  - racao
must_not_have:
  - gato
  - felin
  - equin
  - aves
peso: 1.0
```

## ração para felino (sinônimo)

```yaml
alias: racao felino
display: ração para felino
must_have:
  - racao
  - gat
must_not_have:
  - cao
  - cachorro
  - canin
peso: 1.0
```

## filhote

```yaml
alias: filhote
display: filhote
must_have:
  - filhote
must_not_have: []
peso: 1.0
```

## adulto

```yaml
alias: adulto
display: adulto
must_have:
  - adulto
must_not_have: []
peso: 1.0
```

## sênior

```yaml
alias: senior
display: sênior
must_have:
  - senior
must_not_have: []
peso: 1.0
```

## vermífugo

```yaml
alias: vermifugo
display: vermífugo
must_have:
  - vermifug
must_not_have: []
peso: 1.0
```

## antipulgas

```yaml
alias: antipulga
display: antipulgas
must_have:
  - pulga
must_not_have: []
peso: 1.0
```

## coleira

```yaml
alias: coleira
display: coleira
must_have:
  - coleira
must_not_have:
  - coleirinha
  - enfeite
peso: 1.0
observacao: coleira pet; exclui acessórios decorativos
```

## cloro

```yaml
alias: cloro
display: cloro
must_have:
  - cloro
must_not_have: []
peso: 1.0
```

## piscina

```yaml
alias: piscina
display: piscina
must_have:
  - piscina
must_not_have: []
peso: 1.0
```

## defensivo

```yaml
alias: defensivo
display: defensivo agrícola
must_have:
  - defensivo
must_not_have: []
peso: 1.0
observacao: produto regulamentado; sempre escalar pra humano
```

## semente

```yaml
alias: semente
display: semente
must_have:
  - semente
must_not_have: []
peso: 1.0
```
