# Portfólio — victorflll

Site pessoal construído com [Astro](https://astro.build) e hospedado no GitHub Pages.

## Rodando localmente

```bash
npm install
npm run dev
```

Abrir http://localhost:4321

## Build

```bash
npm run build
npm run preview
```

## Deploy

1. Crie o repositório **`victorflll.github.io`** no GitHub (nome exato — é um user site).
2. Faça push deste projeto para `main`.
3. Em **Settings → Pages → Source: GitHub Actions**.

URL final: `https://victorflll.github.io`

## Stack

- Astro (estático)
- TypeScript
- i18n simples PT/EN com `localStorage`
- Repositórios via API pública do GitHub (fallback estático embutido)
- Tema claro/escuro
