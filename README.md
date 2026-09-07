# FUSEX - Acompanhamento de guias FUSEX
<p align="center">
  <img src="Documentos/assets/logo_datasphere.png" width="200"/>
</p>
<p align="center">
    <a href = #sobre>
    <a href ="#desafio"> Desafio</a> |
    <a href ="#solução"> Solução</a> |
    <a href ="#backlog"> Backlog do Produto</a> |   
    <a href ="#sprints"> Cronograma das Sprints</a> |
    <a href ="#estrutura"> Estrutura do Projeto</a> |
    <a href ="#documentacao"> Documentação </a> |
    <a href ="#tecnologias"> Tecnologias</a> |
    <a href ="#equipe"> Equipe </a> |
    

</p>

### Sobre o Projeto <a id="sobre"></a>
O aplicativo da FUSEx é um projeto desenvolvido por alunos do 3º semestre do curso de Banco de Dados da FATEC, em parceria com o Exército Brasileiro (FUSEx), como parte de um Projeto Integrador.
O objetivo da aplicação é gerenciar as guias emitidas para os beneficiários, desde sua criação até as etapas de atendimento, faturamento e aprovação para pagamento. A solução busca reduzir erros, economizar tempo e automatizar tarefas, tornando o processo mais eficiente e organizado.

---

> Status do projeto: Em andamento

---
### 📋 Backlog do Produto <a id="backlog"></a>
<div align="center">
  <table>
    <tr>
      <th> Id </th>
      <th>User Stories</th>
      <th>Prioridade</th>
      <th>Estimativa</th>
    </tr>
    <tr>
      <td align="center"> <b> US001 </b> </td>
      <td> Como clínica/OCS, quero enviar digitalmente o espelho de fatura, para agilizar o recebimento das faturas pelo FUSEx. </td>
      <td align="center"> BAIXA </td>
      <td align="center"> 5 </td>
    </tr>
    <tr>
      <td align="center"> <b> US002 </b> </td>
      <td> Como auditor, quero comparar os valores apresentados na fatura com os valores do contrato, para identificar divergências antes da aprovação. </td>
      <td align="center"> ALTA </td>
      <td align="center"> 13 </td>
    </tr>
    <tr>
      <td align="center"> <b> US003 </b> </td>
      <td> Como emissor de guia, quero registrar a solicitação de exame gerando uma Pré Guia, para que o processo de encaminhamento já comece padronizado. </td>
      <td align="center"> BAIXA </td>
      <td align="center"> 2 </td>
    </tr>
    <tr>
      <td align="center"> <b> US004 </b> </td>
      <td> Como emissor de guia, quero gerar a Guia de Encaminhamento FUSEx no SIRE com os dados coletados no app, para evitar preenchimento manual duplicado. </td>
      <td align="center"> MÉDIA </td>
      <td align="center"> 3 </td>
    </tr>
    <tr>
      <td align="center"> <b> US005 </b> </td>
      <td> Como beneficiário, quero apresentar a guia com QR Code na clínica, para que o atendimento seja validado de forma segura. </td>
      <td align="center"> ALTA </td>
      <td align="center"> 8 </td>
    </tr>
    <tr>
      <td align="center"> <b> US006 </b> </td>
      <td> Como clínica/OCS, quero validar a guia por QR Code no momento do atendimento, para confirmar que o procedimento está autorizado. </td>
      <td align="center"> ALTA </td>
      <td align="center"> 8 </td>
    </tr>
    <tr>
      <td align="center"> <b> US007 </b> </td>
      <td> Como auditor, quero visualizar o histórico completo de cada guia (solicitação, emissão, atendimento, fatura, aprovação), para garantir rastreabilidade do processo. </td>
      <td align="center"> MÉDIA </td>
      <td align="center"> 8 </td>
    </tr>
    <tr>
      <td align="center"> <b> US008 </b> </td>
      <td> Como beneficiário, quero acessar um painel com o status de cada guia (solicitada, emitida, realizada, faturada, aprovada, liquidada), para acompanhar o andamento sem precisar consultar múltiplas fontes. </td>
      <td align="center"> BAIXA </td>
      <td align="center"> 5 </td>
    </tr>
    <tr>
      <td align="center"> <b> US009 </b> </td>
      <td> Como chefe do FUSEx, quero poder visualizar e aprovar a pré-guia, para que a guia definitiva seja emitida com mais rapidez. </td>
      <td align="center"> ALTA </td>
      <td align="center"> 5 </td>
    </tr>
  </table>
</div>
---


##### Conteúdo dividido por sprint:
- Backlog da sprint
- Critérios de aceite
- Rascunhos das telas

---
### 💻 Tecnologias <a id="tecnologias"></a>

- **Linguagem:** Java <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="20" height="20" alt="Java"/>
- **Framework:** Spring Boot <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" width="20" height="20" alt="Spring Boot"/>
- **Build & Dependências:** Maven <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/maven/maven-original.svg" width="20" height="20" alt="Maven"/>
- **Front-end:** Vue.js <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original.svg" width="20" height="20" alt="Vue.js"/>
- **Banco de Dados:** PostgreSQL <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="20" height="20" alt="PostgreSQL"/>
- **Containerização:** Docker <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="20" height="20" alt="Docker"/>
- **Versionamento:** Git <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="20" height="20" alt="Git"/>---

### 👥 Equipe <a id="equipe"></a>
<div align="center">
  <table>
    <tr>
      <th> </th>
      <th>Membro</th>
      <th>Função</th>
      <th>Github</th>
      <th>Linkedin</th>
    </tr>
    <tr>
      <th> <img src="/Documentos/assets/team_pics/vinicius.png" height=120px> </th>
      <td>Rafael Rodrigues</td>
      <td>Product Owner</td>
      <td><a href="https://github.com/vncssd"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/vncssd?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
     <tr>
      <th> <img src="/Documentos/assets/team_pics/matheus.png" height=120px> </th>
      <td>Matheus Quirino</td>
      <td>Scrum Master</td>
      <td><a href="https://github.com/matquirin0"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/matheus-pquirino/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <th> <img src="/Documentos/assets/team_pics/carolina.png" height=120px> </th>
      <td>Carolina Medeiros</td>
      <td>Desenvolvedora</td>
      <td><a href="https://github.com/mcarolinamedeiros"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://br.linkedin.com/in/mcarolinamedeiros"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr> 
     <tr>
      <th> <img src="/Documentos/assets/team_pics/daiane.png" height=120px> </th>
      <td>Daiane Moura</td>
      <td>Desenvolvedora</td>
      <td><a href="https://github.com/mouradaiane"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/daiane-moura-189987106/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <th> <img src="/Documentos/assets/team_pics/lucas.png" height=120px> </th>
      <td>Lucas Nathan</td>
      <td>Desenvolvedor</td>
      <td><a href="https://github.com/Consolucas"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/lucasconsolo/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <th> <img src="/Documentos/assets/team_pics/vinicius.png" height=120px> </th>
      <td>Vinicius Santos</td>
      <td>Desenvolvedor</td>
      <td><a href="https://github.com/vncssd"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/vncssd?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
 </table>
</div>
