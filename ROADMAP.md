# Os próximos passos do Haku

O foco continua no Android. Esta lista mostra o que ainda falta validar ou desenvolver; não promete datas nem disponibilidade de serviços externos.

## Validar antes da próxima publicação

As melhorias abaixo já estão implementadas nas builds de teste. A pendência é validar o uso real e preparar a publicação, não refazer os recursos.

- Conferir a sincronização AniList + Kitsu na primeira execução, nas seguintes e após reabrir o app, incluindo bibliotecas grandes e conflitos de nota/status.
- Validar downloads com a tela bloqueada, remoção dos recentes e interrupções de rede, preservando os arquivos já salvos.
- Conferir o visual renovado das listas de capítulos e episódios e os controles do leitor em diferentes tamanhos de tela.
- Validar as correções do gateway no ambiente separado de teste antes de atualizar o serviço usado pelas versões públicas.

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
