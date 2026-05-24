<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3000&pause=1000&color=8B949E&center=true&vCenter=true&width=620&lines=qualifying+commits+for+the+agent+era;designing+protocols+for+autonomous+systems;hubtheocoelho.com+%E2%80%94+em+constru%C3%A7%C3%A3o)](https://github.com/hubtheocoelho)

# Theo Coêlho

ai engineer · spec author · open-source · [hubtheocoelho.com](https://hubtheocoelho.com)


<img src="https://img.shields.io/badge/role-AI%20Engineer-blue?style=flat-square" alt="role" />
<img src="https://img.shields.io/github/followers/hubtheocoelho?label=Followers&style=flat-square" alt="followers" />

</div>


<img src="https://img.shields.io/badge/role-AI%20Engineer-blue?style=flat-square" alt="role" />
<img src="https://img.shields.io/github/followers/hubtheocoelho?label=Followers&style=flat-square" alt="followers" />
<img src="https://img.shields.io/badge/QAC-spec-verified-brightgreen?style=flat-square" alt="qac" />

</div>
---

Projeto e construo infraestrutura para agentes de IA — protocolos, orquestração e ferramental que permitem que sistemas autônomos escrevam código, publiquem commits e colaborem sem perder rastreabilidade.

**Foco atual**

- **[QAC — Qualified Agent Commits](https://github.com/hubtheocoelho/qac-spec)** — especificação de mensagem de commit que qualifica cada commit com um schema fixo de quatro trailers (`Agent`, `Mode`, `What`, `Why`). Autorada para tornar repositórios produzidos por agentes interoperáveis entre times, ferramentas e modelos.
- **[hubtheocoelho.com](https://hubtheocoelho.com)** — site pessoal bilíngue, em construção. Concebido como case-study técnico da spec QAC.
- **Pesquisa open-source** — `joaju` (orquestração de agentes), `tekoha` (indexação semântica), `yande` (benchmark de LLMs), `nexus-fs`.

---

## Em destaque

<a href="https://github.com/hubtheocoelho/qac-spec">
  <img src="https://img.shields.io/github/stars/hubtheocoelho/qac-spec?style=for-the-badge&logo=github&labelColor=0d1117&color=30363d" alt="stars" />
  <img src="https://img.shields.io/github/forks/hubtheocoelho/qac-spec?style=for-the-badge&logo=github&labelColor=0d1117&color=30363d" alt="forks" />
  <img src="https://img.shields.io/github/license/hubtheocoelho/qac-spec?style=for-the-badge&labelColor=0d1117&color=30363d" alt="license" />
</a>

> QAC padroniza o que outras equipes deixam ad-hoc: as chaves dos trailers, sua ordem, e os valores permitidos do `Mode`. Qualquer repositório QAC-compliant torna-se consultável com os mesmos padrões — independentemente do time, ferramenta ou agente que produziu o commit.
>
> Quatro trailers. Legíveis por máquinas. Legíveis por humanos. Interoperáveis.

---

## Últimas issues abertas

<!-- ISSUES:START -->
- [`kirodotdev/Kiro#7803`](https://github.com/kirodotdev/Kiro/issues/7803) — [CLI] User-initiated tool use cancellation treated as recoverable failure - agent retries persistently across topic changes `open`
- [`kirodotdev/Kiro#7792`](https://github.com/kirodotdev/Kiro/issues/7792) — [CLI] System prompt <default_to_action> directive overrides agent prompt constraints - no precedence hierarchy between prompt layers `open`
- [`kirodotdev/Kiro#7758`](https://github.com/kirodotdev/Kiro/issues/7758) — Propagate power steering context to subagents - subagents should receive POWER.md and steering files from active powers `open`
- [`kirodotdev/Kiro#7757`](https://github.com/kirodotdev/Kiro/issues/7757) — On-demand power activation - allow agents and subagents to invoke powers explicitly `open`
- [`kirodotdev/Kiro#7756`](https://github.com/kirodotdev/Kiro/issues/7756) — Inter-power communication - enable data passing and composition between active powers `open`
- [`kirodotdev/Kiro#7755`](https://github.com/kirodotdev/Kiro/issues/7755) — Hooks should trigger in subagents - governance must be uniform across all agent types `open`
- [`kirodotdev/Kiro#7754`](https://github.com/kirodotdev/Kiro/issues/7754) — Granular tool classification in powers - declare read/write permissions for MCP tools `open`
- [`kirodotdev/Kiro#7753`](https://github.com/kirodotdev/Kiro/issues/7753) — Explicit parallel activation of multiple powers - enable concurrent power usage by invocation `open`
- [`kirodotdev/Kiro#7751`](https://github.com/kirodotdev/Kiro/issues/7751) — Context-aware power activation - semantic intent matching beyond literal keywords `open`
- [`kirodotdev/Kiro#7511`](https://github.com/kirodotdev/Kiro/issues/7511) — Agent start instruction - agent-initiated response on session start `open`
<!-- ISSUES:END -->

<sub>atualizado automaticamente a cada 6h — ver <a href=".github/workflows/update-readme.yml"><code>update-readme.yml</code></a></sub>

---

## Stack

<div align="center">

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" width="40" height="40" alt="Python" title="Python" />
&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" width="40" height="40" alt="TypeScript" title="TypeScript" />
&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" width="40" height="40" alt="JavaScript" title="JavaScript" />
&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nodejs/nodejs-original.svg" width="40" height="40" alt="Node.js" title="Node.js" />
&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" width="40" height="40" alt="Docker" title="Docker" />
&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linux/linux-original.svg" width="40" height="40" alt="Linux" title="Linux" />

</div>

---
<details>
<summary><b>read in english</b></summary>

<br>

```bash
$ whoami
theo coêlho — ai engineer
```

I design and build infrastructure for AI agents — protocols, orchestration, and tooling that let autonomous systems write code, ship commits, and collaborate without losing traceability.

**Currently working on**

- **[QAC — Qualified Agent Commits](https://github.com/hubtheocoelho/qac-spec)** — a commit-message specification that qualifies each commit with a fixed schema of four trailers (`Agent`, `Mode`, `What`, `Why`). Authored to make agent-produced repositories interoperable across teams, tools, and models.
- **[hubtheocoelho.com](https://hubtheocoelho.com)** — bilingual personal site, under construction. Conceived as the technical case-study for QAC.
- **Open-source research** — `joaju` (agent orchestration), `tekoha` (semantic indexing), `yande` (LLM benchmarking), `nexus-fs`.

### Featured — qac-spec

> QAC standardizes what other teams leave ad-hoc: the trailer keys, their order, and the allowed values for `Mode`. Any QAC-compliant repository becomes queryable with the same patterns — regardless of the team, tool, or agent that produced the commit.
>
> Four trailers. Machine-readable. Human-readable. Interoperable.

</details>

---

<div align="center">
  <sub><code>commits qualificados sob <a href="https://github.com/hubtheocoelho/qac-spec">QAC</a></code></sub>
</div>
