# Branches

## Branch Principal (main/master):

Esta branch deve conter o código estável e pronto para produção. Deve ser protegida contra commits diretos. Todas as alterações devem ser incorporadas através de Pull Requests.

## Branches de Funcionalidades (feature branches):

Criadas a partir da branch principal para o desenvolvimento de novas funcionalidades.
Nomeadas no formato feature/NOME-DA-FUNCIONALIDADE.

### Exemplo: 
- feature/adicionar-autenticacao.

Devem ser o mais específicas e focadas possível.

## Branches de Correção de Bugs (bugfix branches):

Criadas a partir da branch principal para corrigir bugs.
Nomeadas no formato bugfix/DESCRICAO-DO-BUG.

### Exemplo: 
- bugfix/corrigir-erro-login.

Similar a funcionalidade, devem ser o mais específicas e focadas possivel.

## Branches de Refatoração (refactor branches):

Criadas a partir da branch principal para refatoração de código.
Nomeadas no formato refactor/DESCRICAO-DA-REFATORACAO.

### Exemplo: 
- refactor/otimizar-performance-consulta.

# Branches de Hotfix (hotfix branches):

Criadas a partir da branch principal em casos de correção urgente de bugs em produção.
Nomeadas no formato hotfix/DESCRICAO-DO-HOTFIX.
### Exemplo: 
- hotfix/corrigir-falha-pagamento.
