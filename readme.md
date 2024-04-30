PrsRelease
==========

Repositório para gerenciar os release do software Pro Racing Software.

## Instruções de Lançamento:

- Mudar branch para develop. Pode ser necessário desfazer alterações para mudar a branch.
- Incrementar a Versão do Assembly nas Configurações do Projeto
- Incrementar a Versão do Produto no SetupPRS (Product.wxs)
- Adicionar novos arquivos caso necessário no instalador (InstallationComponentsPrs.wxs)
- Caso necessário baixar (icons8.com), converter para .ico (https://convertio.co/pt/png-ico/), e colocar um ícone na aplicação (quando for app nova)
- Incrementar a Versão no manifest.json
- Incrementar a Data de Lançamento no manifest.json
- Atualizar o URL no manifest.json
- Atualizar/criar registro de alterações no manifest.json
- Atualizar o Registro de Alterações no changelog.md
- Atualizar data de lançamento no changelog.md
- Salvar alterações
- Compilar Solução versões Debug e Release
- Desinstalar versão atual
- Baixar instalador do site do PRS e instalar
- Instalar por cima a versão nova e testar o acesso as telas
- Commit no repositório prs_release e enviar
- Commit e pull request no repositório prs_app para a branch develop
- No prs_app mudar para a branch develop, sincronizar, e deletar a branch mesclada
