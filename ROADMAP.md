# Os próximos passos do Haku

O foco continua no Android. Esta lista mostra o que ainda falta validar ou desenvolver; não promete datas nem disponibilidade de serviços externos.

## Acompanhar após a beta 5

A busca e a sincronização AniList + Kitsu, a exclusão de downloads, os ajustes do leitor e o visual das listas de capítulos/episódios foram entregues na beta 5. As correções do gateway também foram publicadas.

- Medir a sincronização automática com bibliotecas grandes e acompanhar conflitos de nota/status em uso real.
- Acompanhar downloads em diferentes aparelhos, com bloqueio de tela, encerramento do processo e interrupções de rede.
- Investigar novos relatos usando os registros de diagnóstico do app e do gateway.

## MangaDex e lançamentos

Integração planejada, ainda não implementada:

1. Unir MangaDex, AniList e Kitsu na busca e na ficha da obra, usando correspondências verificadas e evitando duplicatas. Títulos parecidos, por si só, não serão suficientes para unir obras.
2. Ampliar a área de lançamentos com capítulos novos das obras acompanhadas, indicando idioma e fonte e diferenciando traduções do mesmo capítulo.
3. Integrar as obras disponíveis ao leitor e aos downloads do Haku, com a mesma interface e progresso local. Tratar capítulos extras, decimais e numeração por volume.
4. Avaliar a conexão da conta MangaDex e a sincronização com as demais bibliotecas. Autenticação e campos compatíveis precisam ser confirmados na API antes de definir o alcance da integração. Para dados compatíveis, manter o maior progresso e pedir uma escolha quando nota ou status entrarem em conflito.

A implementação começa pelo catálogo, pelos lançamentos e pela leitura. A sincronização entre as três contas vem depois da validação técnica, respeitando os limites e as condições de cada serviço.

## Outras pendências

- Medir e melhorar a velocidade dos downloads quando houver gargalos identificados, respeitando os limites das fontes.
- Ampliar a cobertura dos avisos e recursos de abertura/encerramento quando existirem dados compatíveis.
- Revisar idiomas, interface e modelos de tradução antes de ampliar a experiência oferecida em português.
- Concluir e testar a versão para PC antes de publicar instaladores ou releases dessa plataforma.

O código permanece privado; este repositório é dedicado à distribuição do aplicativo. O roadmap pode mudar com os testes e a disponibilidade das integrações. Créditos e licenças de terceiros serão mantidos.
