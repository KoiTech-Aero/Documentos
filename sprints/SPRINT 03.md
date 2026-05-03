# Documentação Sprint 3

## Plataforma de Conteúdo Técnico de Normas Aeronáuticas

<p align="center">
  <img width="200" alt="koitech_logo" src="https://i.imgur.com/YugGoAM.png" />
</p>

<h2 align="center">
  <b>KOITECH</b>
</h2>

<p align="center">
  <a href ="#meta"> Meta</a>  |
  <a href ="#demonstracao">Demonstração</a>  |
  <a href ="#historias"> Histórias de usuário</a>  |   
  <a href ="#criterios">Critérios</a> |
  <a href ="#cenarios">Cenários</a> |
  <a href ="#dordod">DoR & DoD</a> |
  <a href ="#equipe"> Equipe</a>
</p>

> Status da Sprint: Não iniciada ❌

## 🏅 Meta (US06, US07 e US08) 
Permitir organizar normas por meio de tags e disponibilizar mecanismos de busca por código, nome ou palavras-chave <a id="meta"></a>

## 📌 Demonstração<a id="demonstracao"></a>

## 📝 Histórias de usuário <a id="historias"></a>

| RANK | PRIORIDADE | USER STORY                                                                                                                          | STORY POINTS | SPRINT | STATUS |
| :--: | :--------: | :---------------------------------------------------------------------------------------------------------------------------------- | :----------: | :----: | :----: |
|  11  |    alta    | Como engenheiro quero solicitar uma nota para uma norma para registrar observações ou interpretações técnicas                       |      8       |   3    |   ❌   |
|  12   |    alta    | Como engenheiro quero pesquisar normas pelo código ou pelo nome para encontrar rapidamente uma norma específica                     |      6       |   3    |   ❌   |
|  13  |   média    | Como gestor do sistema quero aprovar ou rejeitar notas solicitadas para controlar o conteúdo exibido no sistema                     |      7       |   3    |   ❌   |
|  14  |   média    | Como engenheiro quero visualizar as notas aprovadas em uma norma para entender observações relevantes                               |      7       |   3    |   ❌   |
|  15   |   média    | Como gestor do sistema quero cadastrar novas tags para classificar normas de forma padronizada                                      |      5       |   3    |   ❌   |
|  16   |   média    | Como gestor do sistema quero associar tags às normas para melhorar a organização e busca                                            |      5       |   3    |   ❌   |
|  17   |   média    | Como engenheiro quero pesquisar normas por palavras-chave (tags) para encontrar normas relacionadas a um tema técnico               |      7       |   3    |   ❌   |

## 📝 Critérios de aceitação (em ordem númerica e não de prioridade)<a id="criterios"></a>
**US06 — Solicitar nota para uma norma**
```
- O sistema deve permitir que um engenheiro solicite o registro de uma nota associada a uma norma
- A nota deve possuir conteúdo textual com a observação ou interpretação técnica
- O sistema deve registrar o autor da solicitação da nota
- A nota solicitada deve permanecer com status pendente até avaliação do gestor
```

**US07 — Aprovar ou rejeitar notas**
```
- O sistema deve permitir que o gestor visualize notas solicitadas pelos engenheiros
- O sistema deve permitir aprovar uma nota solicitada
- O sistema deve permitir rejeitar uma nota solicitada
- O sistema deve registrar o status da nota como aprovada ou rejeitada
```

**US08 — Visualizar notas aprovadas**
```
- O sistema deve permitir visualizar as notas aprovadas associadas a uma norma
- Notas rejeitadas ou pendentes não devem aparecer na visualização padrão
- A listagem deve exibir o conteúdo da nota
- A visualização deve ser acessível ao perfil engenheiro
```

**US10 — Cadastrar tags**
```
- O sistema deve permitir cadastrar uma nova tag
- Cada tag deve possuir nome único
- O sistema não deve permitir duplicação de tags
- As tags cadastradas devem ficar disponíveis para associação às normas
```

**US11 — Associar tags às normas**
```
- O sistema deve permitir associar uma ou mais tags a uma norma
- Apenas tags previamente cadastradas podem ser associadas
- Deve ser possível visualizar as tags associadas a uma norma
- Deve ser possível remover uma associação de tag
```

**US12 — Buscar normas por código ou nome**
```
- O sistema deve permitir pesquisar normas pelo código da norma
- O sistema deve permitir pesquisar normas pelo nome ou título
- A busca deve retornar todas as normas que correspondam ao termo pesquisado
- O sistema deve permitir selecionar uma norma a partir do resultado da busca
```

**US13 — Filtrar normas por tags**
```
- O sistema deve permitir selecionar uma ou mais tags como filtro
- A listagem deve exibir apenas normas associadas às tags selecionadas
- O sistema deve permitir combinar mais de uma tag na pesquisa
- Se nenhuma norma corresponder ao filtro, o sistema deve informar ausência de resultados
```

## 📝 Cenários <a id="cenarios"></a>
**US06 — Solicitação de nota**

```gherkin id="v0f4z2"
Cenário: Solicitação de nota em uma norma
Dado que o engenheiro está autenticado no sistema
Quando ele solicita uma nova nota em uma norma
Então o sistema deve registrar a solicitação de nota
```

**US07 — Aprovação de notas**

```gherkin id="q7n9kp"
Cenário: Aprovação ou rejeição de notas pelo gestor
Dado que existe uma nota solicitada
Quando o gestor analisa a solicitação
E aprova ou rejeita a nota
Então o sistema deve atualizar o status da nota
```

**US08 — Visualização de notas aprovadas**

```gherkin id="l2m8xa"
Cenário: Visualização de notas aprovadas em uma norma
Dado que o engenheiro está visualizando uma norma
Quando existem notas aprovadas
Então o sistema deve exibir todas as notas aprovadas
```

**US10 — Cadastro de tags**

```gherkin id="x1c6dn"
Cenário: Cadastro de nova tag pelo gestor
Dado que o gestor está autenticado no sistema
Quando ele cria uma nova tag
Então a tag deve ser salva no sistema
```

**US11 — Associação de tags às normas**

```gherkin id="p9r3sv"
Cenário: Associação de tags a uma norma
Dado que existe uma norma cadastrada
Quando o gestor associa tags à norma
Então as tags devem ser vinculadas à norma
```

**US12 — Busca por código ou nome**

```gherkin id="b5k2qz"
Cenário: Busca de normas por código ou nome
Dado que o engenheiro está autenticado no sistema
Quando ele pesquisa uma norma pelo código ou nome
Então o sistema deve retornar as normas correspondentes
```

**US13 — Busca por tags**

```gherkin id="m8t1wj"
Cenário: Busca de normas por palavras-chave
Dado que o engenheiro está autenticado no sistema
Quando ele pesquisa normas por tags
Então o sistema deve retornar normas relacionadas às tags informadas
```

## ✔️ "Definition of Ready" <a id="dordod"></a>
  - Está escrita no formato de história de usuário
  - Possui critérios de aceitação definidos
  - Possui escopo claro
  - É pequena o suficiente para uma Sprint
  - Dependências estão identificadas
  - Foi compreendida pela equipe

## 🎯 "Definition of Done" 
  - Todos os critérios de aceitação foram atendidos
  - Funcionalidade implementada e funcionando
  - Código versionado seguindo o padrão da equipe
  - Pull Request aprovado
  - Código integrado ao repositório remoto
  - Funcionalidade validada pela equipe

## 👥 EQUIPE <a id="equipe"></a>

|       MEMBRO        |     PAPEL     |                                                                            GITHUB                                                                             |                                                         LINKEDIN                                                          |
| :-----------------: | :-----------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------: |
| Guilherme Alvarenga | Product Owner | <a href="https://github.com/hiGuigo"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href="https://www.linkedin.com/in/guilherme-alvarenga-0834b938a/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
|    Mariana Souza    | Scrum Master |     <a href="https://github.com/nevesmariana"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>      | <a href="#"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
|    Giovana Tarozo   | Desenvolvedor |        <a href="https://github.com/giotrzz"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>         | <a href="https://www.linkedin.com/in/giovana-tarozo-a10922226/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
|     João Souza      | Desenvolvedor |      <a href="https://github.com/joao-luis-0"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>      | <a href="http://www.linkedin.com/in/joão-luis--"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
|   Lucas Pereira    | Desenvolvedor |        <a href="http://github.com/lupesii"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>        | <a href=""><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
|    Rayssa Rizzi     | Desenvolvedor |      <a href="https://github.com/rayssarizzi"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>      | <a href="#"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
|   Robert Marques    | Desenvolvedor |      <a href="https://github.com/Robert-gus"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>       | <a href="#"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |