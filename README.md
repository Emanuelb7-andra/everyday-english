# Everyday English

Pratique inglês americano com explicações em português, diálogos, áudios prontos e exercícios de escuta.

- 6 níveis de dificuldade: A1, A2, B1, B2, C1 e C2.
- 24 situações, quatro por nível, com vocabulário e explicações.
- 48 áudios de perguntas e respostas, incluídos no próprio aplicativo.
- Reprodução normal ou lenta.
- Exercícios de escuta com feedback.
- Progresso salvo no navegador, sem conta ou servidor de dados.

Esta é uma trilha inicial de prática. O conteúdo não constitui um curso completo nem certificação de proficiência.

## Abrir o aplicativo

[Acessar Everyday English](https://emanuelb7-andra.github.io/everyday-english/)

Também é possível baixar `index.html` e abri-lo em um navegador. Os áudios são incorporados ao arquivo e não dependem de vozes instaladas no aparelho. Depois de carregar ou baixar o arquivo, os diálogos funcionam sem API de voz.

## Estrutura

O aplicativo completo está em `index.html`: interface, estilos, conteúdo, exercícios e áudios MP3 incorporados. Esse formato evita dependências e caminhos quebrados na hospedagem por subdiretório.

O arquivo contém três blocos de JavaScript: conteúdo das aulas (`LEVELS`, `CONTENT`), mapa de áudio (`AUDIO_FILES`) e comportamento do aplicativo. Ao alterar uma pergunta ou resposta, atualize também o áudio correspondente.

## GitHub Pages

A publicação usa **Settings → Pages → Deploy from a branch → main → /(root)**. Alterações enviadas à branch `main` atualizam o aplicativo após a implantação do GitHub Pages.

## Privacidade

O progresso fica no armazenamento local do navegador. Não há sincronização entre dispositivos, envio de progresso, coleta de voz ou autenticação dentro do aplicativo. O site não solicita chaves de API.
