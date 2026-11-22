# Como cada análise é feita (metodologia 1.0)

Este documento descreve o processo que está **realmente em uso**. As instruções completas, palavra
por palavra, estão em [regras/REGRAS-DO-AGENTE.md](regras/REGRAS-DO-AGENTE.md); aqui elas estão
explicadas para quem lê.

## 1. Quem escolhe a notícia

O autor escolhe as notícias que vê circulando nas redes sociais e na imprensa e envia o link ou a
captura de tela. **Cada notícia enviada vira uma análise.** Não há cota diária nem meta de
quantidade, e nenhum anunciante, parceiro ou leitor escolhe pautas.

Limite conhecido: a escolha das notícias é do autor, então o conjunto de temas reflete o que ele
vê e acha relevante. Esse é um viés possível de seleção, e é por isso que a
[revisão por amostragem](auditoria/REVISAO-POR-AMOSTRAGEM.md) também olha a distribuição dos temas e
dos vereditos por lado político.

## 2. Já existe análise sobre isso?

Antes de escrever, o site é pesquisado com duas ou três formas de escrever o tema.

- Mesmo fato nos últimos 90 dias: a análise existente é **atualizada**, não duplicada.
- Ângulo realmente diferente (por exemplo, um pelo bolso do leitor e outro pelo lado jurídico):
  pode haver uma segunda análise, com texto, título e estrutura diferentes, e as duas se citam.
- Tema relacionado, fato diferente: análise nova, com link para a anterior.

## 3. Pesquisa

### 3.1 O fato
- **Mínimo de 3 fontes, de pelo menos 2 sites diferentes**; o ideal são 5 ou mais.
- Ordem de preferência e equilíbrio: veja a [política de fontes](POLITICA-DE-FONTES.md).
- Rede social nunca é a única fonte de um fato; serve para registrar **o que alguém disse**.

### 3.2 A "engenharia reversa" da notícia ("Como chegamos aqui")
A pergunta "o que precisou acontecer antes para isso acontecer?" é feita em 2 ou 3 níveis,
procurando de propósito em áreas que parecem não ter relação (economia internacional, câmbio,
clima, leis, decisões de tribunais e agências, decisões de empresas, outros países).

Cada causa encontrada entra na linha do tempo da análise, em ordem cronológica, classificada como:

- **Causa direta**: causou a notícia sem intermediários;
- **Causa indireta**: causou algo que causou a notícia;
- **Contexto**: não causou, mas é preciso saber para entender.

Só entra na linha do tempo o que tem evidência com link. Relação possível mas não comprovada só
aparece no texto, identificada como hipótese.

### 3.3 Afirmações
As 2 a 6 afirmações centrais que circulam sobre o tema (da notícia, de políticos, das redes) são
avaliadas uma a uma, com a mesma escala do veredito e a explicação do porquê.

### 3.4 Visões políticas
Quando o tema divide opiniões, cada lado relevante (governo, oposição, setor afetado,
especialistas…) recebe:

- o **melhor argumento**, como um defensor sério dele escreveria, sem caricatura;
- **a mesma extensão e o mesmo cuidado** que os outros lados;
- o que os fatos confirmam ou contradizem naquele argumento.

## 4. Veredito
Um veredito da [escala](ESCALA-DE-VEREDITO.md) e um grau de confiança (alta, média ou baixa).
O veredito é a avaliação do autor com base nas fontes listadas, não um selo oficial.

## 5. Escrita
- Tom de opinião, sempre amarrada aos fatos. Sem defender partido, candidato, governo ou grupo.
- Sem adjetivos carregados ("desastroso", "vergonhoso", "histórico") fora de citações.
- Nada é inventado: todo número, data, citação e fato precisa estar numa fonte listada.
- Texto original: nenhum parágrafo copiado; citação literal curta (até cerca de 25 palavras),
  entre aspas e com a fonte.
- Números para comparar viram tabela ou gráfico em HTML, com a fonte na legenda.
- O site nunca escreve como redação ou veículo de imprensa ("nossa reportagem", "apuramos",
  "com exclusividade" não são usados).

## 6. Mídias
Toda análise tem imagem destacada e pelo menos uma mídia no corpo, com crédito e licença na
legenda. Fontes aceitas: a imagem da matéria original (com o crédito do veículo), agências
públicas com reprodução autorizada, Agência Brasil (CC BY), Wikimedia Commons com licença
compatível, material oficial de órgãos públicos e publicações públicas incorporadas de redes
sociais. **Nenhuma imagem é criada ou gerada.**

## 7. Publicação
A análise é publicada diretamente, em duas etapas: primeiro o texto completo com todos os campos
(veredito, fontes, linha do tempo, afirmações, visões), depois as mídias no mesmo post.

**Não há etapa de revisão humana antes da publicação.** A revisão acontece depois: por pedidos de
correção dos leitores, por atualizações quando surgem fatos novos e pela
[revisão por amostragem](auditoria/REVISAO-POR-AMOSTRAGEM.md).

## 8. Depois de publicada
- Fato novo sobre o mesmo tema: a análise é atualizada, sem mudar a data de publicação, e a
  mudança entra no histórico de correções do próprio texto.
- Mudança de veredito: sempre registrada, com o veredito anterior e o motivo.
- Veja a [política de correções](POLITICA-DE-CORRECOES.md).
