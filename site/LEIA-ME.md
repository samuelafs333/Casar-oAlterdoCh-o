# Casarão Alter do Chão — Site pronto para publicar

## Estrutura
```
site/
├── index.html      → página principal
├── favicon.svg     → ícone da aba do navegador
├── robots.txt      → instruções para o Google
├── sitemap.xml     → mapa do site
└── images/         → 10 fotos da casa
```

## Como publicar (grátis)
**Netlify Drop:** acesse https://app.netlify.com/drop e arraste a pasta `site` inteira.

**Vercel / GitHub Pages / Hostinger:** envie o conteúdo da pasta `site` para a raiz da hospedagem.

## Depois de publicar
1. Troque `www.casaraoalterdochao.com.br` em `robots.txt` e `sitemap.xml` pelo domínio real.
2. Cadastre o site no Google Search Console e envie o `sitemap.xml`.

## Trocar ou adicionar fotos
Coloque a foto em `images/` e edite a lista `polaroidItems` no final do `index.html`.
