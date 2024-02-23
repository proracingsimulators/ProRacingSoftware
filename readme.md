PrsRelease
==========

Repositório para gerenciar os release do software Pro Racing Software.

## Instruções de Lançamento:

- Incrementar a Versão do Assembly e do Arquivo nas Configurações do Projeto
- Incrementar a Versão do Produto no SetupPRS (Product.wxs)
- Incrementar a Versão no manifest.json
- Incrementar a Data de Lançamento no manifest.json
- Atualizar o URL no manifest.json
- Atualizar/criar registro de alterações no manifest.json
- Atualizar o Registro de Alterações no changelog.md
- Atualizar data de lançamento no changelog.md
- Compilar Solução versões Debug e Release
- Commit e pull request prs_release
- Commit e pull request prs_app