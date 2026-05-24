# hubtheocoelho.com

Código-fonte do site pessoal de [Theo Coêlho](https://github.com/hubtheocoelho). Repositório dual-purpose: serve como [GitHub profile README](../README.md) e como source do site.

<details>
<summary><b>EN</b></summary>

Source code for [Theo Coêlho](https://github.com/hubtheocoelho)'s personal site. Dual-purpose repo: serves as [GitHub profile README](../README.md) and as the website source.

</details>

> **Status:** Fase 0 — fundação.

<details>
<summary><b>EN</b></summary>

> **Status:** Phase 0 — foundation.

</details>

## Stack

- **Build:** [Vite](https://vitejs.dev/) + [TypeScript](https://www.typescriptlang.org/) (strict, Node 24 LTS)
- **Estilo:** CSS puro com custom properties
- **Commits:** [QAC v1.0](https://github.com/hubtheocoelho/qac-spec)

<details>
<summary><b>EN</b></summary>

- **Build:** [Vite](https://vitejs.dev/) + [TypeScript](https://www.typescriptlang.org/) (strict, Node 24 LTS)
- **Style:** vanilla CSS with custom properties
- **Commits:** [QAC v1.0](https://github.com/hubtheocoelho/qac-spec)

</details>

## Scripts

```bash
npm run dev         # servidor de desenvolvimento
npm run build       # compila e gera dist/
npm run preview     # serve o build
npm run typecheck   # valida tipos sem emitir
```

<details>
<summary><b>EN</b></summary>

```bash
npm run dev         # dev server
npm run build       # compile and build dist/
npm run preview     # serve the build
npm run typecheck   # validate types without emitting
```

</details>

## Estrutura

```
hubtheocoelho/
├── index.html
├── src/
│   ├── main.ts
│   └── styles.css
├── package.json
├── tsconfig.json
├── vite.config.ts
├── README.md
├── docs/README.md
└── images/
```

## Branches

- `main` — produção
- `staging` — integração
- `feat/*`, `fix/*`, `chore/*` — branches de trabalho

PRs seguem: feature → staging → main.

<details>
<summary><b>EN</b></summary>

- `main` — production
- `staging` — integration
- `feat/*`, `fix/*`, `chore/*` — work branches

PRs flow: feature → staging → main.

</details>
