# Escala de veredito

Cada análise recebe **um** veredito sobre a notícia e um grau de confiança. Cada afirmação
avaliada dentro da análise usa a mesma escala.

## Vereditos

| Veredito | Quando é usado | Nota na marcação ClaimReview* |
|---|---|---|
| **Verdadeiro** | Os fatos centrais são confirmados por fontes independentes e o contexto apresentado é fiel. | 5 de 5 |
| **Majoritariamente verdadeiro** | O núcleo é verdadeiro, mas há detalhes imprecisos ou que dependem de dados ainda não confirmados. | 4 de 5 |
| **Parcialmente verdadeiro** | Mistura fatos comprovados com afirmações sem base ou exageradas. | 3 de 5 |
| **Enganoso** | Usa fatos reais, mas omite ou distorce o contexto a ponto de levar a uma conclusão errada. | 2 de 5 |
| **Falso** | Os fatos centrais são desmentidos por fontes confiáveis e independentes. | 1 de 5 |
| **Inconclusivo** | Ainda não há informação pública suficiente para confirmar ou desmentir. | sem nota (só o nome) |

\* A nota numérica existe apenas para a marcação técnica [schema.org/ClaimReview](https://schema.org/ClaimReview)
que acompanha cada análise e é lida por ferramentas de busca de checagens. Ela não é uma
pontuação usada para decidir o veredito: o veredito é escolhido pelos critérios da coluna do
meio, e a nota apenas o traduz.

## Confiança

| Confiança | Quando |
|---|---|
| **Alta** | Fontes primárias (documentos, dados oficiais) concordam entre si. |
| **Média** | Fontes boas, mas com lacunas. |
| **Baixa** | Poucas fontes ou fatos ainda em andamento. |

## Regras de uso

- O veredito vale para **a notícia como foi apresentada**, não para as pessoas envolvidas.
- O mesmo critério vale para qualquer lado político. A
  [revisão por amostragem](auditoria/REVISAO-POR-AMOSTRAGEM.md) compara vereditos de afirmações
  vindas de lados diferentes para verificar isso.
- A escala não tem pesos ocultos nem pontuação automática: não existe fórmula que some fontes ou
  afirmações para chegar ao veredito. Ele é um julgamento, explicado no texto.
- Se os fatos mudarem, o veredito muda, e a mudança fica registrada no histórico da análise.

## Onde isso está no código do site

A escala é definida no plugin do site (função `nn_vereditos()`); os textos acima são os mesmos
que aparecem no site. Qualquer mudança nela entra no [CHANGELOG.md](CHANGELOG.md).
