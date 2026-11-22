# Registro público por análise

Cada análise guarda um registro que qualquer leitor pode conferir. Este documento diz o que já
existe, o que entrou agora e o que fica para depois.

## O que cada análise mostra

| Item | Onde aparece | Situação |
|---|---|---|
| Data de publicação e de atualização | Topo da análise | Já existe |
| Notícia original (resumo e link) | "O que diz a notícia" | Já existe |
| Veredito e confiança | Quadro do veredito | Já existe |
| Linha do tempo das causas, com fonte | "Como chegamos aqui" | Já existe |
| Afirmações avaliadas | "Afirmações verificadas" | Já existe |
| Visões políticas e o que os fatos dizem | "Visões políticas envolvidas" | Já existe |
| Fontes, tipo e linha editorial, com resumo de equilíbrio | "Fontes consultadas" | Já existe |
| Histórico de correções e atualizações | "Correções e atualizações" | Já existe |
| **Cópia arquivada de cada fonte** | Link "cópia arquivada" ao lado da fonte | **Novo (1.0)** |
| **Versão da metodologia** | "Registro desta análise" | **Novo (1.0)**, preenchida sozinha na publicação |
| **Modelo de IA usado** | "Registro desta análise" | **Novo (1.0)**, preenchido pelo agente |
| Marcação ClaimReview (schema.org) | Código da página, para buscadores de checagens | **Novo (1.0)** |
| Lista pública de correções do site | Página /correcoes/ | **Novo (1.0)** |

## Cópias arquivadas: como funciona agora
No momento da pesquisa, o agente pede ao Internet Archive uma cópia da página da fonte
(`https://web.archive.org/save/<url>`) e grava o endereço da cópia no campo `arquivo` da fonte.
Se o arquivamento falhar (o serviço tem limite de pedidos e algumas páginas bloqueiam), a fonte
fica sem cópia e a análise sai assim mesmo: o campo é opcional e o site não trava nada.

Limites: o Internet Archive é um serviço de terceiros; a cópia pode não capturar páginas com
paywall ou carregadas por script. Documentos oficiais (PDF) costumam ser arquivados bem.

## O que fica para depois
| Item | Por que depois | O que precisa |
|---|---|---|
| Cópia própria das fontes (PDF ou HTML guardado no site) | Exige armazenamento e cuidado com direitos autorais (guardar cópia de matéria inteira de terceiros pode não ser permitido) | Decisão do autor e, se for o caso, orientação jurídica |
| Registro imutável de cada versão do texto (histórico público de revisões) | O WordPress guarda revisões, mas não as mostra ao público | Uma página "versões" por análise, ou exportar cada versão para um repositório público |
| Exportação automática das análises para este repositório (um arquivo por análise com fontes e veredito) | Exige uma tarefa agendada com permissão de escrita no repositório | Repositório público criado e uma chave de escrita só para ele |
| Estatísticas públicas de vereditos por tema e por lado político | Com 14 análises (22/11/2026) ainda não há amostra suficiente | Rodar a cada 6 meses junto com a revisão por amostragem |

## Formato dos campos (para quem audita os dados)
Os campos são expostos pela API pública do WordPress em cada post (`/wp-json/wp/v2/posts/<id>`),
com o prefixo `nn_`. O formato completo está na seção 8 de
[regras/REGRAS-DO-AGENTE.md](regras/REGRAS-DO-AGENTE.md).
