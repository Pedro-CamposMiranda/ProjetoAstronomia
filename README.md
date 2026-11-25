# Observatório Simples

Site introdutório sobre astronomia, com conteúdos sobre o Sistema Solar, nebulosas e galáxias.

## Arquivos

- `index.html`: página principal.
- `sobre.html`: segunda página do site.
- `style.css`: estilos compartilhados.
- `imagens/`: imagens em WebP e imagem para compartilhamento.
- `favicon.ico` e `favicon.svg`: ícones do site.
- `robots.txt` e `sitemap.xml`: arquivos para mecanismos de busca.
- `SEO.md`: palavras-chave, decisões e espaço para registrar os resultados do Lighthouse.

## Antes de publicar

Procure por `https://SEU-DOMINIO` e substitua pelo endereço público real do site em `index.html`, `sobre.html`, `robots.txt` e `sitemap.xml`. Isso é necessário para que canonical, Open Graph e sitemap apontem para o endereço correto.

## Testes

Valide o JSON-LD de cada página em https://validator.schema.org/ e execute o Lighthouse em modo celular depois da publicação. Registre as notas reais no arquivo `SEO.md`.
