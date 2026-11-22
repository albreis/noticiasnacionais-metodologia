# Metodologia do Notícias Nacionais

Este repositório guarda, de forma pública e versionada, **as regras que produzem cada análise
publicada em [noticiasnacionais.com.br](https://noticiasnacionais.com.br)**: como a notícia é
escolhida, como as fontes são cruzadas, como o veredito é dado, como os erros são corrigidos e
quem paga as contas.

O objetivo é simples: qualquer pessoa pode conferir se o método trata todos os lados do mesmo
jeito, e o histórico do Git mostra **quando e por que** cada regra mudou. Nenhuma regra muda em
silêncio.

> O Notícias Nacionais não é um veículo de imprensa e o autor não é jornalista. As análises são
> opiniões pessoais embasadas em informações públicas, com todas as fontes citadas.

## O que tem aqui

| Arquivo | Conteúdo |
|---|---|
| [METODOLOGIA.md](METODOLOGIA.md) | O passo a passo de cada análise, do pedido à publicação |
| [ESCALA-DE-VEREDITO.md](ESCALA-DE-VEREDITO.md) | Os seis vereditos, a confiança e quando cada um é usado |
| [POLITICA-DE-FONTES.md](POLITICA-DE-FONTES.md) | Que fontes valem, em que ordem, e como o equilíbrio é medido |
| [POLITICA-DE-CORRECOES.md](POLITICA-DE-CORRECOES.md) | Como pedir uma correção e como ela fica registrada |
| [CONFLITO-DE-INTERESSE-E-FINANCIAMENTO.md](CONFLITO-DE-INTERESSE-E-FINANCIAMENTO.md) | Quem financia o site e as regras contra influência |
| [USO-DE-IA.md](USO-DE-IA.md) | Como a inteligência artificial é usada e quais instruções ela segue |
| [regras/REGRAS-DO-AGENTE.md](regras/REGRAS-DO-AGENTE.md) | As instruções completas, exatamente como o agente de publicação as recebe |
| [REGISTRO-POR-ANALISE.md](REGISTRO-POR-ANALISE.md) | O que cada análise registra publicamente (fontes, cópias arquivadas, versão do método) |
| [auditoria/](auditoria/) | Modelo de relatório de auditoria externa e o procedimento de revisão por amostragem |
| [CHANGELOG.md](CHANGELOG.md) | Versões da metodologia e o que mudou em cada uma |

## Versão em vigor

**Metodologia 1.0**, em vigor desde 22/11/2026. Cada análise publicada a partir dessa data mostra,
no quadro "Registro desta análise", a versão da metodologia com que foi feita.

## Como uma regra muda

1. A mudança é proposta como um commit (ou pull request) neste repositório, com o motivo.
2. Se muda o resultado das análises (critério de veredito, política de fontes, peso de algo), a
   versão sobe (1.0 → 1.1 para ajustes, 1.x → 2.0 para mudanças de critério) e entra no
   [CHANGELOG.md](CHANGELOG.md).
3. Análises antigas **não são reclassificadas em massa** por causa de uma regra nova. Se uma
   análise antiga for revista, a revisão fica registrada nela, com a data e a versão usada.

## Como contestar

- Erro numa análise: siga a [política de correções](POLITICA-DE-CORRECOES.md).
- Discordância do método: abra uma *issue* neste repositório explicando o problema. Toda issue
  recebe resposta pública, mesmo que seja para explicar por que a regra fica como está.

## O que este repositório não é

- Não é um selo de checagem reconhecido por terceiros. O site não é signatário da IFCN nem de
  outra rede de checagem, e não usa selo que sugira esse aval.
- Não contém senhas, chaves, dados de leitores nem configurações de servidor.
