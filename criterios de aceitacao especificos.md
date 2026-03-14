## US01 — Cadastrar norma
```
- O sistema deve permitir cadastrar uma norma informando código e título

- O sistema deve permitir registrar descrição ou resumo da norma
- O sistema deve registrar a data de cadastro da norma

- O sistema não deve permitir cadastrar duas normas com o mesmo código
```

## US02 — Registrar versões de norma
```
- O sistema deve permitir adicionar uma nova versão a uma norma existente

- Cada versão deve possuir identificação de versão

- O sistema deve manter histórico das versões registradas

- O sistema deve permitir visualizar todas as versões de uma norma

- O sistema deve indicar qual versão é a atualmente ativa
```

## US03 — Listar normas ativas
```
- O sistema deve permitir listar todas as normas ativas

- Normas desativadas ou obsoletas não devem aparecer na listagem padrão

- A listagem deve exibir código e título da norma

- A listagem deve ser acessível ao perfil engenheiro
```

## US04 — Registrar requisitos de uma norma
```
- O sistema deve permitir registrar requisitos associados a uma norma

- Cada requisito deve possuir identificador ou número

- Cada requisito deve possuir descrição textual

- O requisito deve permanecer associado à norma correspondente

- Deve ser possível listar os requisitos de uma norma
```

## US05 — Registrar correlações entre requisitos
```
- O sistema deve permitir associar um requisito a outro requisito

- A correlação deve indicar qual requisito referencia o outro

- O sistema deve permitir visualizar as correlações existentes

- Um requisito pode possuir mais de uma correlação
```

## US06 — Cadastrar tags
```
- O sistema deve permitir cadastrar uma nova tag

- Cada tag deve possuir nome único

- O sistema não deve permitir duplicação de tags

- As tags cadastradas devem ficar disponíveis para associação às normas
```

## US07 — Associar tags às normas
```
- O sistema deve permitir associar uma ou mais tags a uma norma

- Apenas tags previamente cadastradas podem ser associadas

- Deve ser possível visualizar as tags associadas a uma norma

- Deve ser possível remover uma associação de tag
```

## US08 — Filtrar normas por tags
```
- O sistema deve permitir selecionar uma ou mais tags como filtro

- A listagem deve exibir apenas normas associadas às tags selecionadas

- Se nenhuma norma corresponder ao filtro, o sistema deve informar ausência de resultados
```

## US09 — Buscar normas por código ou nome
```
- O sistema deve permitir pesquisar normas pelo código da norma

- O sistema deve permitir pesquisar normas pelo nome ou título

- A busca deve retornar todas as normas que correspondam ao termo pesquisado

- O sistema deve permitir selecionar uma norma a partir do resultado da busca
```

## US10 — Filtrar normas por área técnica
```
- O sistema deve permitir selecionar uma área técnica como filtro

- A listagem deve exibir apenas normas da área selecionada

- O filtro deve poder ser removido para exibir todas as normas novamente
```

## US11 — Combinar filtros de área e tags
```
- O sistema deve permitir aplicar filtro por área técnica e tags simultaneamente

- A listagem deve retornar apenas normas que satisfaçam todos os filtros aplicados

- Deve ser possível remover individualmente cada filtro aplicado
```

## US12 — Cadastrar usuários
```
- O sistema deve permitir cadastrar novo usuário informando nome e identificação

- O sistema deve permitir definir perfil do usuário (engenheiro ou gestor)

- O sistema não deve permitir duplicação de usuários com o mesmo identificador

- O usuário cadastrado deve aparecer na lista de usuários
```

## US13 — Visualizar usuários
```
- O sistema deve permitir visualizar todos os usuários cadastrados

- A listagem deve exibir nome e perfil do usuário

- A listagem deve ser acessível apenas ao gestor do sistema
```

## US14 — Alterar dados ou permissões
```
- O sistema deve permitir editar dados de um usuário existente

- O sistema deve permitir alterar o perfil/permissões do usuário

- As alterações devem ser salvas e refletidas na lista de usuários
```

## US15 — Desativar usuários
```
- O sistema deve permitir desativar um usuário existente

- Usuários desativados não devem conseguir acessar o sistema

- O sistema deve manter registro do usuário desativado para histórico
```