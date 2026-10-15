# Dra. Gabrielly Mazochin — site de apresentação

Site de uma página (HTML, CSS e JavaScript puros, sem bibliotecas) da cirurgiã-dentista **Dra. Gabrielly Mazochin Ferreira**, de Campo Grande – MS.

Publicado em: https://ocarlaum.github.io/dra-gabrielly-mazochin/

## Estrutura

| Arquivo | Função |
|---|---|
| `index.html` | Página inteira (estilos e scripts embutidos) |
| `favicon.ico`, `favicon-96x96.png`, `assets/favicon.svg`, `apple-touch-icon.png` | Ícones do site |
| `site.webmanifest`, `web-app-manifest-*.png` | Ícones e dados para instalar o site como app |
| `assets/gabrielly-mazochin.webp`, `assets/gabrielly-mazochin-480.webp` | Foto principal (900 px e 480 px para telas pequenas) |
| `assets/og-image.jpg` | Imagem de compartilhamento (1200×630) |
| `robots.txt`, `sitemap.xml` | Rastreamento para buscadores |
| `google*.html` | Verificação de propriedade no Google Search Console (não apagar) |

## Recursos

- Modo claro e escuro (botão no topo; a escolha fica salva no navegador)
- Layout responsivo para celular, tablet e computador
- FAQ animado e formulário que abre uma conversa no WhatsApp
- SEO: title e description, canonical, Open Graph, Twitter Cards, dados estruturados JSON-LD (Dentist, Person, FAQPage)

## Como editar

1. Edite o `index.html` (textos, links e dados de contato ficam no próprio arquivo).
2. Se o número de WhatsApp mudar, atualize também os links `wa.me` e o JSON-LD.
3. Atualize o `lastmod` do `sitemap.xml` a cada mudança de conteúdo.
4. Faça o commit na branch `main`; o GitHub Pages atualiza sozinho em alguns minutos.

## Se mudar o endereço do site

Ao migrar para um domínio próprio, troque o endereço antigo no `canonical`, nas tags `og:`/`twitter:`, no JSON-LD, no `robots.txt` e no `sitemap.xml`. Com o site na raiz do domínio, os caminhos que começam com `/` (ícones e `site.webmanifest`) passam a funcionar.

## Observações

- O conteúdo segue as normas de publicidade odontológica do CFO/CRO: sem preços, promoções ou depoimentos, e sem o termo "especialista" antes do registro da especialidade.
- Os dados de contato publicados são apenas os profissionais (consultório e WhatsApp).
