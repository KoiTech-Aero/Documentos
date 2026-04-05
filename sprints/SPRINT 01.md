# Documentação Sprint 1

## Plataforma de Conteúdo Técnico de Normas Aeronáuticas

<p align="center">
  <img width="200" alt="koitech_logo" src="https://i.imgur.com/YugGoAM.png" />
</p>

<h2 align="center">
  <b>KOITECH</b>
</h2>

<p align="center">
  <a href ="#meta"> Meta</a> |
  <a href ="#demonstracao">Demonstração</a>  |
  <a href ="#historias"> Histórias de usuário</a>  |   
  <a href ="#criterios">Critérios</a> |
  <a href ="#dordod">DoR & DoD</a> |
  <a href ="#equipe"> Equipe</a>
</p>

> Status da Sprint: Em andamento 🟨

## 🏅 Meta (US01 e US03)
Estabelecer a estrutura inicial do sistema, permitindo o cadastro de normas, registro de versões, inclusão de escopo e visualização de referências entre normas <a id="meta"></a>

## 📌 Demonstração<a id="demonstracao"></a>

## 📝 Histórias de usuário <a id="historias"></a>

| RANK | PRIORIDADE | USER STORY                                                                                                                          | STORY POINTS | SPRINT | STATUS |
| :--: | :--------: | :---------------------------------------------------------------------------------------------------------------------------------- | :----------: | :----: | :----: |
|  1   |    alta    | Como gestor do sistema quero cadastrar uma nova norma para que ela esteja disponível no sistema                                     |      7       |   1    |   🟩   |
|  2   |    alta    | Como engenheiro quero listar normas ativas para saber quais são válidas para uso                                                    |      7       |   1    |   🟩   |
|  3   |   média    | Como gestor do sistema quero registrar versões de uma norma para manter histórico e rastreabilidade                                 |      8       |   1    |   🟩   |
|  4   |   baixa    | Como gestor do sistema quero associar uma norma a outras normas referenciadas para representar as dependências entre normas         |      5       |   1    |   🟩   |
|  5   |   baixa    | Como engenheiro quero visualizar quais normas são referenciadas por uma norma para entender suas dependências técnicas              |      7       |   1    |   🟩   |

## 📝 Critérios de aceitação (em ordem númerica e não de prioridade)<a id="criterios"></a>

**US01 — Cadastrar norma**
```
- O sistema deve permitir cadastrar uma norma informando código e título
- O sistema deve permitir registrar a área técnica da norma
- O sistema deve registrar automaticamente a data de cadastro da norma
- O sistema deve permitir cadastrar o escopo da norma
- O sistema não deve permitir cadastrar duas normas com o mesmo código
```

**US02 — Registrar versões de norma**
```
- O sistema deve permitir adicionar uma nova versão a uma norma existente
- Cada versão deve possuir identificação de versão
- O sistema deve manter histórico das versões registradas
- O sistema deve permitir visualizar todas as versões de uma norma
- O sistema deve indicar qual versão é a atualmente ativa
```

**US03 — Listar normas ativas**
```
- O sistema deve permitir listar todas as normas ativas
- Normas desativadas ou obsoletas não devem aparecer na listagem padrão
- A listagem deve exibir código e título da norma
- A listagem deve ser acessível ao perfil engenheiro
```

**US04 — Associar normas referenciadas**
```
- O sistema deve permitir associar uma norma a outras normas já cadastradas
- A associação deve indicar qual norma referencia a outra
- Uma norma pode possuir múltiplas normas referenciadas
- O sistema deve permitir visualizar todas as referências associadas a uma norma
- O sistema deve permitir remover uma associação de referência
```

**US05 — Visualizar normas referenciadas**
```
- O sistema deve permitir visualizar as normas referenciadas por uma norma
- A listagem deve exibir código e título das normas referenciadas
- O sistema deve permitir acessar os detalhes de uma norma referenciada
- A visualização deve ser acessível ao perfil engenheiro
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