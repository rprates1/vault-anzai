---
tipo: alias_collection
categoria: agro
company_id: 24710665-1440-4ec1-9e33-560dfdf35490
---

# Aliases — Agro / Pet / Vet

## ração (genérica)

```yaml
alias: racao
display: ração
must_have:
  - racao
must_not_have: []
peso: 0.5
observacao: ração genérica - peso baixo pra deixar variações mais específicas ganharem prioridade
```

## ração para cachorro

```yaml
alias: racao cachorro
display: ração para cachorro
must_have:
  - racao
  - "(cao|cachorro|canin|dog|caes)"
must_not_have:
  - gato
  - felin
  - equin
  - aves
  - bovino
  - frango
  - peixe
peso: 1.0
observacao: ração canina; bloqueia gato/equino/aves/bovino/frango/peixe
```

## ração para gato

```yaml
alias: racao gato
display: ração para gato
must_have:
  - racao
  - "(gat|felin|cat)"
must_not_have:
  - cao
  - cachorro
  - canin
  - equin
  - aves
  - bovino
  - frango
  - peixe
  - dog
peso: 1.0
observacao: ração felina; bloqueia cão/cachorro/equino/aves/bovino/frango/peixe
```

## ração para cão (sinônimo de cachorro)

```yaml
alias: racao cao
display: ração para cão
must_have:
  - racao
  - "(cao|cachorro|canin|dog|caes)"
must_not_have:
  - gato
  - felin
  - equin
  - aves
  - frango
peso: 1.0
```

## ração para cães (sinônimo)

```yaml
alias: racao caes
display: ração para cães
must_have:
  - racao
  - "(cao|cachorro|canin|dog|caes)"
must_not_have:
  - gato
  - felin
  - equin
  - aves
  - frango
peso: 1.0
```

## ração para felino (sinônimo de gato)

```yaml
alias: racao felino
display: ração para felino
must_have:
  - racao
  - "(gat|felin|cat)"
must_not_have:
  - cao
  - cachorro
  - canin
  - equin
  - aves
  - frango
peso: 1.0
```

## ração para frango

```yaml
alias: racao frango
display: ração para frango
must_have:
  - racao
  - "(frango|aves|ave|galinh|postura|engorda)"
must_not_have:
  - gato
  - cao
  - cachorro
  - equin
  - bovino
peso: 1.0
```

## ração para peixe

```yaml
alias: racao peixe
display: ração para peixe
must_have:
  - racao
  - peixe
must_not_have:
  - gato
  - cao
  - cachorro
peso: 1.0
```

## ração para boi (bovino)

```yaml
alias: racao boi
display: ração para bovino
must_have:
  - racao
  - "(boi|bovino|gado|vaca)"
must_not_have:
  - gato
  - cao
  - cachorro
  - aves
  - frango
  - peixe
peso: 1.0
```

## filhote

```yaml
alias: filhote
display: filhote
must_have:
  - "(filhote|junior|puppy|baby)"
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
  - "(senior|idoso|7\\+)"
must_not_have: []
peso: 1.0
```

## vermífugo

```yaml
alias: vermifugo
display: vermífugo
must_have:
  - "(vermifug|verminose|antiverm)"
must_not_have: []
peso: 1.0
```

## antipulgas

```yaml
alias: antipulga
display: antipulgas
must_have:
  - "(pulga|antipulg|carrapat)"
must_not_have: []
peso: 1.0
```

## coleira (pet)

```yaml
alias: coleira
display: coleira
must_have:
  - coleira
must_not_have:
  - enfeite
  - decorativ
peso: 1.0
observacao: coleira pet; exclui decorativas
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

## defensivo agrícola

```yaml
alias: defensivo
display: defensivo agrícola
must_have:
  - "(defensiv|herbicid|inseticid|fungicid)"
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
