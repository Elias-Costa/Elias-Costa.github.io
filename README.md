# Portfólio — Elias Rodrigues

Site pessoal

**[elias-costa.github.io](https://elias-costa.github.io/)**

Portfólio de Engenharia de Software: projetos, experiência, pesquisa e contato.

## Projetos em destaque

- **[ECRX Caixa](https://caixa.ecrxtecnologia.com.br/)** — sistema de caixa e vendas em Java e Spring, com PWA offline, sincronização e operação própria, incluindo backups cifrados no Amazon S3 e restauração ensaiada.
- **Fichinhas** — controle de fiado e estoque para uma revendedora, com uso real, persistência local e sincronização.
- **[SiteHealth](https://site-health-ten.vercel.app)** — SaaS de monitoramento técnico de sites, em pré-lançamento.

Os detalhes de engenharia ficam em blocos expansíveis. As descrições distinguem recursos em uso, implantação e validações pendentes, e as contagens de testes vêm da execução das suítes de cada projeto.

## Stack

HTML, CSS e JavaScript puro. Sem framework, sem build step, sem dependências. É um site estático de página única, e o GitHub Pages serve os arquivos direto do repositório.

- `index.html` — marcação; página única com uma âncora por seção
- `css/style.css` — todo o estilo, com design tokens em `:root`
- `js/main.js` — revelação das seções por `IntersectionObserver`, respeitando `prefers-reduced-motion`
- `favicon.svg` — favicon
- `og-image.png` — imagem 1200×630 do card de compartilhamento (`og:image`)
- `og-image.svg` — fonte vetorial do card; o PNG acompanha sua versão renderizada
- `artigo-erbase-2025.pdf` — artigo publicado na ERBASE 2025, servido pelo site
