# A Hora da Paz: página de vendas

Página estática (HTML + CSS inline + 1 script de ~15 linhas). Não precisa de build.

## Arquivos
- `index.html`: a página inteira (copy, estilos, script da barra fixa mobile).
- `assets/img/`: capa e páginas reais do eBook (WebP), foto da família, imagem de compartilhamento com a foto da família (`og-familia.jpg`, 1200x630).
- `assets/fonts/`: Cormorant Garamond e Nunito Sans (latin), hospedadas junto com a página.
- `favicon.svg`, `favicon-32.png`, `apple-touch-icon.png`.

## Checkout (não alterar sem necessidade)
`https://pay.hotmart.com/T104840650A?off=4oj6ord3&hotfeature=51`
Está em 4 botões: topo, oferta, final e barra fixa mobile.

## Dados confirmados no painel da Hotmart
- Preço base: R$ 29,90 (oferta `4oj6ord3`); cartão em até 4x com acréscimo, Pix, boleto, PayPal.
- Prazo para reembolso: 7 dias.

## Publicação
Hospedada no GitHub Pages (repositório `familiasouza2025/a-hora-da-paz`, branch `main`): https://familiasouza2025.github.io/a-hora-da-paz/
Se o endereço mudar, atualize canonical, og:url, og:image, twitter:image e o JSON-LD no `<head>`.

## Depoimentos
Não há depoimentos reais ainda. Existe um bloco comentado em `index.html` (procure por "DEPOIMENTOS"), com estilos já prontos. Ative somente com textos reais e autorizados.

## Testar localmente
Use qualquer servidor estático na pasta, por exemplo `npx serve .`.
