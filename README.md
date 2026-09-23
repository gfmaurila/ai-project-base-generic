# AI Project Base — Generic

Estrutura genérica para desenvolvimento assistido por IA, preparada para:

- Claude Code
- OpenAI Codex
- GitHub Copilot

## Princípio central

A documentação do projeto é a fonte de verdade. Os arquivos específicos de cada IA funcionam como adaptadores e apontam para as mesmas regras, estado e tarefas.

## Fluxo recomendado

1. Preencher `PROJECT.md`.
2. Definir requisitos em `docs/requirements/`.
3. Definir arquitetura em `docs/architecture/`.
4. Se houver UI, cadastrar referências em `docs/screens/`.
5. Criar tarefas a partir de `tasks/TASK-TEMPLATE.md`.
6. Colocar somente a tarefa atual em `tasks/CURRENT.md`.
7. Pedir para a IA executar somente a tarefa atual.
8. Exigir build, testes, validação e atualização do `PROJECT-STATE.md`.

## Arquivos por IA

- Claude Code: `CLAUDE.md` + `.claude/`
- Codex: `AGENTS.md` + `.codex/`
- GitHub Copilot: `.github/copilot-instructions.md` + `.github/instructions/`

Não coloque regras de negócio importantes apenas em arquivos específicos de uma IA.
