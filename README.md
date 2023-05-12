### <p align="center">Aprendizado por Projeto Integrador </center>
# <p align="center"> InoDevs </center> 
<hr>

<p align="center">
  <a href ="#dart-prosposta"> Proposta </a>  • 
  <a href ="#pushpin-requisitos"> Requisitos </a>  • 
  <a href ="#calendar-planejamento"> Planejamento </a>  • 
  <a href ="#iphone-front-end-mobile"> Front-end Mobile </a>  •
  <a href ="#gear-back-end"> Back-end </a>  • 
  <a href ="#book-user-stories"> User Stories </a>  •  
  <a href ="#computer-wireframe"> Wireframe</a>  • 
  <a href ="#rocket-tecnologias"> Tecnologias </a>  •  
  <a href ="#mortar_board-dev-team"> Dev Team </a> 
</p>
<hr>


## :dart: Prosposta
<p align="justify">
Desenvolver uma aplicação híbrida/responsiva, que funcione como Serviço de Atendimento ao Cliente (SAC), onde ele poderá criar ROs, verificar as solicitações criadas, entrar em contato via chat com algum administrador (programador da equipe). 

<br>

## :pushpin: Requisitos

**Requisitos Funcionais**
1. &nbsp; Área de Cliente e áreade Administrador, com controles de acesso (autenticação/autorização);
2. &nbsp; Opções de criar e acompanhar ROs;
3. &nbsp; Comunicação com os administradores do sistema via chat;
4. &nbsp; Atualização do Status das ROs em tempo real;
5. &nbsp; Envio de e-mail com notificações para o cliente e administradores;
6. &nbsp; Relatórios/gráficos de sumarização das ROs.

**Requisitos Não Funcionais**
1. &nbsp; Documentação com mapeamento das regras de negócio do cliente;
2. &nbsp; JavaScript;
3. &nbsp; TypeScript;
4. &nbsp; React;
5. &nbsp; ReactNative;
6. &nbsp; MongoDB;
7. &nbsp; Python. <br>

## :calendar: Planejamento

* [x] __Kick-off__ - 28/02/2023
* [X] [__Sprint 1__](https://github.com/inodevs-5/Reportify_Doc/tree/main/Sprint-1) - 13/03/2023 a 12/04/2023  
* [X] [__Sprint 2__](https://github.com/inodevs-5/Reportify_Doc/tree/main/Sprint-2) - 03/04/2023 a 23/04/2023  
* [X] [__Sprint 3__](https://github.com/inodevs-5/Reportify_Doc/tree/main/Sprint-3) - 24/04/2023 a 14/05/2023   
* [ ] [__Sprint 4__]() - 15/05/2023 a 04/06/2023   
* [ ] __Feira de Soluções__ - 13/06/2022 a 14/06/2023 
>_Acesse a pasta referente a entrega da sprint clicando no link acima_  <br>

## :iphone: Front-end Mobile
* [Clique aqui para acessar o código Front-end do Mobile](https://github.com/inodevs-5/Reportify_Frontend_App)

## :gear: Back-end
* [Clique aqui para acessar o código Back-end ](https://github.com/inodevs-5/Reportify_Backend)

## :book: User Stories

<div id="table_use_cases" align="center" width="400">
  <table align="justify">
    <tr>
      <th>User Story id</th>
      <th>Como um (ator)</th>
      <th>Eu quero (ação)</th>
      <th>Para que seja possível (funcionalidade)</th>
      <th>Prioridade</th>
    </tr>
    <tr>
      <td>1</td>
      <td>Administrador</td>
      <td>Acessar as funcionalidades destinadas ao administrador do sistema</td>
      <td>Cadastrar novos usários, acompanhar todos os Registros de Ocorrência criados no aplicativo, enviar mensagem a outros usuários em caso de dúvidas por meio do chat após realizar o login no app.</td>
      <td>M</td>
    </tr>
     <tr>
      <td>2</td>
      <td>Cliente</td>
      <td>Ter acesso a uma área com as funcionalidades destinadas somente aos clientes</td>
      <td>Realizar a criação de Registros de Ocorrências, acompanha-los durante seu tratamento e entrar em contato com o desenvolvedor da IACIT em caso de dúvidas após realizar login no aplicativo.</td>
      <td>M</td>
    </tr>
     <tr>
      <td>3</td>
      <td>Usuário</td>
      <td>Criar novos Registros de Ocorrência  e acompanhar todas as atualizações de status desde o momento de sua criação até sua conclusão</td>
      <td>Evitar ruídos de comunicação e a solução dos possíveis problemas que possam ocorrer nas empresas clientes que utilizam os produtos/serviços oferecidos pela IACIT.</td>
      <td>M</td>
    </tr>
     <tr>
      <td>4</td>
      <td>Cliente</td>
      <td>Poder me comunicar com o administrador do sistema via chat</td>
      <td>Esclarecer possíveis dúvidas que venham a surgir durante o tratamento do Registro de Ocorrência.</td>
      <td>S</td>
    </tr>
     <tr>
      <td>5</td>
      <td>Usuário</td>
      <td>Receber notificações via e-mail e no app sobre mudanças de status dos Registros de Ocorrências relacionados a mim</td>
      <td>Acompanhar em tempo real as atualizações de status de um RO.</td>
      <td>M</td>
    </tr>
     <tr>
      <td>6</td>
      <td>Usuário</td>
      <td>Receber notificações do aplicativo também em meu e-mail</td>
      <td>Acompanhar todas as atualizações realizadas no aplicativo, tanto por parte dos clientes da IACIT, quanto pelos administradores do app.</td>
      <td>S</td>
    </tr>
     <tr>
      <td>7</td>
      <td>Administrador</td>
      <td>Ter acesso a relatórios e gráficos com a sumarização dos Registros de Ocorrência</td>
      <td>Acompanhar as médias de ROs criados, em tratamento, solucionados entre outras métricas.</td>
      <td>S</td>
    </tr>
    <tr>
      <td>8</td>
      <td>Usuário</td>
      <td>Receber meus dados cadastrados no sistema no ato da criação da conta</td>
      <td>Ter uma cópia dos dados salvos na base de dados.</td>
      <td>C</td>
    </tr>
    <tr>
      <td>9</td>
      <td>Usuário</td>
      <td>Ter a opção de solicitar a edição dos meus dados ao administrador do sistema</td>
      <td>Corrigir dados que eventualmente possam estar errados ou atualizar alguma informação.</td>
      <td>S</td>
    </tr>
    <tr>
      <td>10</td>
      <td>Usuários</td>
      <td>Poder solicitar a exclusão do meu cadastro do aplicativo de acordo com a Lei Geral de Proteção de Dados</td>
      <td>Eliminar qualquer dado sensível que me pertença da base de dados do aplicativo.</td>
      <td>M</td>
    </tr>
    <tr>
      <td>11</td>
      <td>Administrador</td>
      <td>Uma funcionalidade de backup automatizado do banco de dados</td>
      <td>Garantir a segurança e a integridade dos dados armazenados, de forma a minimizar a perda de dados em caso de falhas ou incidentes.</td>
      <td>M</td>
    </tr>
  </table>
</div>

### A priorização das user stories foi feita com basea no método MoSCoW:

- Must Have (M): Funcionalidades essenciais para o funcionamento básico do aplicativo.
- Should Have (S): Funcionalidades importantes, mas que não são críticas para o funcionamento básico do aplicativo.
- Could Have (C): Funcionalidades desejáveis, mas que podem ser adiadas ou excluídas sem comprometer o funcionamento básico do aplicativo.
- Won't Have (W): Funcionalidades que não são consideradas importantes para esta versão do aplicativo e podem ser incluídas em versões futuras.
As user stories foram priorizadas de acordo com a importância das funcionalidades que elas representam, considerando a perspectiva dos usuários e a necessidade de atender às expectativas do negócio.

## :computer: Wireframe

* [Clique aqui!](https://www.figma.com/file/GvwC1jGe64qvfg9INSTXQY/iacit?node-id=0%3A1&t=KOjui4GE)  
> _Acesse o link acima para visualizar o protótipo no Figma._ 


 ## :rocket: Tecnologias

#### **Front-end**  
 ![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)

#### **Back-end**  
 ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

#### **Data-base**  
 ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
 
<br>

## :mortar_board: Dev Team

| Aluno(a)         | Função           | GitHub                                                         | LinkedIn                                              |
| ---------------- | ---------------- | -------------------------------------------------------------- | ----------------------------------------------------- |
|__Anderson Lira__  | *Developer Team* | [![](https://bit.ly/3f9Xo0P)](https://github.com/alira1984)  | [![](https://bit.ly/2P1ZogM)](https://www.linkedin.com/in/anderson-lira-ads) |
|__Debora Conceição Faria__  | *Developer Team*  | [![](https://bit.ly/3f9Xo0P)](https://github.com/deborafaria01)| [![](https://bit.ly/2P1ZogM)](https://bit.ly/2QwcT8R) |
|__Gustavo Kenji Ando__  | *Developer Team* | [![](https://bit.ly/3f9Xo0P)](https://github.com/GustavoAndo)  | [![](https://bit.ly/2P1ZogM)](https://www.linkedin.com/in/gustavo-ando-054414209/) |
|__Júlia Maria Santos Barroso__  | *Developer Team* | [![](https://bit.ly/3f9Xo0P)](https://github.com/jumajubs)  | [![](https://bit.ly/2P1ZogM)](https://www.linkedin.com/in/j%C3%BAlia-maria-santos-850739188/) |
|__Kauã Gustavo Rodrigues Reno__  |  *Developer Team* | [![](https://bit.ly/3f9Xo0P)](https://github.com/Kaua-Reno)  | [![](https://bit.ly/2P1ZogM)](https://www.linkedin.com/in/kau%C3%A3-gustavo-r-reno-6a3142205/) |
|__Luís Henrique Ferreira Souza__  | *Developer Team*  | [![](https://bit.ly/3f9Xo0P)](https://github.com/Luisttine)  | [![](https://bit.ly/2P1ZogM)](https://www.linkedin.com/in/lu%C3%ADs-souza/) |
|__Maria Eduarda Macedo Braga__  | *Scrum Master* | [![](https://bit.ly/3f9Xo0P)](https://github.com/madu-braga)  | [![](https://bit.ly/2P1ZogM)](https://www.linkedin.com/in/maria-eduarda-macedo-braga-4663bb208/) |
|__Richard Rafael Sacramento Soares__  | *Developer Team* | [![](https://bit.ly/3f9Xo0P)](https://github.com/Richardrafael)  | [![](https://bit.ly/2P1ZogM)](https://www.linkedin.com/in/richardsoaress) |
|__Vitória Cristina Saturnino de Moura__  | *Product Owner* | [![](https://bit.ly/3f9Xo0P)](https://github.com/vitoriasaturnino)  | [![](https://bit.ly/2P1ZogM)](https://www.linkedin.com/in/vit%C3%B3ria-cristina-saturnino-de-moura-6393391b0/) |


<h1 align="center"></h1>

##### <p align="center"><img src="https://cdn.discordapp.com/attachments/826526043917647912/883363052425195560/faTec.png" width="20" height="20" /> Projeto Integrador 2023 - Fatec São José dos Campos </center>
