# Transição para o Claude Code — Plano do Curso

**courseId:** `claude-code`
**Emoji:** 🤖
**Formato:** INEMA v2 (dark premium + camada de aprendizagem)
**Base:** infográfico "Track Your Transition Into Claude Code" (12 semanas, 234 tasks)

---

## Estrutura: 5 Trilhas × 6 Módulos = 30 Módulos = 180 Tópicos

### Trilha 1: CLI e Configuração (Emerald) — Semanas 1-2

| Módulo | Título | Tópicos (6) | Tipo |
|--------|--------|-------------|------|
| 1.1 | Instalação e Primeiro Comando | Instalação (npm/brew), primeiro `claude`, modos interativo/one-shot, navegando o help, flags essenciais, diagnóstico de problemas | Prático |
| 1.2 | Navegando o CLI como um Pro | Atalhos de teclado, slash commands, modelo e contexto, sessões e /resume, leitura de imagens, output formatado | Prático |
| 1.3 | CLAUDE.md — O Cérebro do Projeto | O que é, hierarquia (global/projeto/pasta), sintaxe e convenções, instruções eficazes, exemplos reais, manutenção | Fundamento |
| 1.4 | Configuração Avançada | settings.json, .claudeignore, permissões e allowedTools, variáveis de ambiente, perfis de projeto, model override | Prático |
| 1.5 | Memory e Contexto Persistente | Como a memória funciona, /memory, context window, compaction, session handoff, checkpoint strategies | Fundamento |
| 1.6 | Seu Workflow Pessoal | Aliases de shell, scripts wrapper, integração com editor (VS Code), tmux/screen, dotfiles, daily driver setup | Prático |

### Trilha 2: Plan e Loop Modes (Blue) — Semanas 3-4

| Módulo | Título | Tópicos (6) | Tipo |
|--------|--------|-------------|------|
| 2.1 | Plan Mode — Pense Antes de Codar | O que é plan mode, quando usar, anatomia de um plano, approval flow, iterando no plano, anti-patterns | Fundamento |
| 2.2 | Planos que Funcionam | Plano de feature, plano de refactor, plano de bug fix, decomposição, dependências, estimativa de esforço | Prático |
| 2.3 | Loop Mode — Automação Iterativa | O que é, quando usar, loop vs interativo, guardas de segurança, monitoramento, parar no ponto certo | Fundamento |
| 2.4 | Patterns de Loop na Prática | Loop de testes, loop de lint/format, loop de migração, loop de dados, loop de docs, loop composto | Prático |
| 2.5 | Combinando Plan + Loop | Plan para definir, loop para executar, pipeline plan→loop→review, handoff entre modos, escalando complexidade, case studies | Avançado |
| 2.6 | Agentic Coding — O Novo Normal | Filosofia agentic, delegação eficaz, revisão vs micro-management, trust calibration, velocity metrics, mindset shift | Conceitual |

### Trilha 3: MCP Servers (Purple) — Semanas 5-6

| Módulo | Título | Tópicos (6) | Tipo |
|--------|--------|-------------|------|
| 3.1 | O que são MCP Servers | Protocolo MCP, client-server, tool discovery, por que importa, ecosystem overview, analogia com APIs | Fundamento |
| 3.2 | Seus Primeiros MCPs | Filesystem, Git, SQLite, configuração no settings.json, testando ferramentas, troubleshooting | Prático |
| 3.3 | MCPs de Produtividade | Slack, Google Calendar, Gmail, Notion, Linear, combinando múltiplos MCPs | Prático |
| 3.4 | MCPs de Database e APIs | PostgreSQL, Redis, HTTP/REST, GraphQL, conectando a serviços reais, segurança de credenciais | Prático |
| 3.5 | Criando seu Próprio MCP Server | Anatomia de um server, SDK (TypeScript/Python), definindo tools, input schemas, testing, packaging | Avançado |
| 3.6 | Ecossistema e Marketplace | Awesome MCP, Smithery, community servers, avaliando qualidade, composição de servers, futuro do MCP | Conceitual |

### Trilha 4: Subagentes e Git (Amber) — Semanas 7-10

| Módulo | Título | Tópicos (6) | Tipo |
|--------|--------|-------------|------|
| 4.1 | Subagentes — Conceitos | O que são, Task tool, tipos de agente, comunicação pai-filho, isolamento, quando usar vs não usar | Fundamento |
| 4.2 | Paralelismo Real | Lançando múltiplos agents, independência vs dependência, worktrees, background tasks, coletando resultados | Prático |
| 4.3 | Patterns de Multi-Agent | Fan-out/fan-in, pipeline, explore→plan→execute, specialist agents, error handling, cost control | Avançado |
| 4.4 | Git com IA — Versionamento | Commits semânticos, staging inteligente, diff review, merge conflicts, branching strategy, .gitignore | Prático |
| 4.5 | Pull Requests e Code Review | Criar PRs com gh, review automatizado, CI checks, addressing feedback, squash/rebase, best practices | Prático |
| 4.6 | CI/CD e GitHub Actions | Actions basics, workflow com Claude, testes automatizados, deploy contínuo, security scanning, monitoring | Avançado |

### Trilha 5: Python e Ship (Teal) — Semanas 11-12

| Módulo | Título | Tópicos (6) | Tipo |
|--------|--------|-------------|------|
| 5.1 | Python + Claude Code | Setup Python, venvs, pip/uv, scripts de automação, debugging, type hints com IA | Prático |
| 5.2 | Automação de Scripts | Web scraping, file processing, data transforms, scheduling, APIs de terceiros, error handling robusto | Prático |
| 5.3 | FastAPI e Web Services | API REST com FastAPI, modelos Pydantic, endpoints, middleware, docs automáticas, deploy | Prático |
| 5.4 | Testing Automatizado | pytest basics, fixtures, mocks, coverage, TDD com Claude, CI integration | Prático |
| 5.5 | Deploy e Infraestrutura | Docker basics, Docker Compose, cloud deploy (Railway/Fly.io), env management, monitoring | Avançado |
| 5.6 | Ship Your Product | MVP mindset, priorização, launch checklist, feedback loop, iteração, o que vem depois | Conceitual |

---

## Regras de Produção

- Cada módulo: 500-800 linhas HTML, ≥6 tópicos, ≥1 SVG futurista, variados componentes
- Módulos práticos: ≥1 exemplo copy-run real
- Módulos fundamento: definir cada termo inline
- Manifesto completo em todas as páginas
- Anti-FOUC + learn.css + learn.js + INEMA.init()
- Cores: T1=Emerald, T2=Blue, T3=Purple, T4=Amber, T5=Teal
