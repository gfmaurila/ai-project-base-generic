# AGENTS.md — Codex

Você está trabalhando em um projeto orientado por tarefas.

Leia nesta ordem:
1. `PROJECT.md`
2. `AI-WORKFLOW.md`
3. `PROJECT-STATE.md`
4. `docs/`
5. `tasks/CURRENT.md`

Regras:
- Execute SOMENTE a tarefa atual.
- Preserve arquitetura e contratos existentes.
- Não faça refatorações fora do escopo sem necessidade comprovada.
- Não invente requisitos.
- Use mocks/fakes quando dependências externas não estiverem disponíveis.
- Gere ou atualize testes para comportamento alterado.
- Rode as validações aplicáveis antes de declarar PASS.
- Se houver UI de referência, trate `references/screens/` e `docs/screens/` como contrato visual.
- Ao final, entregue relatório objetivo: RESULT, FILES CHANGED, TESTS, VALIDATION, PENDING, NEXT SAFE STEP.

As regras compartilhadas em `docs/` e `AI-WORKFLOW.md` têm precedência sobre preferências locais do agente.
