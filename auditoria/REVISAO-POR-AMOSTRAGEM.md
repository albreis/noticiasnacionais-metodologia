# Revisão por amostragem (conselho de revisão)

Enquanto não há auditoria externa contratada, a revisão por amostragem é o controle que pode ser
feito já, a baixo custo.

## Quem revisa
Um grupo de 2 a 5 pessoas voluntárias, de preferências políticas diferentes entre si, sem
vínculo financeiro com o site.

**Situação em 22/11/2026: membros ainda não definidos.** Até lá, a revisão é feita pelo autor e
registrada como "revisão interna", sem valor de revisão independente.

Familiares e sócios do autor podem participar, mas o vínculo é declarado no relatório e a
participação deles não conta como revisão independente: para isso, é preciso pelo menos um
membro sem vínculo pessoal ou financeiro com o autor.

Os nomes são publicados aqui, salvo quem pedir anonimato; nesse caso o relatório diz quantos
membros anônimos participaram.

## Como funciona
1. **A cada mês** (ou a cada 30 análises, o que vier primeiro), sorteiam-se 5 análises
   publicadas no período, com um sorteio registrado (lista de IDs + semente).
2. Cada revisor confere as análises sorteadas usando a tabela da seção 3 do
   [modelo de relatório](MODELO-DE-RELATORIO.md).
3. Divergências de veredito são discutidas; se a maioria concordar que há erro, a análise é
   corrigida pela [política de correções](../POLITICA-DE-CORRECOES.md), citando a revisão.
4. O resultado (análises revisadas, problemas encontrados, o que foi corrigido) é publicado
   neste repositório em `auditoria/revisoes/AAAA-MM.md`.

## A cada 6 meses
Comparar o conjunto: vereditos por lado político das afirmações, temas mais frequentes e tempo de
resposta às correções. Se aparecer um desequilíbrio, a explicação (ou a correção de rumo) entra no
relatório e, se mudar regra, no [CHANGELOG.md](../CHANGELOG.md).
