# 📦 Catálogo — `developer-challenge`

> **Recrutamento · Repo público** — Desafio técnico para candidatos. Público no GitHub. 1 commit (2026-05-28).
>
> Status: **🟢 Ativo** (em desenvolvimento ativo) · Catalogado em 2026-08-11

Documento gerado na análise estrutural do parque de aplicações Webapps da Kingspan Isoeste.
Visão consolidada do parque, consolidação e roadmap de EDA: **`ANALISE-PARQUE-WEBAPPS.md`** na raiz de `~/projetos/ksi/kingspan/`.

---

## 1. Identidade

| Campo | Valor |
|---|---|
| Pasta local | `developer-challenge` |
| Repositório GitHub | `developer-challenge` |
| Aplicação | Recrutamento |
| Camada | Repo público |
| Branch local | `main` |
| Marcadores de stack | — |

## 2. O que entrega para o negócio

Enunciado do teste técnico de contratação, com `AGENTS.md`, `CLAUDE.md`, `README.md` (299 linhas) e `suggestions.md`.

## 3. Estrutura e features detectadas

Nenhuma estrutura de módulos/rotas/entidades foi detectada automaticamente — repositório sem código extraível, vazio, ou com organização fora dos padrões reconhecidos.

## 4. Saúde técnica

| Métrica | Valor | Leitura |
|---|---|---|
| Último commit | 2026-05-28 | por *mauriciofilhoTI* |
| Último assunto | `feat: :sparkles: add test description` | |
| Total de commits | 1 | primeiro em 2026-05-28 |
| Autores no histórico | 1 | bus factor alto |
| Branches remotas | 3 | ok |
| CI (GitHub Actions) | 0 workflows | ⚠️ sem CI no repositório |
| Arquivos de código | 0 | |
| Arquivos citando SQS/SNS | 0 | |
| README na raiz | ❌ ausente | |
| Pasta `docs/` | ❌ ausente | |

## 5. Pontos de atenção

- **Repo público da org** — verificar que não expõe detalhes internos de arquitetura.
- Contém `CLAUDE.md` e `AGENTS.md`: instruções para agentes de IA num desafio que avalia candidatos. Considerar se isso é intencional (candidatos podem usar IA) ou vazamento de gabarito.

## 6. Papel na virada para EDA (SQS/SNS via integrations-service)

Nenhum.

## 7. Recomendação de consolidação

> **Manter.** Revisar o conteúdo público.

---

## 8. Plano de evolução — 17/08/2026 (Mesa 5)

Documento-mãe do sistema: [`ECOSSISTEMA-2026/17-PLANOS-POR-SISTEMA.md`](../ECOSSISTEMA-2026/17-PLANOS-POR-SISTEMA.md).
Mesa: [`02-MESA-EDA-TESTES-O11Y.md`](../ECOSSISTEMA-2026/02-MESA-EDA-TESTES-O11Y.md) ·
EDA [`14`](../ECOSSISTEMA-2026/14-PLANO-MIGRACAO-EDA.md) ·
testes/AI [`15`](../ECOSSISTEMA-2026/15-PLANO-TESTES-AI.md) ·
o11y [`16`](../ECOSSISTEMA-2026/16-PLANO-OBSERVABILIDADE.md).

| Eixo | Plano |
|---|---|
| **EDA / Datasul** | Manter público; revisar conteúdo. |
| **Testes / AI** | N/A. |
| **Observabilidade** | Não. |

> Premissa: o `integrations-service` **está em construção** e ainda não centralizou o parque. Feature nova não abre `DatasulClient`. Agente de IA só gera PR de feature em repo ≥ L2 (CI + contrato + teste do que mudou).

<sub>Catálogo gerado por análise automatizada do código-fonte + revisão. Fontes: `git log`, manifests de dependência, estrutura de diretórios, Second Brain (Catálogo de Aplicações WebApps, Mapeamento AWS jul/2026, Grafo Graphify).</sub>
