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
| Modelo | _PREENCHER: nome e versão exatos do modelo configurado nas tarefas agendadas_ |
| Como publica | Pela API do WordPress, via o plugin O4AI (servidor MCP do próprio site) |
| Instruções | [regras/REGRAS-DO-AGENTE.md](regras/REGRAS-DO-AGENTE.md) (cópia fiel do que o agente lê) |
| Instruções da tarefa agendada | _PREENCHER: colar aqui o texto da tarefa agendada, se houver algo além de "siga as regras"_ |

Quando o modelo muda, a troca entra no [CHANGELOG.md](CHANGELOG.md) com a data. Cada análise
mostra, no quadro "Registro desta análise", a versão da metodologia e, quando informado, o modelo
usado.

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
