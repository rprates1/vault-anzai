---
tipo: proposta_pendente
id: prop_002_telha_fluxo
status: pendente
criada_em: "2026-05-25T16:40:00"
categoria: fluxo
arquivo_alvo: agente/instrucoes_gerais.md
correcoes_count: 3
correcoes_window: "2026-05-23 a 2026-05-25"
titulo: "Perguntar metragem do telhado antes de oferecer telha"
mudanca_proposta:
  tipo: adicao
  bloco_alvo: "Quando cliente pedir telha"
  antes: null
  depois:
    nova_regra: "Antes de sugerir marca ou quantidade, perguntar a metragem do telhado pra calcular o numero correto de pecas"
correcoes_exemplos:
  - cliente: "quero telha"
    ia_sugeriu: "Temos telha Eternit fibrocimento. Quantas pecas precisa?"
    operador_enviou: "Telha pra que metragem de telhado? Pra eu calcular as pecas certinhas."
    ts: "2026-05-23T11:20:00"
  - cliente: "preciso de telha pra cobrir uma area"
    ia_sugeriu: "Telha Eternit, quantas?"
    operador_enviou: "Qual a metragem? Ai eu te falo quantas pecas precisa."
    ts: "2026-05-24T15:00:00"
  - cliente: "tem telha?"
    ia_sugeriu: "Tem, qual quantidade?"
    operador_enviou: "Tem sim. Pra cobrir quantos metros? Ai ja te passo a quantidade certa."
    ts: "2026-05-25T10:30:00"
---

# Perguntar metragem do telhado antes de oferecer telha

3 conversas mostraram que o operador sempre redireciona a pergunta de "quantidade" pra "metragem", porque o cliente leigo nao sabe calcular. Sugestao e incluir essa regra no fluxo do agente.
