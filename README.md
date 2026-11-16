# Site Maronez & Damaceno Advogados Associados

Landing page estática (HTML + CSS + JS em um arquivo). Não precisa de build.

## 1. Troque o endereço do site (obrigatório)

Os arquivos usam o endereço de exemplo `https://SEU-USUARIO.github.io/SEU-REPOSITORIO`.
Troque pelo endereço real (sem barra no final) em 3 arquivos: `index.html`, `robots.txt` e `sitemap.xml`.

Pelo terminal (Linux/Mac):

    sed -i 's#https://SEU-USUARIO.github.io/SEU-REPOSITORIO#https://seudominio.com.br#g' index.html robots.txt sitemap.xml

Sem terminal: abra cada arquivo no editor do GitHub (lápis) e use localizar e substituir.

## 2. Publicar no GitHub Pages

1. Crie um repositório e envie TODOS os arquivos desta pasta, incluindo `.nojekyll`.
2. Em Settings > Pages, escolha "Deploy from a branch", branch `main`, pasta `/ (root)`.
3. Aguarde 1 a 2 minutos. O site abre em `https://SEU-USUARIO.github.io/SEU-REPOSITORIO/`.
4. Domínio próprio (opcional): crie um arquivo `CNAME` com o domínio e configure o DNS.

## 3. Depois de publicar (SEO)

1. Google Search Console: adicione o site, envie `sitemap.xml` e peça a indexação da página inicial.
2. Google Meu Negócio (Perfil da Empresa): o que mais pesa na busca "advogado trabalhista em Francisco Beltrão". Use o mesmo nome, endereço e telefone do site e coloque o link do site no perfil.
3. Coloque o link do site na bio do Instagram.
4. Teste em https://search.google.com/test/rich-results (dados estruturados) e em https://pagespeed.web.dev.

## 4. Antes de divulgar

- Inclua nome e número de OAB dos advogados no rodapé.
- Confirme o horário de atendimento (hoje diz "horário comercial").
- Para compartilhar no WhatsApp com prévia, o `og-image.jpg` precisa estar no endereço final.

## Arquivos

- `index.html`: a página.
- `404.html`: página de erro.
- `robots.txt` e `sitemap.xml`: orientam o Google.
- `site.webmanifest`, `favicon-48.png`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`: ícones.
- `og-image.jpg`: imagem de prévia (1200x630) ao compartilhar o link.
- `.nojekyll`: evita processamento do Jekyll no GitHub Pages.
