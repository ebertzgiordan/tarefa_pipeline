# tarefa_pipeline

Tarefa de Pipeline DevOps com GitHub Actions.

Este repositório contém um arquivo `index.html` e um workflow de
Integração Contínua que valida o HTML automaticamente a cada `git push`.

## Regras de validação do pipeline

1. Verifica se a tag `<h1>` existe no `index.html`
2. Verifica se a declaração `<!DOCTYPE html>` existe (HTML5)
3. Verifica se a tag `<title>` existe na página

Se qualquer uma dessas regras falhar, o pipeline falha.
