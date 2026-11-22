# Uso de inteligência artificial

## Resumo
As análises são preparadas com auxílio de um assistente de inteligência artificial, que pesquisa
as fontes, monta a linha do tempo, avalia as afirmações e escreve o texto **seguindo as instruções
publicadas em [regras/REGRAS-DO-AGENTE.md](regras/REGRAS-DO-AGENTE.md)**, sem instruções ocultas.
O autor escolhe cada notícia e responde pelo que é publicado.

## Ferramenta em uso

| Item | Valor |
|---|---|
| Assistente | Claude, da Anthropic |
| Modelo | Registrado em cada análise, no quadro "Registro desta análise" (campo `nn_modelo_ia`) |
| Quando roda | Sob demanda: o autor encontra uma notícia e pede a análise. Não há publicação automática agendada |
| Como publica | Pela API do WordPress, via o plugin O4AI (servidor MCP do próprio site) |
| Instruções | [regras/REGRAS-DO-AGENTE.md](regras/REGRAS-DO-AGENTE.md) (cópia fiel do que o agente lê) |

Como o modelo pode mudar com o tempo, ele é registrado em cada análise, e não só aqui.

## O que a IA não faz
- **Não cria imagens.** Só usa mídias reais com crédito e licença.
- **Não inventa fontes.** Toda afirmação precisa de fonte com link; isso pode ser conferido em
  cada análise.
- **Não escolhe as notícias.** Quem escolhe é o autor.

## Limites conhecidos
- Modelos de linguagem podem errar fatos, datas e números. Por isso toda afirmação tem link
  para conferir, e existe a [política de correções](POLITICA-DE-CORRECOES.md).
- Não há revisão humana obrigatória **antes** da publicação. A revisão é feita depois, pelos
  pedidos de correção e pela [revisão por amostragem](auditoria/REVISAO-POR-AMOSTRAGEM.md).
- A pesquisa depende das páginas que o assistente consegue acessar no momento; conteúdo atrás de
  paywall pode ficar de fora.
