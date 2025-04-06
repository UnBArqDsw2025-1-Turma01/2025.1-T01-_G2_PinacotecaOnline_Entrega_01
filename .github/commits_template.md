# Commits

## Formato das Mensagens de Commit:

A mensagem do commit deve ser concisa e descritiva, respeitando o seguinte formato:

<tipo>(<escopo opcional>): <descrição da mudança><issue>

[corpo opcional]

### Exemplos:
- refactor(pagamento): extrai lógica de cálculo de frete para função separada #161. Corpo: Facilita a manutenção e os testes da lógica de cálculo de frete.
- style(cabeçalho): ajusta espaçamento entre os elementos #151. Corpo: Melhora o espaçamento entre os elementos do cabeçalho para melhor legibilidade.
- docs(API): corrige documentação do endpoint de login #131. Corpo: Corrige a descrição do formato de resposta do endpoint de login.
- fix(pagamento): corrige erro de cálculo do frete #789. Corpo: Resolve o problema que causava o cálculo incorreto do frete.
- feat(cadastro): adiciona campo de CPF #123. Corpo: Implementa a validação do CPF no formulário de cadastro.

## Descrição:

### Tipos de Commits:
- feat: Novas funcionalidades.
- fix: Correção de bugs.
- docs: Alterações na documentação.
- style: Alterações no estilo do código (formatação, etc.).
- refactor: Refatoração de código (sem adicionar funcionalidades ou corrigir bugs).
- test: Adição ou correção de testes.
- chore: Alterações nas tarefas de build ou dependências.
- perf: Alterações de performance.

### Escopo: 
- Indica a parte do código que foi afetada pelo commit. Ele é opcional, mas recomendado para commits mais complexos. Exemplos: (login), (api), (componente-usuário).

### Descrição:
- Descrição clara e concisa das alterações realizadas. Utilizar o imperativo presente (ex: "Adiciona funcionalidade de login"). Evitar detalhes excessivos; o código deve falar por si.

## Comandos:
- Commit com mensagem de uma linha: git commit -m "mensagem";
- Commit com mensagem de uma ou mais linhas: git commit -m "Assunto" -m "Descrição..."

### Exemplos:

```sh
git commit -m "fix(pagamento): corrige erro de cálculo do frete #789" -m "Resolve o problema que causava o cálculo incorreto do frete."
```

