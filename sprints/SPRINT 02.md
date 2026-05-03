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
  <a href ="#cenarios">Cenários</a> |
  <a href ="#dordod">DoR & DoD</a> |
  <a href ="#equipe"> Equipe</a>
</p>

> Status da Sprint: Concluída 🟩

## 🏅 Meta (US14 e US17)

Implementar mecanismos de colaboração entre engenheiros e gestores, além de permitir a administração de usuários do sistema <a id="meta"></a>

## 📌 Demonstração<a id="demonstracao"></a>

## 📝 Histórias de usuário <a id="historias"></a>

| RANK | PRIORIDADE | USER STORY                                                                                                                          | STORY POINTS | SPRINT | STATUS |
| :--: | :--------: | :---------------------------------------------------------------------------------------------------------------------------------- | :----------: | :----: | :----: |
|  6   |    alta    | Como gestor do sistema quero cadastrar novos usuários no sistema para que eles possam acessar a plataforma conforme suas permissões |      5       |   2    |   🟩   |
|  7   |    alta    | Como gestor do sistema quero desativar usuários para que eles não tenham mais acesso ao sistema                                     |      4       |   2    |   🟩   |
|  8   |   média    | Como gestor do sistema quero visualizar a lista de usuários cadastrados para que eu possa gerenciar quem tem acesso ao sistema      |      4       |   2    |   🟩   |
|  9   |   média    | Como gestor do sistema quero alterar dados ou permissões de um usuário para que eu possa ajustar seu acesso quando necessário       |      5       |   2    |   🟩   |
|  10  |   baixa    | Como engenheiro quero solicitar o cadastro de uma norma para que ela seja adquirida ou cadastrada pela empresa                      |      7       |   2    |   🟩   |

## 📝 Critérios de aceitação (em ordem númerica e não de prioridade)<a id="criterios"></a>

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

## 📝 Cenários <a id="cenarios"></a>
**US09 — Solicitação de cadastro de norma**

```
Cenário: Solicitação de cadastro de nova norma pelo engenheiro
Dado que o engenheiro está autenticado no sistema
Quando ele solicita o cadastro de uma nova norma
Então o sistema deve registrar a solicitação
E enviá-la para análise do gestor
```

**US14 — Cadastro de usuários**

```
Cenário: Cadastro de novo usuário pelo gestor
Dado que o gestor está autenticado no sistema
Quando ele cadastra um novo usuário com permissões
Então o usuário deve ser criado no sistema
```

**US15 — Listagem de usuários**

```
Cenário: Visualização da lista de usuários
Dado que o gestor está autenticado no sistema
Quando ele acessa a lista de usuários
Então o sistema deve exibir todos os usuários cadastrados
```

**US16 — Edição de usuário**

```
Cenário: Alteração de dados ou permissões de usuário
Dado que o gestor está autenticado no sistema
Quando ele altera os dados ou permissões de um usuário
Então o sistema deve atualizar as informações do usuário
```

**US17 — Desativação de usuário**

```
Cenário: Desativação de usuário pelo gestor
Dado que o gestor está autenticado no sistema
Quando ele desativa um usuário
Então o usuário não deve mais conseguir acessar o sistema
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

|       MEMBRO        |     PAPEL     |                                                                        GITHUB                                                                        |                                                                                      LINKEDIN                                                                                       |
| :-----------------: | :-----------: | :--------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Guilherme Alvarenga | Product Owner |   <a href="https://github.com/hiGuigo"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>    | <a href="https://www.linkedin.com/in/guilherme-alvarenga-0834b938a/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
|    Mariana Souza    | Scrum Master  | <a href="https://github.com/nevesmariana"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> |                             <a href="#"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>                              |
|   Giovana Tarozo    | Desenvolvedor |   <a href="https://github.com/giotrzz"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>    |   <a href="https://www.linkedin.com/in/giovana-tarozo-a10922226/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>    |
|     João Souza      | Desenvolvedor | <a href="https://github.com/joao-luis-0"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>  |           <a href="http://www.linkedin.com/in/joão-luis--"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>           |
|    Lucas Pereira    | Desenvolvedor |    <a href="http://github.com/lupesii"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>    |                              <a href=""><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>                              |
|    Rayssa Rizzi     | Desenvolvedor | <a href="https://github.com/rayssarizzi"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>  |                             <a href="#"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>                              |
|   Robert Marques    | Desenvolvedor |  <a href="https://github.com/Robert-gus"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>  |                             <a href="#"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>                              |
