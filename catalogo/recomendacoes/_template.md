---

tipo: recomendacao_collection

categoria: TEMPLATE

company_id: 24710665-1440-4ec1-9e33-560dfdf35490

versao: 1

ativo: false

---

# Recomendações — TEMPLATE (não usar em produção)

> Modelo base pra criar arquivos de recomendação por categoria.

> Copia esse arquivo, renomeia pra categoria.md, troca ativo: false por true,

> e preenche os blocos de cada produto.

## [nome do produto] (exemplo: cimento estrutural)

```yaml

produto: cimento estrutural

recomendacao_padrao:

  marca: Votorantim

  modelo: CPII-Z

  motivo: melhor giro, qualidade consistente, padrão regional

alternativas:

  - marca: Tupi

    quando: quando Votorantim em falta ou cliente pede mais barato

  - marca: Itaú

    quando: obra que pede cimento branco/especial

nao_recomendar:

  - marca: [marca-que-evita]

    motivo: alta taxa de devolução / qualidade inconsistente

apresentar:

  - mencionar disponibilidade imediata

  - se construtor: ir direto na quantidade

  - se leigo: explicar diferença CPII vs CPV

combo_natural:

  - areia média

  - brita 1

escala_humano_se:

  - pedido > 50 sacos (vendas materiais)

  - cliente pede análise técnica de traço

```

## Como preencher

- produto: o nome canônico (mesmo do alias se houver)

- recomendacao_padrao: marca/modelo que SEMPRE é a primeira opção

- alternativas: até 3, com regra clara de "quando"

- nao_recomendar: marcas a evitar e por quê (importante pro agente não sugerir)

- apresentar: dicas de tom/abordagem específicas

- combo_natural: produtos que vão junto (pra perguntar se quer levar)

- escala_humano_se: gatilhos pra passar pro vendedor humano
