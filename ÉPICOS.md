# **ÉPICO 01 - GESTÃO DE NORMAS**
Permitir armazenar, versionar e relacionar normas técnicas

### Características:
- cadastro de normas
- versionamento
- resumo/contexto da norma
- referências entre normas
- notas em versões

### Histórias de usuário:
**US01 — Cadastrar norma**
```
Como gestor do sistema
quero cadastrar uma nova norma
para que ela esteja disponível no sistema
```

**US02 — Registrar versões de norma**
```
Como gestor do sistema
quero registrar versões de uma norma
para manter histórico e rastreabilidade
```

**US03 — Listar normas ativas**
```
Como engenheiro
quero listar normas ativas
para saber quais são válidas para uso
```

**US04 — Associar normas referenciadas**
```
Como gestor do sistema
quero associar uma norma a outras normas referenciadas
para representar as dependências entre normas
```

**US05 — Visualizar normas referenciadas**
```
Como engenheiro
quero visualizar quais normas são referenciadas por uma norma
para entender suas dependências técnicas
```

**US06 — Solicitação de nota**
```
Como engenheiro
quero solicitar uma nota para uma norma
para registrar observações ou interpretações técnicas
```

**US07 — Visualização de notas**
```
Como engenheiro
quero visualizar todas as notas no sistema
para entender observações relevantes
```

**US08 — Aprovação de notas**
```
Como gestor do sistema
quero aprovar ou rejeitar notas solicitadas
para controlar o conteúdo exibido no sistema
```

**US09 — Solicitar cadastro de norma**
```
Como engenheiro
quero solicitar o cadastro de uma norma
para que ela seja adquirida ou cadastrada pela empresa
```

<br>

# **ÉPICO 02 - SISTEMA DE TAGS**
Permitir classificar normas usando palavras-chave técnicas

### Características:
- cadastro de tags
- associação de tags às normas

### Histórias de usuário:
**US10 — Cadastro de tags**
```
Como gestor do sistema
quero cadastrar novas tags
para classificar normas de forma padronizada
```

**US11 — Associação de tags às normas**
```
Como gestor do sistema
quero associar tags às normas
para melhorar a organização e busca
```

<br>

# **ÉPICO 03 - BUSCA E FILTRAGEM**
Permitir encontrar normas rapidamente

### Características:
- busca por código ou nome
- busca por palavras-chave (tags)

### Histórias de usuário:
**US12 — Busca por código ou nome**
```
Como engenheiro
quero pesquisar normas pelo código ou pelo nome
para encontrar rapidamente uma norma específica
```

**US13 — Busca por tags**
```
Como engenheiro
quero pesquisar normas por palavras-chave (tags)
para encontrar normas relacionadas a um tema técnico
```

<br>

# **ÉPICO 04 - GESTÃO DE USUÁRIOS**
Permitir "tipos" de usuário no sistema

### Características:
- cadastro de usuários
- gerenciamento de usuários

### Histórias de usuário:
**US14 — Cadastrar usuários**
```
Como gestor do sistema
quero cadastrar novos usuários no sistema
para que eles possam acessar a plataforma conforme suas permissões
```

**US15 — Visualizar usuários**
```
Como gestor do sistema
quero visualizar a lista de usuários cadastrados
para que eu possa gerenciar quem tem acesso ao sistema
```

**US16 — Alterar dados ou permissões de usuário**
```
Como gestor do sistema
quero alterar dados ou permissões de um usuário
para que eu possa ajustar seu acesso quando necessário
```

**US17 — Desativar usuários**
```
Como gestor do sistema
quero desativar usuários
para que eles não tenham mais acesso ao sistema
```