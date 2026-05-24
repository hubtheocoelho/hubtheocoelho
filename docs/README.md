# hubtheocoelho.com

Código-fonte do site pessoal de [Theo Coêlho](https://github.com/hubtheocoelho). Repositório dual-purpose: serve como [GitHub profile README](../README.md) e como source do site.

> **Status:** Fase 0 — fundação.

## Stack

- **Build:** [Vite](https://vitejs.dev/) + [TypeScript](https://www.typescriptlang.org/) (strict, Node 20 LTS)
- **Estilo:** CSS puro com custom properties
- **Commits:** [QAC v1.0](https://github.com/hubtheocoelho/qac-spec)

## Scripts

```bash
npm run dev         # servidor de desenvolvimento
npm run build       # compila e gera dist/
npm run preview     # serve o build
npm run typecheck   # valida tipos sem emitir
```

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

---

<details>
<summary><b>Read in English</b></summary>
<br />

# hubtheocoelho.com

Source code for [Theo Coêlho](https://github.com/hubtheocoelho)'s personal site. Dual-purpose repo: serves as [GitHub profile README](../README.md) and as the website source.

> **Status:** Phase 0 — foundation.

## Stack

- **Build:** [Vite](https://vitejs.dev/) + [TypeScript](https://www.typescriptlang.org/) (strict, Node 20 LTS)
- **Style:** vanilla CSS with custom properties
- **Commits:** [QAC v1.0](https://github.com/hubtheocoelho/qac-spec)

## Scripts

```bash
npm run dev         # dev server
npm run build       # compile and build dist/
npm run preview     # serve the build
npm run typecheck   # validate types without emitting
```

## Branches

- `main` — production
- `staging` — integration
- `feat/*`, `fix/*`, `chore/*` — work branches

PRs flow: feature → staging → main.

</details>
