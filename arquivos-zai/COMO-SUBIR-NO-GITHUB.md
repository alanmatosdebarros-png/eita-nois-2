# Como subir a v3 no GitHub Pages (2 minutos)

Você só precisa de 1 arquivo: **index.html** (o app inteiro é um arquivo só, 924 KB).

## Passo a passo (pelo navegador, sem instalar nada)

1. Baixe aqui do chat o arquivo `index.html` (dentro da pasta `eita-nois-v3`).
2. Abra seu repositório: `github.com/alanmatosdebarros-png/eita-nois`
3. Clique em **Add file → Upload files**.
4. Arraste o `index.html` novo pra dentro e clique em **Commit changes**.
   - Se pedir, escolha "Commit directly to the main branch".
5. Pronto. O GitHub Pages atualiza sozinho em 1–2 minutos.

## Alternativa (editar direto no GitHub)

1. No repo, clique no `index.html` → ícone de lápis (✏️ Edit).
2. Apague todo o conteúdo, cole o conteúdo do arquivo novo, e faça o commit.
   (O upload por arrastar é mais fácil — o arquivo é grande.)

## Como conferir que a v3 entrou no ar

- Abra o site e aperte **Ctrl + Shift + R** (recarrega ignorando o cache).
- O menu "você" mostra o chip **v3 · motion ao vivo · Creator Room**.
- Nada se perde: chave da API, marcas e projetos continuam salvos no seu navegador.

## ⚠️ Importante — chaves de API

O arquivo do creator-room que você compartilhou continha **chaves de API reais** dentro dele.
Como ele circulou por fora, o ideal é **revogar/trocar essas chaves agora** no painel da
Anthropic (e de qualquer outro serviço que apareça nelas) e usar a chave nova no app.
No app, a chave continua sendo cadastrada só em **Configurações** e fica salva apenas
no seu navegador (localStorage) — nada fica hardcoded no arquivo do site.
