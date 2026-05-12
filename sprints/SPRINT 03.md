# Documentação Sprint 3

## <p align="center">**Plataforma de Conteúdo Técnico de Normas Aeronáuticas**</p>

<p align="center">
  <img width="200" alt="koitech_logo" src="https://i.imgur.com/YugGoAM.png" />
</p>

<div align="center">
  <strong>KOITECH - AERO</strong>
</div>

<div align="center">

|                                                                                                                                                                                                                                                              |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <a href="#meta">Meta</a> • <a href="#demonstracao">Demonstração</a> • <a href="#historias">Histórias de Usuário</a> • <a href="#criterios">Critérios</a> • <a href="#cenarios">Cenários</a> • <a href="#dordod">DoR & DoD</a> • <a href="#equipe">Equipe</a> |

</div>

> <p align="center"><strong>Status da Sprint:</strong> 🟨 Em andamento</p>

## 🏅 **Meta (US06, US07 e US08)**

Permitir organizar normas por meio de tags e disponibilizar mecanismos de busca por código, nome ou palavras-chave <a id="meta"></a>

<br>

## 📌 **Demonstração**<a id="demonstracao"></a>

### <a href="#">Sprint 3 - Site Koitech - Aero</a>

<br>

## 📝 **Histórias de usuário (em ordem númerica)** <a id="historias"></a>

| RANK | PRIORIDADE | USER STORY                                                                                                            | STORY POINTS | SPRINT | STATUS |
| :--: | :--------: | :-------------------------------------------------------------------------------------------------------------------- | :----------: | :----: | :----: |
|  11  |    alta    | Como engenheiro quero solicitar uma nota para uma norma para registrar observações ou interpretações técnicas         |      8       |   3    |   ❌   |
|  12  |    alta    | Como engenheiro quero pesquisar normas pelo código ou pelo nome para encontrar rapidamente uma norma específica       |      6       |   3    |   ❌   |
|  13  |   média    | Como gestor do sistema quero aprovar ou rejeitar notas solicitadas para controlar o conteúdo exibido no sistema       |      7       |   3    |   ❌   |
|  14  |   média    | Como engenheiro, quero visualizar todas as notas no sistema, para entender observações relevantes                     |      7       |   3    |   ❌   |
|  15  |   média    | Como gestor do sistema quero cadastrar novas tags para classificar normas de forma padronizada                        |      5       |   3    |   ❌   |
|  16  |   média    | Como gestor do sistema quero associar tags às normas para melhorar a organização e busca                              |      5       |   3    |   ❌   |
|  17  |   média    | Como engenheiro quero pesquisar normas por palavras-chave (tags) para encontrar normas relacionadas a um tema técnico |      7       |   3    |   ❌   |

<br>

## 📝 **Critérios de aceitação (em ordem númerica)** <a id="criterios"></a>

**US06 — Solicitar nota para uma norma**

```
 - A rota deve estar implementada e fazendo a requisição corretamente;
 - A tela de solicitação de nota deve possuir os campos: "conteúdo da nota" (textarea), "norma atribuída" (modal com uma lista de normas aprovadas), data da solicitação (campo inativo com a data), solicitante (campo inativo com o nome do usuário);
 - A tela deve estar seguindo o padrão de responsividade;
 - O status da nota deve ser cadastrado como "pendente";
 - Commits realizados dentro da nova branch: feature-solicitacao-notas;
 - O padrão dos commits deve seguir o nome da task, o tipo da tarefa e sua descrição. Exemplo: KOIKOI-123 feat: descrição da atividade feita.
```

**US07 — Visualizar notas**

```
 - As rotas devem estar implementadas e fazendo as requisições corretamente;
 - A tela de listagem deve exibir conforme os filtros: pendente, aprovada, rejeitada ou exibir todas;
 - Cada item (nota) deve possuir informado: nome, status, data de solicitação, data de aprovação/rejeição (se não estiver pendente), qual a norma relacionada e um botão detalhes;
 - O botão detalhes deve exibir um modal com o conteúdo (texto) da nota, quem a solicitou e dois botões: aprovar e rejeitar;
 - Os botões de aprovação não devem aparecer caso a nota já esteja avaliada;
 - Commits realizados dentro da nova branch: feature-listar-notas;
 - O padrão dos commits deve seguir o nome da task, o tipo da tarefa e sua descrição. Exemplo: KOIKOI-123 feat: descrição da atividade feita.
```

**US08 — Aprovar ou rejeitar notas**

```
 - A rota deve estar implementada e fazendo a requisição corretamente;
 - A funcionalidade do botão no modal dentro da listagem de notas deve atender à funcionalidade de aprovar ou rejeitar uma nota;
 - Commits realizados dentro da nova branch: feature-aprovacao-notas;
 - O padrão dos commits deve seguir o nome da task, o tipo da tarefa e sua descrição. Exemplo: KOIKOI-123 feat: descrição da atividade feita.
```

**US10 — Cadastrar tags**

```
 - A rota deve estar implementada e fazendo a requisição corretamente;
 - A tela de cadastro de tag deve possuir o campo de nome e esse deve ser único;
 - O conteúdo do nome deve ser padronizado para "capitalize" antes de ser registrado no banco de dados;
 - Commits realizados dentro da nova branch: feature-cadastrar-tags;
 - O padrão dos commits deve seguir o nome da task, o tipo da tarefa e sua descrição. Exemplo: KOIKOI-123 feat: descrição da atividade feita.
```

**US11 — Associar tags às normas**

```
 - A rota deve estar implementada e fazendo a requisição corretamente;
 - A página de cadastro de norma deve estar atualizada com o novo campo "tags";
 - Deve ser possível adicionar mais de uma tags à norma;
 - A página de detalhes da norma deve estar atualizada com o novo campo "tags" e deve ser possível remover uma tag caso o usuário assim queira;
 - Commits realizados dentro da nova branch: feature-associar-tags;
 - O padrão dos commits deve seguir o nome da task, o tipo da tarefa e sua descrição. Exemplo: KOIKOI-123 feat: descrição da atividade feita.
```

**US12 — Buscar normas por código ou nome**

```
 - A filtragem na tela de pesquisa deve estar implementada corretamente;
 - Commits realizados dentro da nova branch: feature-pesquisar-normas;
 - O padrão dos commits deve seguir o nome da task, o tipo da tarefa e sua descrição. Exemplo: KOIKOI-123 feat: descrição da atividade feita.
```

**US13 — Filtrar normas por tags**

```
 - A filtragem na tela de pesquisa deve estar implementada corretamente;
 - Commits realizados dentro da nova branch: feature-pesquisar-normas;
 - O padrão dos commits deve seguir o nome da task, o tipo da tarefa e sua descrição. Exemplo: KOIKOI-123 feat: descrição da atividade feita.
```

<br>

## 📝 **Cenários** <a id="cenarios"></a>

**US06 — Solicitação de nota**

```
Cenário: Solicitação de nota em uma norma
Dado que o engenheiro está autenticado no sistema
Quando ele solicita uma nova nota em uma norma
Então o sistema deve registrar a solicitação de nota como pendente
```

**US07 — Visualização de notas**

```
Cenário: Visualização de notas cadastradas
Dado que existem notas registradas no sistema
Quando o usuário acessa a listagem de notas
Então o sistema deve exibir as notas conforme os filtros selecionados
```

**US08 — Aprovação de notas**

```
Cenário: Aprovação de uma nota
Dado que existe uma nota pendente no sistema
Quando o gestor aprova ou rejeita a nota
Então o sistema deve atualizar o status da nota corretamente
```

**US10 — Cadastro de tags**

```
Cenário: Cadastro de uma nova tag
Dado que o gestor está autenticado no sistema
Quando ele cadastra uma nova tag
Então o sistema deve registrar a tag com nome único e padronizado
```

**US11 — Associação de tags às normas**

```
Cenário: Associação de tags a uma norma
Dado que existe uma norma cadastrada no sistema
Quando o usuário associa uma ou mais tags à norma
Então o sistema deve vincular corretamente as tags à norma
```

**US12 — Busca por código ou nome**

```
Cenário: Pesquisa de normas por código ou nome
Dado que existem normas cadastradas no sistema
Quando o usuário realiza uma pesquisa por código ou nome
Então o sistema deve exibir as normas correspondentes ao filtro informado
```

**US13 — Busca por tags**

```
Cenário: Filtragem de normas por tags
Dado que existem normas cadastradas com tags associadas
Quando o usuário filtra normas utilizando uma tag
Então o sistema deve exibir apenas as normas relacionadas à tag selecionada
```

<br>

## ✔️ **"Definition of Ready"** <a id="dordod"></a>

- Está escrita no formato de história de usuário
- Possui critérios de aceitação definidos
- Possui escopo claro
- É pequena o suficiente para uma Sprint
- Dependências estão identificadas
- Foi compreendida pela equipe

<br>

## 🎯 **"Definition of Done"**

- Todos os critérios de aceitação foram atendidos
- Funcionalidade implementada e funcionando
- Código versionado seguindo o padrão da equipe
- Pull Request aprovado
- Código integrado ao repositório remoto
- Funcionalidade validada pela equipe

<br>

## 👥 **Equipe** <a id="equipe"></a>

|       MEMBRO        |     PAPEL     |                                                                        GITHUB                                                                        |                                                                                      LINKEDIN                                                                                       |
| :-----------------: | :-----------: | :--------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Guilherme Alvarenga | Product Owner |   <a href="https://github.com/hiGuigo"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>    | <a href="https://www.linkedin.com/in/guilherme-alvarenga-0834b938a/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
|    Mariana Souza    | Scrum Master  | <a href="https://github.com/nevesmariana"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> |                             <a href="#"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>                              |
|   Giovana Tarozo    | Desenvolvedor |   <a href="https://github.com/giotrzz"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>    |   <a href="https://www.linkedin.com/in/giovana-tarozo-a10922226/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>    |
|     João Souza      | Desenvolvedor | <a href="https://github.com/joao-luis-0"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>  |           <a href="http://www.linkedin.com/in/joão-luis--"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>           |
|    Lucas Pereira    | Desenvolvedor |    <a href="http://github.com/lupesii"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>    |                              <a href=""><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>                              |
|    Rayssa Rizzi     | Desenvolvedor | <a href="https://github.com/rayssarizzi"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>  |                             <a href="#"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>                              |
|   Robert Marques    | Desenvolvedor |  <a href="https://github.com/Robert-gus"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>  |                             <a href="#"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>                              |
