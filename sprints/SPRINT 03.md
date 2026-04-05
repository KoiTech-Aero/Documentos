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
  <a href ="#dordod">DoR & DoD</a> |
  <a href ="#equipe"> Equipe</a>
</p>

> Status da Sprint: Não iniciada ❌

## 🏅 Meta (US07 e US15)
Implementar mecanismos de colaboração entre engenheiros e gestores, além de permitir a administração de usuários do sistema <a id="meta"></a>

## 📌 Demonstração<a id="demonstracao"></a>

## 📝 Histórias de usuário <a id="historias"></a>

| RANK | PRIORIDADE | USER STORY                                                                                                                          | STORY POINTS | SPRINT | STATUS |
| :--: | :--------: | :---------------------------------------------------------------------------------------------------------------------------------- | :----------: | :----: | :----: |
|  10  |    alta    | Como engenheiro quero solicitar uma nota para uma norma para registrar observações ou interpretações técnicas                       |       8      |    3   |    ❌   |
|  11  |    alta    | Como gestor do sistema quero cadastrar novos usuários no sistema para que eles possam acessar a plataforma conforme suas permissões |       5      |    3   |    ❌   |
|  12  |    média   | Como gestor do sistema quero aprovar ou rejeitar notas solicitadas para controlar o conteúdo exibido no sistema                     |       7      |    3   |    ❌   |
|  13  |    média   | Como engenheiro quero visualizar as notas aprovadas em uma norma para entender observações relevantes                               |       7      |    3   |    ❌   |
|  14  |    baixa   | Como engenheiro quero solicitar o cadastro de uma norma para que ela seja adquirida ou cadastrada pela empresa                      |       7      |    3   |    ❌   |
|  15  |    baixa   | Como gestor do sistema quero visualizar a lista de usuários cadastrados para que eu possa gerenciar quem tem acesso ao sistema      |       4      |    3   |    ❌   |
|  16  |    baixa   | Como gestor do sistema quero alterar dados ou permissões de um usuário para que eu possa ajustar seu acesso quando necessário       |       5      |    3   |    ❌   |
|  17  |    baixa   | Como gestor do sistema quero desativar usuários para que eles não tenham mais acesso ao sistema                                     |       4      |    3   |    ❌   |

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

**US09 — Solicitar cadastro de norma**
```
- O sistema deve permitir que um engenheiro solicite o cadastro de uma nova norma
- A solicitação deve conter pelo menos o código ou o título da norma
- O sistema deve registrar o autor da solicitação
- A solicitação deve ficar disponível para visualização do gestor do sistema
```

**US14 — Cadastrar usuários**
```
- O sistema deve permitir cadastrar novo usuário informando nome e identificação
- O sistema deve permitir definir perfil do usuário (engenheiro ou gestor)
- O sistema não deve permitir duplicação de usuários com o mesmo identificador
- O usuário cadastrado deve aparecer na lista de usuários
```

**US15 — Visualizar usuários**
```
- O sistema deve permitir visualizar todos os usuários cadastrados
- A listagem deve exibir nome e perfil do usuário
- A listagem deve ser acessível apenas ao gestor do sistema
- Usuários desativados devem continuar visíveis na listagem para fins de histórico
```

**US16 — Alterar dados ou permissões de usuário**
```
- O sistema deve permitir editar dados de um usuário existente
- O sistema deve permitir alterar o perfil ou permissões do usuário
- As alterações devem ser salvas no sistema
- As alterações devem ser refletidas na lista de usuários
```

**US17 — Desativar usuários**
```
- O sistema deve permitir desativar um usuário existente
- Usuários desativados não devem conseguir acessar o sistema
- O sistema deve manter registro do usuário desativado para histórico
- O sistema deve permitir visualizar que o usuário está com status desativado
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