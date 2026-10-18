# cruzvermelhaitaguai.org

Cópia do site publicado na Hostinger (conta `u448697994`, pasta
`domains/cruzvermelhaitaguai.org/public_html`). `index.html` e `assets/` são os
mesmos arquivos da raiz do domínio; a versão anterior continua no servidor em
`public_html/paginaantiga/`.

## Verificação do domínio no Facebook (BM)

O `<head>` do `index.html` carrega a metatag `facebook-domain-verification`
pedida pelo Gerenciador de Negócios. Não remova: o Meta volta a conferir o
domínio periodicamente e a verificação cai se ela sumir. Ela precisa ficar no
HTML estático, fora de qualquer JavaScript.

## Privacidade e cookies (LGPD)

- `privacidade/index.html` é a Política de Privacidade (link do rodapé, `/privacidade/`), com a
  tabela de cookies em `#cookies`.
- `consentimento.js` é o aviso de cookies, no mesmo desenho do site do Rio: três botões do mesmo
  tamanho, estatística e marketing desligados até a pessoa ligar. A escolha fica no cookie
  `cvbi_consentimento` (12 meses, só neste domínio). Qualquer elemento com `data-cookies` reabre as
  preferências.
- O bloco de medição no `<head>` das duas páginas só baixa o Google Analytics (`G-S6RZHLJJX0`) e o
  Pixel da Meta (`2224500131617302`) depois do "sim". Não volte a pôr o `<noscript>` com a imagem do
  Pixel (dispara PageView sem consentimento). Ferramenta nova de medição entra atrás do
  consentimento e na tabela de cookies da política.

## Publicar

Enviar os arquivos alterados para `public_html` pelo Gerenciador de Arquivos
do hPanel (ou pela API de arquivos da Hostinger).
