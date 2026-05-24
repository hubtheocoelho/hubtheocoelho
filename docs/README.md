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

## Variáveis de ambiente

| Variável        | Descrição                                                  |
| --------------- | ---------------------------------------------------------- |
| `VITE_SITE_URL` | URL canônica em produção (ex: `https://hubtheocoelho.com`) |

Valores locais em `.env` (gitignored). Em produção, definidas no painel do Netlify. CI lê de GitHub Actions vars. `.env.example` documenta as vars esperadas.

<details>
<summary><b>EN</b></summary>

| Variable        | Description                                                   |
| --------------- | ------------------------------------------------------------- |
| `VITE_SITE_URL` | canonical production URL (e.g., `https://hubtheocoelho.com`)  |

Local values in `.env` (gitignored). In production, set in the Netlify dashboard. CI reads from GitHub Actions vars. `.env.example` documents the expected variables.

</details>

## CI

`.github/workflows/ci.yml` roda em PRs e pushes pra `staging` e `main`:

- `typecheck` (`tsc --noEmit`)
- `build` (`vite build`)

Falha em qualquer um bloqueia o merge.

<details>
<summary><b>EN</b></summary>

`.github/workflows/ci.yml` runs on PRs and pushes to `staging` and `main`:

- `typecheck` (`tsc --noEmit`)
- `build` (`vite build`)

Failure on either blocks merge.

</details>

## Deploy

[Netlify](https://www.netlify.com/), build declarado em `netlify.toml`. Auto-deploy de `main`. Headers de segurança (HSTS, CSP, X-Frame-Options, Referrer-Policy, Permissions-Policy) aplicados a todas as rotas.

<details>
<summary><b>EN</b></summary>

[Netlify](https://www.netlify.com/), build declared in `netlify.toml`. Auto-deploy from `main`. Security headers (HSTS, CSP, X-Frame-Options, Referrer-Policy, Permissions-Policy) applied to all routes.

</details>

## Estrutura

```
hubtheocoelho/
├── .env.example
├── .github/
│   └── workflows/
│       ├── ci.yml
│       └── update-readme.yml
├── .mise.toml
├── docs/
│   └── README.md
├── images/
├── index.html
├── netlify.toml
├── package.json
├── README.md
├── src/
│   ├── main.ts
│   └── styles.css
├── tsconfig.json
└── vite.config.ts
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
