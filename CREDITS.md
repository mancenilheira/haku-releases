# Quem torna o Haku possível

Obrigado às pessoas que organizam informações, constroem ferramentas e dão vida às histórias que acompanhamos. O Haku reúne trabalhos de muitas comunidades; este documento registra como cada uma participa.

## Biblioteca e descoberta

| Projeto | Uso no Haku |
|---|---|
| [AniList](https://anilist.co) · [API](https://docs.anilist.co/) | Obras, personagens, capas, perfis, listas, avaliações e sincronização de progresso. É a base da biblioteca. |
| [trace.moe](https://trace.moe) · soruly | Busca de anime a partir de uma cena enviada com confirmação. [Termos da API](https://soruly.github.io/trace.moe-api/#/terms). |
| [AniSkip](https://github.com/aniskip/aniskip-api) | Intervalos comunitários de aberturas e encerramentos, quando há correspondência compatível. |
| [MangaDex](https://mangadex.org) | Metadados do feed de capítulos recentes e links para a origem. |
| [Crunchyroll News](https://www.crunchyroll.com/news) e [Anime News Network](https://www.animenewsnetwork.com) | Notícias e links para os artigos originais. |

## Leitura, vídeo e tradução

| Projeto | Uso e avisos |
|---|---|
| [GoAnime](https://github.com/alvarorichard/GoAnime), alvarorichard e colaboradores | Base para uma das integrações de anime. [Avisos preservados](licenses/GoAnime.txt). |
| [Yuzono anime-extensions](https://github.com/yuzono/anime-extensions) | Integração da fonte Animes Digital. [Licença e alterações](licenses/Yuzono.txt). |
| [AndroidX Media3 / ExoPlayer](https://github.com/androidx/media) | Player nativo Android. [Apache 2.0](licenses/Media3.txt). |
| [Foxlet Translate](https://github.com/yinvoke/foxlet-translate), yinvoke | Tradução local no Android com o runtime 0.5.0. [Licenças e componentes](licenses/Foxlet.txt). |
| [Mozilla / Firefox Translations](https://github.com/mozilla/firefox-translations), [Bergamot](https://github.com/browsermt/bergamot-translator) e [Marian](https://github.com/marian-nmt/marian) | Tecnologia e modelos usados pela tradução Foxlet. Os avisos aplicáveis estão no arquivo Foxlet. |
| [Helsinki-NLP / OPUS](https://opus.nlpl.eu), [Xenova](https://huggingface.co/Xenova/opus-mt-en-ROMANCE), [ONNX Runtime](https://onnxruntime.ai) | Modelos e execução do tradutor desktop, com tokenização SentencePiece. |

As fontes de leitura e vídeo são serviços de terceiros. Sua disponibilidade varia, e a integração não transfere direitos sobre o conteúdo. Os créditos de autores, editoras, artistas e tradutores pertencem a essas pessoas e organizações.

## Base técnica

[Flutter](https://flutter.dev), [Dart](https://dart.dev), [Supabase](https://supabase.com), [PostgreSQL](https://www.postgresql.org), Android e suas bibliotecas, além dos mantenedores de Hive, GraphQL Flutter, Provider, Share Plus, flutter_inappwebview e os demais pacotes incluídos no aplicativo.

A lista de licenças no aplicativo inclui os avisos dos pacotes Flutter e dos componentes adicionais. Os arquivos de `licenses/` preservam os avisos adicionais usados nesta versão.

