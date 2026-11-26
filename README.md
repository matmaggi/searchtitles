# SearchTitles

**Buscador de legendas para contexto: encontre termos em vários arquivos de uma vez e veja como foram traduzidos.**

O SearchTitles pesquisa palavras e frases em várias legendas ao mesmo tempo, mostra as falas ao redor e, se você carregar a tradução, exibe a versão traduzida da mesma fala. É útil para manter a consistência em séries e conferir como um termo foi usado antes.

## Formatos aceitos
SRT, DFXP, PXTT, TTML e TTAL.

## Funcionalidades
- **Vários arquivos de uma vez:** adicione quantos quiser, arrastando ou clicando na área de arquivos, e remova individualmente ou todos.
- **Pareamento automático:** reconhece pelo nome qual arquivo é o original e qual é a tradução do mesmo episódio e mostra os dois lado a lado.
- **Dois modos de busca:**
  - *Tempo real:* a busca começa sozinha a partir de 3 caracteres.
  - *Lista de termos:* adicione vários termos (Enter), cada um buscado de forma independente.
- **Busca normalizada:** por padrão, ignora acentos, maiúsculas e minúsculas e o tipo de aspas e apóstrofos (“nao” encontra “não”, “don't” encontra “don’t”).
- **Busca exata (opcional):** diferencia acentos, aspas e maiúsculas.
- **Palavra ou frase inteira** ou parte de palavra.
- **Ignora a formatação:** encontra o termo mesmo quando ele está dividido por tags (itálico etc.), sem alterar o texto original.
- **Leitura completa dos formatos:** itálico e negrito definidos em estilos de DFXP/TTML, estilos sobrepostos em TTAL, timecode drop-frame (29,97) e legendas SRT com linha em branco no meio do texto.
- **Resultados por arquivo, em ordem natural dos episódios** (E2 antes de E10), com o termo destacado. Uma legenda que contém vários termos da lista aparece uma vez só, com cada termo destacado na sua cor. Tem paginação ("Mostrar mais") e opção de mostrar os arquivos sem correspondência.
- **Contexto:** mostra as 3 legendas anteriores e as 3 posteriores, com botões para ver mais.
- **Tradução lado a lado:** carregue a legenda traduzida e veja a fala correspondente, pareada pelo tempo.
- **Mostrar tags originais** nos resultados e no contexto.
- Limpar resultados ou resetar tudo.

## Privacidade
Todos os arquivos são analisados no seu computador. Nenhuma legenda é enviada para nenhum servidor.

## Créditos
Adaptação da ferramenta Subtricks, desenvolvida por Pedro Pereira.
