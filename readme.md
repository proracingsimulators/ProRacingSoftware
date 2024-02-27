PrsRelease
==========

Repositório para gerenciar os release do software Pro Racing Software.

## Instruções de Lançamento:

- Desinstalar versão atual
- Baixar instalador do site do PRS e instalar
- Instalar por cima a versão nova e testar o acesso as telas
- Mudar branch para develop. Pode ser necessário desfazer alterações para mudar a branch.
- Incrementar a Versão do Assembly e do Arquivo nas Configurações do Projeto
- Incrementar a Versão do Produto no SetupPRS (Product.wxs)
- Incrementar a Versão no manifest.json
- Incrementar a Data de Lançamento no manifest.json
- Atualizar o URL no manifest.json
- Atualizar/criar registro de alterações no manifest.json
- Atualizar o Registro de Alterações no changelog.md
- Atualizar data de lançamento no changelog.md
- Compilar Solução versões Debug e Release
- Commit no repositório prs_release e enviar
- Commit e pull request no repositório prs_app para a branch develop
- No prs_app mudar para a branc develop, sincronizar, e deletar a branch mesclada
