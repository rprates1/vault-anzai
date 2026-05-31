---

tipo: recomendacao_collection

categoria: construcao

company_id: 24710665-1440-4ec1-9e33-560dfdf35490

versao: 1

ativo: true

---

# Recomendações — Construção

> Preferências de marca/modelo pra produtos da categoria construção.

> Têm prioridade sobre as orientações gerais quando há conflito.

## cimento estrutural

```yaml

produto: cimento

recomendacao_padrao:

  marca: Tupi

  modelo: CPII-Z 40kg

  motivo: padrão regional, melhor giro, qualidade consistente

alternativas:

  - marca: Tupi

    quando: cliente sensível a preço e Votorantim sem promoção

  - marca: Itaú

    quando: Votorantim e Tupi indisponíveis

nao_recomendar: []

apresentar:

  - se construtor: ir direto na quantidade ("manda quantos sacos?")

  - se leigo: perguntar pra que vai usar antes de sugerir

combo_natural:

  - areia média

  - brita 1

escala_humano_se:

  - pedido acima de 50 sacos

  - cliente pede dimensionamento ou traço técnico

```

## cimento queimado

```yaml

produto: cimento queimado

recomendacao_padrao:

  marca: Cau Cau

  motivo: marca regional reconhecida pra acabamento decorativo

alternativas: []

apresentar:

  - confirmar que cliente sabe que NÃO é cimento estrutural

  - perguntar metragem da área pra calcular quantidade

escala_humano_se:

  - cliente pede orientação de aplicação (escala)

```

## argamassa colante (cimento cola)

```yaml

produto: cimento cola

recomendacao_padrao:

  modelo: AC-2

  motivo: cobre 90% das aplicações (área interna, piso e parede)

alternativas:

  - modelo: AC-1

    quando: parede interna área seca

  - modelo: AC-3

    quando: área externa, piscina, fachada (sempre confirmar uso)

nao_recomendar: []

apresentar:

  - sempre perguntar se é piso, parede, interna ou externa

  - explicar diferença AC-1/AC-2/AC-3 só se cliente perguntar

escala_humano_se:

  - aplicação em fachada/piscina sem certeza do tipo

```

## areia

```yaml

produto: areia

recomendacao_padrao:

  tipo: areia média

  motivo: uso mais comum em assentamento e reboco

alternativas:

  - tipo: areia fina

    quando: reboco fino, acabamento

  - tipo: areia grossa

    quando: concreto estrutural

apresentar:

  - perguntar pra que vai usar antes de sugerir

  - quantidade em metro cúbico ou saco (m³ pra obra, saco pra reparo)

escala_humano_se:

  - pedido a granel acima de 3m³ (vendas materiais)

```

## brita

```yaml

produto: brita

recomendacao_padrao:

  tipo: brita 1

  motivo: granulometria mais usada (concreto, lastro, drenagem)

alternativas:

  - tipo: brita 0

    quando: concreto de pequena espessura

  - tipo: brita 2

    quando: lastro pesado, contrapiso espesso

apresentar:

  - confirmar aplicação antes de sugerir

escala_humano_se:

  - pedido a granel (vendas materiais)

```

## tijolo

```yaml

produto: tijolo

recomendacao_padrao:

  tipo: tijolo de 6 furos (tijolinho)

  motivo: padrão pra vedação em construção residencial

alternativas:

  - tipo: tijolo maciço (tijolão)

    quando: parede estrutural, pequena alvenaria, churrasqueira

  - tipo: bloco cerâmico estrutural

    quando: alvenaria estrutural (escalar pra confirmação técnica)

apresentar:

  - cliente leigo costuma falar "tijolinho/tijolão" — confirmar pelo uso

escala_humano_se:

  - pedido grande (acima de 1000 unidades)

  - alvenaria estrutural

```

## telha

```yaml

produto: telha

recomendacao_padrao:

  marca: Eternit

  tipo: fibrocimento ondulada

  motivo: padrão mais procurado, preço acessível

alternativas:

  - marca: Brasilit

    quando: Eternit indisponível

  - tipo: telha cerâmica

    quando: cliente pede acabamento (estética)

apresentar:

  - perguntar metragem do telhado antes

  - mencionar acessórios (cumeeira, parafusos, espaçador)

combo_natural:

  - cumeeira

  - parafusos com vedação

escala_humano_se:

  - telhado novo (cálculo de quantidade e estrutura)

  - telha traslúcida ou especial

```
