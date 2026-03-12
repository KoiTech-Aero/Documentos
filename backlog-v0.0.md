# ÉPICOS E HISTÓRIAS DE USUÁRIO DETALHADOS

## ÉPICO 01 - GESTÃO DE NORMAS
Permitir armazenar e gerenciar normas técnicas

### Características
- cadastro de normas
- upload de arquivos
- versionamento de normas
- marcar como norma obsoleta

### Histórias de usuário
**US01**
```
Como gestor de normas
quero cadastrar uma nova norma
para que ela esteja disponível no sistema
```

**US02**
```
Como gestor de normas
quero registrar versões de uma norma
para manter histórico e rastreabilidade
```

**US03**
```
Como engenheiro
quero visualizar normas ativas
para saber quais são válidas para uso
```

## ÉPICO 02 - SISTEMA DE TAGS
Permitir classificar normas usando palavras-chave técnicas

### Características
- cadastro de tags
- associação de tags às normas
- busca por tags
- filtragem por tags

### Histórias de usuário
**US04**
```
Como gestor de normas
quero cadastrar novas tags
para classificar normas de forma padronizada
```

**US05**
```
Como gestor de normas
quero associar tags às normas
para melhorar a organização e busca
```

**US06**
```
Como engenheiro
quero filtrar normas por tags
para encontrar rapidamente normas relevantes
```

## ÉPICO 03 - FILTRAGEM E BUSCA DE NORMAS
Permitir encontrar normas rapidamente

### Características
- busca por código (id)
- busca por texto
- filtragem por área
- filtragem por tags
- filtros combinados

### Histórias de usuário
**US07**
```
Como engenheiro
quero pesquisar normas por código ou nome
para encontrar uma norma específica
```

**US08**
```
Como engenheiro
quero filtrar normas por área técnica
para reduzir o número de resultados
```

**US09**
```
Como engenheiro
quero combinar filtros de área e tags
para encontrar normas com mais precisão
```

## ÉPICO 04 - GESTÃO DE PEÇAS
Permitir registrar peças e normas aplicadas

### Características
- cadastro de peças
- associação de normas
- histórico de normas usadas

### Histórias de usuário
**US10**
```
Como engenheiro
quero cadastrar uma peça
para documentar sua fabricação
```

**US11**
```
Como engenheiro
quero associar normas a uma peça
para registrar quais foram utilizadas
```

## ÉPICO 05 - DOCUMENTAÇÃO DE ETAPAS
Registro de documentos por fase de peça

### Características
- upload de documentos
- registro de etapas
- vínculo com peça

### Histórias de usuário
**US12**
```
Como engenheiro
quero registrar documentos em cada etapa da peça
para manter rastreabilidade do processo
```

## ÉPICO 06 - SEGURANÇA E CONTROLE DE ACESSO
Permitir "tipos" de usuário no sistema

### Características
- autenticação
- permissões
- acesso controlado dos arquivos

### Histórias de usuário
**US13**
```
Como gestor do sistema
quero definir permissões de usuários
para controlar quem pode editar normas
```

**US14**
```
Como gestor do sistema
quero acessar apenas recursos permitidos
para garantir segurança das informações.
```

## ÉPICO 07 - PREPARAÇÃO PARA IA

### Características
- armazenamento estruturado de dados
- histórico de aplicação de normas

### Histórias de usuário
**US15**
```
Como engenheiro
quero registrar histórico de normas aplicadas às peças
para permitir recomendações futuras por IA
```

<br><br>

# MAPA DAS SPRINTS
```
A intenção é seguir uma progressão de valor

Primeiro: resolver a principal dor do cliente
 - encontrar as normas rapidamente
 - organizando as informações

Segundo: permitir o uso real no processo de engenharia

Terceiro: finalizar com a rastreabilidade e segurança
```

## Sprint 1

**Meta da Sprint:** US08 - Filtrar normas por área técnica

Aqui nós entregamos o maior valor para o cliente, reduzindo o tempo de busca das normas

### Épicos envolvidos
```
ÉPICO 01 – Gestão de normas
ÉPICO 02 – Sistema de tags
ÉPICO 03 – Filtragem e busca
```

### User Stories da Sprint 1
```
US01 - Cadastrar normas no sistema
US03 - Visualizar normas ativas
US04 - Cadastrar tags
US05 - Associar tags às normas
US06 - Filtrar normas por tags
US08 - Filtrar normas por área técnica
```

### Características entregues na Sprint 1

ÉPICO 01 – Gestão de Normas
```
- cadastro de normas
- upload de arquivos

(versionamento e obsolescência ficam para outra sprint)
```

ÉPICO 02 – Sistema de Tags
```
- cadastro de tags
- associação de tags às normas
- filtragem por tags
```

ÉPICO 03 – Filtragem e Busca
```
- filtragem por área
- filtragem por tags

(busca textual e filtros combinados ficam para sprint seguinte)
```

### Resultado da Sprint 1

O sistema já permitirá:
```
- cadastrar normas
- cadastrar tags
- associar tags às normas
- filtrar normas por área
- filtrar normas por tags
```

## Sprint 2

**Meta da Sprint:** US11 — Associar normas a uma peça

Essa é a funcionalidade que começa a gerar valor operacional real

### Épicos envolvidos
```
ÉPICO 03 – Filtragem e busca
ÉPICO 04 – Gestão de peças
```

### User Stories da Sprint 2
```
US07 - Pesquisar normas por código ou nome
US09 - Combinar filtros de área e tags
US10 - Cadastrar uma peça
US11 - Associar normas a uma peça
```

### Características entregues na Sprint 2

ÉPICO 03 – Filtragem e Busca
```
- busca por código
- busca por texto
- filtros combinados
```

ÉPICO 04 – Gestão de Peças
```
- cadastro de peças
- associação de normas
- histórico de normas usadas
```

### Resultado da Sprint 2

O sistema já permitirá:
```
- cadastrar peças
- encontrar normas rapidamente
- associar normas a peças
- registrar histórico de aplicação
```

# Sprint 3

**Meta da Sprint:** US12 — Registrar documentos em cada etapa da peça

Isso garante rastreabilidade completa do processo de fabricação

### Épicos envolvidos
```
ÉPICO 01 – Gestão de normas
ÉPICO 05 – Documentação
ÉPICO 06 – Segurança
ÉPICO 07 – Preparação para IA
```

### User Stories da Sprint 3
```
US02 - Registrar versões de normas
US012 - Registrar documentação em cada etapa da peça
US013 - Definir permissões de usuários
US014 - Acessar apenas recursos permitidos
US015 - Registrar histórico de normas aplicadas às peças
```

### Características entregues na Sprint 3

ÉPICO 01 – Gestão de Normas
```
- versionamento de normas
- marcar norma como obsoleta
```

ÉPICO 05 – Documentação
```
- upload de documentos
- registro de etapas
- vínculo com peça
```

ÉPICO 06 – Segurança
```
- autenticação
- permissões
- acesso controlado aos arquivos
```

ÉPICO 07 – Preparação para IA
```
- armazenamento estruturado de dados
- histórico de aplicação de normas
```

### Resultado da Sprint 3

O sistema permitirá:
```
- rastreabilidade completa das peças
- controle de usuários
- histórico de normas utilizadas
- base estruturada para futura IA
```