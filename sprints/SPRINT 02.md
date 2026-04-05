# Documentação Sprint 2

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
  <a href ="#dordod">DoR & DoD</a> |
  <a href ="#equipe"> Equipe</a>
</p>

> Status da Sprint: Não iniciada ❌

## 🏅 Meta (US13) 
Permitir organizar normas por meio de tags e disponibilizar mecanismos de busca por código, nome ou palavras-chave <a id="meta"></a>

## 📌 Demonstração<a id="demonstracao"></a>

## 📝 Histórias de usuário <a id="historias"></a>

| RANK | PRIORIDADE | USER STORY                                                                                                                          | STORY POINTS | SPRINT | STATUS |
| :--: | :--------: | :---------------------------------------------------------------------------------------------------------------------------------- | :----------: | :----: | :----: |
|   6  |    alta    | Como engenheiro quero pesquisar normas pelo código ou pelo nome para encontrar rapidamente uma norma específica                     |       6      |    2   |    ❌   |
|   7  |    média   | Como gestor do sistema quero cadastrar novas tags para classificar normas de forma padronizada                                      |       5      |    2   |    ❌   |
|   8  |    média   | Como gestor do sistema quero associar tags às normas para melhorar a organização e busca                                            |       5      |    2   |    ❌   |
|  9  |    média   | Como engenheiro quero pesquisar normas por palavras-chave (tags) para encontrar normas relacionadas a um tema técnico               |       7      |    2   |    ❌   |

## 📝 Critérios de aceitação (em ordem númerica e não de prioridade)<a id="criterios"></a>
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