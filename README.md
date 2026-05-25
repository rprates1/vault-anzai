# Vault Anzai — cérebro do agente vendedor

**Versão final v3** — fusão das melhores partes do plano original com a personalidade real extraída do workflow v3.2 em produção.

Tudo aqui dentro é lido pelo agente vendedor IA da Casa Anzai e usado pra responder os clientes no WhatsApp.

## Como funciona

1. Você edita os arquivos `.md` neste vault no Obsidian
2. Quando você dá `git push`, o sistema automático lê suas mudanças
3. Em ~2 minutos o agente IA já está usando as novas regras/textos
4. Sem programador, sem deploy

## Estrutura completa

```
vault-anzai/
├── _meta/                          ← Config da empresa
│   └── company.md
│
├── agente/                         ← PERSONALIDADE E REGRAS DO VENDEDOR
│   ├── personalidade.md            ← Tom de voz real do balconista Anzai
│   ├── instrucoes_gerais.md        ← Estrutura de resposta, busca vs refinamento
│   ├── regras_comerciais.md        ← Frete, desconto, garantia
│   └── tabu.md                     ← O que JAMAIS pode fazer
│
├── catalogo/                       ← COMO O SISTEMA ENTENDE PRODUTOS
│   ├── aliases/                    ← Sinônimos e regras de não-confundir
│   │   ├── construcao.md
│   │   ├── hidraulica.md
│   │   ├── eletrica.md
│   │   ├── ferramentas.md
│   │   └── agro.md
│   ├── taxonomia.md
│   ├── marcas.md
│   └── excecoes.md
│
└── conhecimento/                   ← BASE OPERACIONAL
    ├── objecoes/
    │   ├── preco_alto.md           ← "Tá caro"
    │   ├── vou_pensar.md           ← "Vou pensar"
    │   └── desconfianca.md         ← "Isso aguenta?"
    ├── faq/
    │   ├── horario_entrega.md
    │   ├── formas_pagamento.md
    │   └── garantia.md
    ├── playbooks/
    │   ├── cliente_construtor.md
    │   ├── cliente_dona_de_casa.md
    │   └── fechamento_pedido.md    ← Tom específico do "Confirma o pedido"
    └── casos_reais/
        └── reforma_completa.md
```

## Regras de edição

- ✅ Pode editar qualquer arquivo `.md`
- ✅ Pode adicionar arquivos novos nas pastas existentes
- ⚠️ Não renomeie pastas (vai quebrar a indexação)
- ⚠️ Cada arquivo tem um **frontmatter YAML** no topo (entre `---`) — não mexa nele a não ser que saiba o que tá fazendo
- ❌ Não delete o `_meta/company.md`

## Quem edita o quê

- **Dono / Gerente:** `agente/`, `conhecimento/`, `catalogo/excecoes.md`
- **Vendedor sênior:** `conhecimento/objecoes/`, `conhecimento/casos_reais/`, `conhecimento/playbooks/`
- **Operação:** `catalogo/aliases/`, `catalogo/marcas.md`
- **IRPIA (suporte técnico):** `_meta/`, `catalogo/taxonomia.md`

---

## Composição da v3 (de onde veio cada coisa)

### Do workflow v3.2 em produção (real)
- Identidade: "atendente da Casa Anzai" (sem nome próprio inventado)
- Expressões naturais: "entendi", "perfeito", "faz sentido", "boa pergunta", "isso é bem comum", "boa", "anotando", "tá certinho?"
- Regras técnicas: máximo 3 opções, exceção pra pedido grande, nunca inventar produtos
- Conceito **busca nova vs refinamento** (central)
- Estrutura de resposta: confirmação + lista + pergunta
- Tom de fechamento: "boa, deixa eu confirmar", "Demorou!"
- Tratamento de erro: "Pô, deixa eu chamar um vendedor"

### Adicionado (estrutura + contexto regional)
- Vocabulário regional do interior paulista (saco de massa, tijolinho, encanamento, etc)
- Limites comerciais explícitos (sem desconto sem autorização, etc)
- Tabu (concorrentes, política, religião, etc)
- Playbooks de perfil de cliente (construtor, dona de casa)
- Objeções com triggers parseáveis
- FAQ básico (entrega, pagamento, garantia)
- Marcas catalogadas (Votorantim, Tigre, Tramontina, etc)
- Taxonomia hierárquica de categorias
- Aliases técnicos (cimento, ração, cabo, etc) com proteções (must_not_have)
- Frontmatter YAML estruturado em todos os arquivos pra parsing automático

### Removido da versão anterior
- ❌ "Zé da Anzai" (nome inventado)
- ❌ Bordões inventados: "Bora!", "Anota aí:", "Pode confiar." (não eram da v3.2)
- ❌ "Tem sim, chefe" (forçado)
- ❌ Vocabulário fictício

<!-- teste webhook -->
