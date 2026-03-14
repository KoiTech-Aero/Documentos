# Cenários por história de usuário

# US01
**Cenário 1 — Cadastro de norma com sucesso**
```
Dado que o gestor está na tela de cadastro de normas
Quando ele informa os dados obrigatórios de uma norma e confirma o cadastro
Então o sistema deve registrar a nova norma
```
**Cenário 2 — Código de norma já existente**
```
Dado que já existe uma norma cadastrada com determinado código
Quando o gestor tenta cadastrar outra norma com o mesmo código
Então o sistema deve impedir o cadastro
```
**Cenário 3 — Campos obrigatórios não informados**
```
Dado que o gestor está na tela de cadastro de normas
Quando ele tenta cadastrar uma norma sem preencher os campos obrigatórios
Então o sistema deve impedir o cadastro
```

# US02
**Cenário 1 — Registro de nova versão**
```
Dado que existe uma norma cadastrada no sistema
Quando o gestor registra uma nova versão para essa norma
Então o sistema deve armazenar a nova versão no histórico da norma
```
**Cenário 2 — Norma inexistente**
```
Dado que o gestor tenta registrar uma versão
Quando a norma informada não existe no sistema
Então o sistema deve impedir o registro da versão
```

# US03
**Cenário 1 — Listagem de normas ativas**
```
Dado que existem normas ativas cadastradas no sistema
Quando o engenheiro solicita a listagem de normas
Então o sistema deve exibir apenas as normas ativas
```

# US04
**Cenário 1 — Registro de requisito**
```
Dado que existe uma norma cadastrada
Quando o engenheiro registra um novo requisito associado a essa norma
Então o sistema deve armazenar o requisito
```
**Cenário 2 — Norma inexistente**
```
Dado que o engenheiro tenta registrar um requisito
Quando a norma informada não existe
Então o sistema deve impedir o registro
```

# US05
**Cenário 1 — Registro de correlação**
```
Dado que existem requisitos cadastrados no sistema
Quando o engenheiro registra uma correlação entre dois requisitos
Então o sistema deve armazenar essa correlação
```
**Cenário 2 — Requisito inexistente**
```
Dado que o engenheiro tenta registrar uma correlação
Quando um dos requisitos informados não existe
Então o sistema deve impedir o registro
```

# US06
**Cenário 1 — Cadastro de tag**
```
Dado que o gestor está na área de cadastro de tags
Quando ele informa os dados da nova tag
Então o sistema deve registrar a tag
```
**Cenário 2 — Tag já existente**
```
Dado que já existe uma tag cadastrada
Quando o gestor tenta cadastrar outra com a mesma identificação
Então o sistema deve impedir o cadastro
```

# US07
**Cenário 1 — Associação de tag a norma**
```
Dado que existem normas e tags cadastradas
Quando o gestor associa uma tag a uma norma
Então o sistema deve registrar essa associação
```

# US08
**Cenário 1 — Filtragem por tag**
```
Dado que existem normas associadas a diferentes tags
Quando o engenheiro aplica um filtro por tag
Então o sistema deve exibir apenas as normas que possuem essa tag
```

# US09
**Cenário 1 — Pesquisa por código ou nome**
```
Dado que existem normas cadastradas
Quando o engenheiro realiza uma pesquisa informando código ou nome
Então o sistema deve exibir as normas correspondentes
```

# US10
**Cenário 1 — Filtragem por área técnica**
```
Dado que existem normas associadas a diferentes áreas técnicas
Quando o engenheiro aplica o filtro por área técnica
Então o sistema deve exibir apenas as normas dessa área
```

# US11
**Cenário 1 — Uso de múltiplos filtros**
```
Dado que existem normas classificadas por área e tags
Quando o engenheiro aplica filtros de área e tags simultaneamente
Então o sistema deve exibir apenas normas que atendam aos filtros
```

# US12
**Cenário 1 — Cadastro de usuário**
```
Dado que o gestor está na área de cadastro de usuários
Quando ele informa os dados necessários
Então o sistema deve registrar o novo usuário
```

# US13
**Cenário 1 — Visualização da lista de usuários**
```
Dado que existem usuários cadastrados
Quando o gestor solicita a listagem de usuários
Então o sistema deve exibir os usuários cadastrados
```

# US14
**Cenário 1 — Alteração de dados de usuário**
```
Dado que existe um usuário cadastrado
Quando o gestor altera seus dados ou permissões
Então o sistema deve atualizar as informações do usuário
```

# US15
**Cenário 1 — Desativação de usuário**
```
Dado que existe um usuário ativo no sistema
Quando o gestor desativa esse usuário
Então o sistema deve registrar o usuário como inativo
```