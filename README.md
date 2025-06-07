# Guia de Commits para Projetos .NET

## Visão Geral
Este documento descreve o padrão de mensagens de commit utilizado em nossos projetos .NET. Seguir estas diretrizes ajuda na colaboração, na rastreabilidade das mudanças e na manutenção de um histórico limpo.

## Tipos de Commit
- `feat`: nova funcionalidade.
- `fix`: correção de bug.
- `docs`: documentação.
- `test`: testes unitários.
- `build`: ajustes de build e dependências.
- `perf`: melhoria de performance.
- `style`: formatação ou padronização de estilo (sem alteração de código).
- `refactor`: refatoração que não corrige bug nem adiciona recurso.
- `chore`: tarefas rotineiras como atualização de dependências.
- `ci`: alterações em pipelines de integração contínua.
- `raw`: arquivos de configuração ou dados.

## Estrutura da Mensagem
### Título
- Resuma a mudança em até 50 caracteres.
- Use o tipo de commit seguido de dois pontos.
- Escreva no imperativo, por exemplo: `feat: adicionar tela de login`.

### Corpo
- Detalhe o que foi feito e o motivo.
- Quebre em linhas de até 72 caracteres.
- Utilize marcadores para múltiplos itens.
- Referencie IDs de tarefa ou issues.

### Rodapé
- Adicione metadados como `Reviewed-by` ou `BREAKING CHANGE`.
- Inclua links para tarefas (Jira, Trello etc.).

## Exemplo
```text
feat: implementar autenticação

- cria endpoint /login
- ajusta validação de usuário
- adiciona testes de autenticação

Reviewed-by: Maria Silva
Refs: TRELLO-123
```

## Melhores Práticas
- Mantenha os commits pequenos e focados.
- Revise a mensagem antes de enviar.
- Evite descrições genéricas como "update" ou "fix bug".
- Prefira escrever as mensagens em inglês quando o projeto for internacional.

---

*Commite com propósito, clareza e profissionalismo.*
