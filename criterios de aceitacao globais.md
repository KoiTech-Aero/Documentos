# Critérios de Aceitação do Backlog

Uma história de usuário é considerada aceita quando todos os critérios abaixo forem atendidos.

## 1. Implementação da funcionalidade
```
- A funcionalidade descrita na história foi implementada conforme a descrição da US

- Todos os critérios de aceitação específicos da história foram atendidos
```

## 2. Versionamento e fluxo de desenvolvimento

O desenvolvimento deve seguir o fluxo de versionamento no repositório remoto

### Desenvolvimento de novas funcionalidades

Para implementação de features deve ser:
```
criada uma branch seguindo o padrão
  `feat-nome-da-feature`

realizado commit seguindo o padrão
  `feat: descrição do que foi implementado`

solicitado Pull Request

o Pull Request deve:
  - possuir revisão de pelo menos um membro da equipe
  - estar aprovado antes do merge
```

### Correções

Para correções de erros deve ser:
```
criada uma branch seguindo o padrão
  `hotfix-descricao-da-correcao`

realizado commit seguindo o padrão
  `fix: descrição da correção realizada`

aberto Pull Request com revisão da equipe
```

### Documentação

Para alterações na documentação do projeto:
```
 branch
  `docs-descricao`

commit
  `docs: descrição do que foi feito`

abrir Pull Request para revisão
```

## 3. Validação da funcionalidade

- A funcionalidade deve ser testada pela equipe
- O comportamento deve corresponder ao definido nos critérios da história
