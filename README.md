<br id="topo">

<img src="Images/capa-nova.png">

<p align="center">
    <a href="#objetivo">Objetivo</a> |  
    <a href="#relatório">Relatórios</a> | 
    <a href="#projeto">Backlog</a> |
    <a href="#tecnologias">Tecnologias</a> | 
    <a href="#commits">Commits</a> |
    <a href="#branches">Branches</a> |
    <a href="#equipe">Equipe</a> 
</p>

<span id="objetivo">

## 🎯 Objetivo

<p align="justify">
  Na indústria petrolífera e em embarcações de exploração de petróleo existem locais de acesso restrito denominados Red Zone. Por segurança, nestas Red Zones deve haver o monitoramento da quantidade de acessos, que é feito atualmente por meio de câmeras nos locais. Essas imagens são monitoradas por guardas e todos os registros de entrada e saída desses locais são lançados manualmente em planilhas.
  <br>
  <br>
  Por ser um trabalho manual, como dito anteriormente, as anotações estão suscetíveis a falha humana e a geração de relatórios acaba sendo trabalhosa. Por esse motivo, a Altave Intelligent Monitoring, empresa parceira, propôs o desenvolvimento de um sistema automático para contabilização do número de pessoas que entram e saem de cada Red Zone. Importante lembrar ainda que a câmera utilizada para o monitoramento desses locais cobre todos os pontos de entrada e saída, mas pode não alcançar toda a área da Red Zone.
  <br>
  <br>
  Diante desse contexto, o sistema deverá fornecer uma interface que possibilite ao usuário visualizar a quantidade pessoas em tempo real no local, bem como consultar a movimentação naquela região em determinado período de tempo a ser selecionado pelo usuário. Além disso, o sistema poderá monitorar diversas Red Zones em cada departamento, portanto, será necessário que o acesso seja restrito a cada guarda de cada departamento, de modo que apenas o gerente de segurança terá acesso aos dados de todos os locais.
</p>

<span id="relatório">
 
 ## :clipboard: Relatórios
Na tabela abaixo é possível visualizar os resultados de cada Sprint clicando em "Ver relatório". 
    
| Sprint | Entrega | Status | Relatório |
|:-----:|:----------:|:---------:|:---------:|
| 01 | 14/04/2024 |	✅ | [Ver relatório](https://github.com/peonia-api/API_6_Semestre/tree/main/Docs/Sprint-01) |
| 02 | 05/05/2024 |	⏳ | [Ver relatório](https://github.com/peonia-api/API_6_Semestre/tree/main/Docs/Sprint-02) |
| 03 | 26/05/2024 |	⏳ | [Em breve]  |
| 04 | 16/06/2024 |	⏳ | [Em breve]  |


→ [Voltar ao topo](#topo)

<span id="projeto">
    
 ## 📌 Backlog do Produto
 
<div align="center">
    <br>
      <img src="Images/Backlog do Produto.png">
    <br>
</div>

<br>

- Requisito Funcional #1 (RF1): Desenvolver uma interface web intuitiva para visualização dos registros em forma de relatórios;
- Requisito Funcional #2 (RF2): Permitir exportação de relatórios contendo os registros do monitoramento realizado;
- Requisito Funcional #3 (RF3): Implementar modelo de machine learning para automatizar o monitoramento das red zones;
- Requisito Funcional #4 (RF4): Implementar método de autenticação de usuários;
- Requisito Funcional #5 (RF5): Criar seção para gestão de usuários;
- Requisito Funcional #6 (RF6): Permitir a inclusão e exclusão de usuários no sistema;
- Requisito Funcional #7 (RF7): Criar seção para gestão de red zones, permitindo a inclusão e exclusão de red zones do sistema;
- Requisito Funcional #8 (RF8): Desenvolver um dashboard com indicadores por períodos;
- Requisito Funcional #9 (RF9): Permitir que o usuário aplique filtros por períodos para análise dos dados.

    
→ [Voltar ao topo](#topo)  

<span id="tecnologias">

## 🛠️ Tecnologias

Foram usadas as seguintes ferramentas, linguagens e tecnologias para a execução do projeto:

- [Git](https://git-scm.com): Versionamento de código
- [GitHub](https://github.com/): Armazenamento de código
- [Teams](https://teams.microsoft.com): Comunicação interna do grupo
- [Slack](https://slack.com/intl/pt-br): Comunicação com o cliente
- [DevOps](https://azure.microsoft.com/pt-br/products/devops): Planejamento e gestão do projeto
- [Docker](https://docs.docker.com/): Integração entre Front-End e Back-End
- [MongoDB](https://www.mongodb.com/pt-br): Banco de dados NoSQL
- [Python](https://www.python.org/): Automação com inteligência artificial
- [Java](https://www.java.com/pt-BR/): Aplicação de lógica de programação no back-end
- [Spring](https://spring.io/): Framework de desenvolvimento de aplicações Java 
- [Vue](https://vuejs.org/): Framework para a construção de interfaces web
- [Typescript](https://www.typescriptlang.org/): Linguagem de programação aplicada para front-end

→ [Voltar ao topo](#topo)    

<span id="commits">

## 🗂️ Padronização de Commits
<p align="justify">
    No início da primeira sprint, foi estabelecido um padrão para as mensagens de commit, o qual segue a seguinte estrutura:
    
- `<Ação>`: Representa a ação realizada, como "Add" para adições de novos recursos, "Fix" para correções de bugs, "Update" para atualizações de funcionalidades existentes, etc.
- `<Descrição>`: Fornece uma breve descrição do que foi alterado ou adicionado.

Exemplos de mensagens de commit seguindo este padrão:

- `adding images and technologies`: Adição de imagens e tecnologias.
- `removed unused imports`: Remoção de importações não utilizadas.
- `fixed some error with mongoDB`: Correção de erro relacionado ao MongoDB.
<br>
    Ao final da sprint, foi convencionado que seria adotada outra forma de padronização, já amplamente utilizada na área de desenvolvimento de software, o <i>conventional commit</i>. Esta nova abordagem foi implementada para organizar o repositório em que o projeto foi armazenado, tornando-o mais acessível. O conventional commits padroniza todas as alterações realizadas, permitindo que qualquer pessoa que consulte o histórico de commits deste projeto seja capaz de identificar facilmente o tipo de alteração feita no código da aplicação em cada commit.
    <br>
    <br>
    Esse tipo de convenção divide a mensagem de commit em duas partes fundamentais: o tipo de commit e a descrição do que foi incluído, alterado ou excluído. Por tipo de commit é possível entender se foi feita a correção de um bug (fix), se foi excluída ou implementada uma nova feature (feat), se foi adicionada alguma documentação (docs), entre outros. Por fim, a descrição contém um breve resumo sobre o que foi modificado.
    <br>
    <br>
    Seguem alguns exemplos da padronização adotada:
    <br>
</p>

```feat: add user management section```

```chore: modify .gitignore```

```docs: update sprint backlog```

<br>

Repositório de referência: [Conventional Commits](https://gist.github.com/qoomon/5dfcdf8eec66a051ecd85625518cfd13)

<br>

→ [Voltar ao topo](#topo) 

<span id="branches">

## ⚙️ Estratégia de Branches
<p align="justify">
    Para a primeira sprint, seguimos uma estratégia de nomenclatura de branches baseada em tarefas ou funcionalidades. Isso significa que cada branch é nomeada de forma descritiva para indicar a tarefa ou funcionalidade em que está trabalhando.
<br>
    <p>Exemplos da estratégia adotada:</p>
    
### Repositório [IA](https://github.com/peonia-api/API_6_Semestre_IA)
- **dataset:** Esta branch está focada na organização do dataset utilizado no desenvolvimento da IA.
- **ia:** Esta branch está dedicada ao treinamento do modelo de IA.
- **camera:** Esta branch se concentra no desenvolvimento da funcionalidade de identificação de pessoas por meio de câmeras
    
### Repositório [Vue](https://github.com/peonia-api/API_6_Semestre_Vue)
- **Ligacao:** Esta branch está relacionada à implementação da funcionalidade de ligação, entre o back-end com o front-end, dentro do componente Vue.
- **relatorio:** Esta branch está sendo usada para implementar a tela de relatório na aplicação Vue.
<hr>
A partir da segunda sprint, decidimos alinhar a estratégia de nomenclatura das branches com o padrão de commits adotado. Portanto, as novas branches seguirão o mesmo padrão de mensagens de commit.
<br>
    <p>Exemplos:</p>
    
```feature/branch-name```

```bugfix/branch-name```

```test/branch-name```

</p>

→ [Voltar ao topo](#topo)  
    
<span id="equipe">

## 👥 Equipe

|Função|Nome|GitHub|LinkedIn|
| -------- |-------- |-------- |-------- |
| Scrum Master |Ana Carolina das Neves|<a href="https://github.com/AnaCarolinaNeves" target="_blanck"><img src = "https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank"></a> |<a href="https://www.linkedin.com/in/ana-carolina-neves-36aa68207/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>|
| Product Owner |Larissa Aparecida Diniz Silva|<a href="https://github.com/laaridiniz" target="_blanck"><img src = "https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank"></a> |<a href="https://www.linkedin.com/in/larissa-diniz-dev" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>|
| Developer |Ana Paula Santos de Oliveira|<a href="https://github.com/AnaPaulaSOliveira" target="_blanck"><img src = "https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank"></a>|<a href="https://www.linkedin.com/in/ana-paula-santos-de-oliveira-237a401ab/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>|
| Developer |Diego Batista da Silva|<a href="https://github.com/diiegobsilva" target="_blanck"><img src = "https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank"></a>|<a href="https://www.linkedin.com/in/diegobatista1/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>|
| Developer |Jeniffer Cristina Freitas Ramos|<a href="https://github.com/Jennyads" target="_blanck"><img src = "https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank"></a>|<a href="https://www.linkedin.com/in/jeniffer-cristina-65787b205/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>|
| Developer |Mateus Henrique Lima da Silva|<a href="https://github.com/mateushlsilva" target="_blanck"><img src = "https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank"></a> |<a href="https://www.linkedin.com/in/mateus-silva-80232a222/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>|
| Developer |Wallace Marinho de Souza Silva|<a href="https://github.com/WallaceMarinho" target="_blanck"><img src = "https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank"></a> |<a href="https://www.linkedin.com/in/wallace-marinho/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>|

→ [Voltar ao topo](#topo)   

<h5 align="center"> Aprendizagem por Projetos Integrados - Faculdade de Tecnologia de São José dos Campos - Prof. Jessen Vidal </h5>
