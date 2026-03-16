# ÉPICOS E HISTÓRIAS DE USUÁRIO DETALHADOS

## ÉPICO 01 - GESTÃO DE NORMAS
Permitir armazenar, versionar e relacionar normas técnicas

### Características
- cadastro de normas
- versionamento
- resumo/contexto da norma
- referências entre normas
- notas em versões

### Histórias de usuário
**US01**
```
Como gestor do sistema
quero cadastrar uma nova norma
para que ela esteja disponível no sistema
```

**US02**
```
Como gestor do sistema
quero registrar versões de uma norma
para manter histórico e rastreabilidade
```

**US03**
```
Como engenheiro
quero listar normas ativas
para saber quais são válidas para uso
```

**US04**
```
Como gestor do sistema
quero associar uma norma a outras normas referenciadas
para representar as dependências entre normas
```

**US05**
```
Como engenheiro
quero visualizar quais normas são referenciadas por uma norma
para entender suas dependências técnicas
```

**US06**
```
Como gestor do sistema
quero cadastrar um resumo ou contexto da norma
para facilitar o entendimento do seu conteúdo
```

**US07**
```
Como engenheiro
quero solicitar uma nota para uma norma
para registrar observações ou interpretações técnicas
```

**US08**
```
Como gestor do sistema
quero aprovar ou rejeitar notas solicitadas
para controlar o conteúdo exibido no sistema
```

**US09**
```
Como engenheiro
quero visualizar as notas aprovadas em uma norma
para entender observações relevantes
```

**US10**
```
Como engenheiro
quero solicitar o cadastro de uma norma
para que ela seja adquirida ou cadastrada pela empresa
```

## ÉPICO 02 - SISTEMA DE TAGS
Permitir classificar normas usando palavras-chave técnicas

### Características
- cadastro de tags
- associação de tags às normas

### Histórias de usuário
**US11**
```
Como gestor do sistema
quero cadastrar novas tags
para classificar normas de forma padronizada
```

**US12**
```
Como gestor do sistema
quero associar tags às normas
para melhorar a organização e busca
```

## ÉPICO 03 - BUSCA E FILTRAGEM
Permitir encontrar normas rapidamente

### Características
- busca por código ou nome
- busca por palavras-chave (tags)

### Histórias de usuário
**US13**
```
Como engenheiro
quero pesquisar normas pelo código ou pelo nome
para encontrar rapidamente uma norma específica
```

**US14**
```
Como engenheiro
quero pesquisar normas por palavras-chave (tags)
para encontrar normas relacionadas a um tema técnico
```

## ÉPICO 04 - GESTÃO DE USUÁRIOS
Permitir "tipos" de usuário no sistema

### Características
- cadastro de usuários
- gerenciamento de usuários

### Histórias de usuário
**US15**
```
Como gestor do sistema
quero cadastrar novos usuários no sistema
para que eles possam acessar a plataforma conforme suas permissões
```

**US16**
```
Como gestor do sistema
quero visualizar a lista de usuários cadastrados
para que eu possa gerenciar quem tem acesso ao sistema
```

**US17**
```
Como gestor do sistema
quero alterar dados ou permissões de um usuário
para que eu possa ajustar seu acesso quando necessário
```

**US18**
```
Como gestor do sistema
quero desativar usuários
para que eles não tenham mais acesso ao sistema
```

<br><br>

## Sprint 1 - Estrutura básica de normas

**Meta da Sprint (US01 e US03):** Estabelecer a estrutura inicial do sistema, permitindo o cadastro de normas, registro de versões, inclusão de contexto e visualização de referências entre normas

**User Stories da Sprint 1**
```
US01 - Cadastrar normas
US02 - Registrar versões de normas
US03 - Listar normas
US04 - Associar normas referenciadas
US05 - Visualizar normas referenciadas
US06 - Cadastrar resumo/contexto da norma
```

## Sprint 2 - Estrutura básica de normas

**Meta da Sprint (US13):** Permitir organizar normas por meio de tags e disponibilizar mecanismos de busca por código, nome ou palavras-chave

**User Stories da Sprint 2**
```
US11 - Cadastrar novas tags
US12 - Associar tags às normas
US13 - Pesquisar normas por código ou nome
US14 - Pesquisar normas por palavras-chave
```

### Sprint 3 - Estrutura básica de normas

**Meta da Sprint (US07 e US15):** Implementar mecanismos de colaboração entre engenheiros e gestores, além de permitir a administração de usuários do sistema

**User Stories da Sprint 3**
```
US07 - Solicitar nota para uma norma
US08 - Aprovar ou rejeitar notas
US09 - Visualizar notas aprovadas
US10 - Solicitar cadastro de nova norma
US15 - Cadastrar usuários
US16 - Visualizar usuários
US17 - Editar usuários
US18 - Desativar usuários
```