# Meu Projeto Responsivo


Site estático demonstrativo com foco em responsividade (mobile-first), acessibilidade básica e estrutura limpa.


## O que tem
- `index.html` — página principal (HTML sem frameworks).
- `styles.css` — estilos responsivos (mobile-first + breakpoints para tablet e desktop).


## Como usar
1. Clone ou baixe os arquivos.
2. Abra `index.html` no navegador (não precisa de servidor). Para desenvolvimento, pode usar a extensão "Live Server" no VSCode.


## Principais decisões de design
- **Mobile-first:** os estilos base são para celular; a partir de `@media(min-width:720px)` o layout muda para tablet/desktop.
- **Flex e Grid:** usados para compor o layout com poucas linhas, mais simples de manter.
- **Acessibilidade:** foco visível, aria-expanded no botão do menu e textos com contraste legível.


## Personalização rápida
- Troque as cores em `:root`.
- Substitua o conteúdo da seção `gallery` por imagens reais (usar `<img>` com `alt`).
- Para formulários reais, conecte a `action` do form a um endpoint.
