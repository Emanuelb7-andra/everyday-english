# Everyday English

Pratique inglês com explicações em português, diálogos, áudio normal e lento, vocabulário e exercícios de escuta.

**624 práticas: 104 por nível de A1 a C2.**.

[Abrir aplicativo](https://emanuelb7-andra.github.io/everyday-english/)

## Como estudar

- Escolha um dos seis níveis e uma prática.
- Ouça a pergunta e a resposta, em velocidade normal ou lenta.
- Oculte as traduções para treinar a compreensão.
- Use a busca por tema, palavra ou tradução para encontrar uma prática.
- Navegue pela lista em blocos de dez ou digite um número de 1 a 104.
- No modo **Treinar escuta**, cada sessão sorteia dez perguntas do nível.

Os novos grupos apresentam estruturas de comunicação em cinco contextos distintos. A dificuldade aumenta de situações cotidianas para argumentação, interpretação e precisão lexical. A organização por níveis é uma referência de dificuldade, não uma certificação de proficiência ou promessa de curso completo.

## Áudio

São 1.248 áudios, uma pergunta e uma resposta por prática, com vozes sintéticas de inglês dos Estados Unidos. Não dependem de vozes instaladas no aparelho nem de uma API de voz durante o estudo.

Para manter o carregamento inicial leve, os áudios são carregados em blocos de dez práticas. O primeiro acesso a cada bloco precisa de conexão. Depois, os áudios desse bloco permanecem disponíveis na página enquanto ela estiver aberta. Se o navegador bloquear a reprodução, toque no controle de áudio que aparece abaixo do diálogo.

## Progresso e privacidade

O progresso fica no armazenamento local do navegador. Os identificadores das quatro práticas originais e a chave de armazenamento foram preservados. As marcações anteriores continuam valendo: por exemplo, 3/4 passa a aparecer como 3/104 no mesmo navegador e endereço.

Não há login, sincronização entre aparelhos, coleta de voz nem envio de progresso a servidor. Apagar os dados do navegador também pode apagar as marcações locais.

## Estrutura do repositório

- `index.html`: interface, estilos, conteúdo das 624 práticas, exercícios, navegação e carregador de áudio.
- `audio-A1-0.js` a `audio-C2-10.js`: 66 bancos de áudio MP3, separados por nível e blocos de dez práticas.
- `.nojekyll`: publicação estática direta.

Ao alterar uma pergunta ou resposta em inglês, atualize também seu áudio no banco do nível. O app precisa de `index.html` e dos 66 bancos de áudio na mesma pasta; `index.html` sozinho não inclui os novos bancos de áudio.

## GitHub Pages

Publicação configurada em **Settings → Pages → Deploy from a branch → main → /(root)**. Alterações na branch `main` são publicadas após a implantação do GitHub Pages.
