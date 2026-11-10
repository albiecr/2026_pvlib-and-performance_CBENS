# Estudos — CBENS 2026 (pvlib e análise de desempenho)

Exercícios do curso refeitos por mim, com `TODO(human)` para praticar.

| Arquivo | O que é |
|---|---|
| `03_clearsky.ipynb` | Função 3 — `get_clearsky`: céu claro em Niterói, conferência GHI = DNI·cos(θz) + DHI e irradiação diária (kWh/m²) |

---

## ⚠️ Lembrete: como fazer commit

1. Conferir o que mudou: `git status`
2. Adicionar o arquivo: `git add <arquivo>`
3. Rodar **`git commit`** (sem `-m`!)
4. Abre uma aba no VS Code com o modelo → escrever na **1ª linha**
5. Salvar (**Ctrl+S**) e **fechar a aba** → o commit é concluído
6. Conferir: `git log --oneline -3`

**Formato:** `<tipo>(<área>): <ação no presente>`

| Tipo | Quando usar |
|---|---|
| `feat` | algo novo |
| `fix` | correção |
| `docs` | documentação |
| `study` | exercício/estudo |
| `chore` | manutenção |

Exemplo: `study(funcao3): refaz exercício de get_clearsky`

**Observações**

- Para cancelar: apague tudo na aba, salve e feche.
- `git commit -m "..."` e a caixa de commit do VS Code **não** mostram o modelo.
- Só funciona no terminal do **VS Code** (SSH pelo VS Code). Em SSH puro pelo PowerShell o comando `code` não existe.
- Modelo: `.gitmessage.txt` na raiz do repositório. Configuração (só neste repo):
  `git config commit.template ...` e `git config core.editor "code --wait"`.
  Desfazer: `git config --unset commit.template` e `git config --unset core.editor`.
