---
tipo: "proposta_pendente"
id: "prop_fato_horario_atendimento"
status: "pendente"
criada_em: "2026-06-11T00:55:51.615Z"
atualizada_em: "2026-06-11T00:55:51.615Z"
categoria: "fato"
arquivo_alvo: "agente/regras_comerciais.md"
chave_agrupamento: "fato_horario_atendimento"
correcoes_count: 1
threshold: 1
pronta_pra_revisao: true
titulo: "Horário de atendimento: não afirmar sem confirmação"
mudanca_proposta: 
  tipo: "substituicao"
  antes: 
    mensagem_operador: ""
  depois: 
    sugestao_ia: "Boa tarde! Nosso horário de atendimento:

- Segunda a sexta: 7h às 18h30 
- Sábado: 7h30 às 12h30 
- Domingo: fechado

Em feriados pode variar. Tá certinho assim ou quer que eu confirme se estamos abertos hoje?"
    acao: "recusada_pelo_operador"
correcoes_exemplos: 
  - cliente: "(não capturado)"
    ia_sugeriu: "Boa tarde! Nosso horário de atendimento:

- Segunda a sexta: 7h às 18h30 
- Sábado: 7h30 às 12h30 
- Domingo: fechado

Em feriados pode variar. Tá certinho assim ou quer que eu confirme se estamos abertos hoje?"
    operador_enviou: null
    ts: "2026-06-05T22:36:42.644Z"
    evento: "recusar"
    conversa_id: "cfa97985-76c3-4930-86ce-61ba7a752240"
---

# Horário de atendimento: não afirmar sem confirmação

Gerada automaticamente. 1/1 correções similares acumuladas.
