<h1 align="center">Grupo 8 - Trabalho de Projeto Integrador</h1>

<p>Grupo conposto por:</p>

    - DAVID NECKEL DOS SANTOS
    - HENRIQUE GRIGOLETTI SANTOS
    - HENRIQUE LUCAS LOPES
    - IGO MARCOS DA SILVA
    - LOUYSE CHRISTINE ARAUJO CARVALHO DA SILVA
    - MATHEUS FERNANDES DORTA
    - RODRIGO ESTABEL BOQUER

<p align="center" >Nome da escola: <b> COLÉGIO FUTURO BRILHANTE</b></p>

<h2 > Introdução </h2>
<p>Nesta segunda fase do projeto, o objetivo foi a criação de um protótipo de sistema de cadastro, tendo como base os diagramas de caso de uso e o diagrama de classes que foram desenvolvidos na primeira etapa do trabalho. Para realizar esta etapa, utilizamos a ferramenta Figma, uma aplicação web amplamente utilizada para o design de interfaces. O projeto desenvolvido tem como objetivo apresentar o layout e demonstrar como algumas funcionalidades do projeto que devem ser desenvolvidas, tornando-as mais compreensíveis por meio de uma interface de usuário amigável. Isso complementa e aprofunda as informações fornecidas na primeira parte do trabalho, fornecendo uma visualização prática e interativa do sistema em desenvolvimento. Este processo visa tornar mais acessível e tangível as funcionalidades e a aparência do sistema, proporcionando uma compreensão mais clara e facilitada para os envolvidos no projeto, incluindo os desenvolvedores, os usuários finais</p>
</br>

<p ><b> PROTOTIPOS : </b></p>
 <a href="https://www.figma.com/file/Trb0ehs1cwYXuRedZLfJTd/PROJETO-INTEGRADOR---ESCOLA?type=design&node-id=0%3A1&mode=design&t=aClYvUOCDbm7kTYe-1">FIGMA TELAS</a>
 </br>
 <a href="https://www.figma.com/file/Trb0ehs1cwYXuRedZLfJTd/PROJETO-INTEGRADOR---ESCOLA?type=design&node-id=0%3A1&mode=design&t=aClYvUOCDbm7kTYe-1](https://www.figma.com/proto/Trb0ehs1cwYXuRedZLfJTd/PROJETO-INTEGRADOR---ESCOLA?type=design&node-id=56-7&t=aClYvUOCDbm7kTYe-0&scaling=scale-down&page-id=0%3A1&starting-point-node-id=56%3A7&show-proto-sidebar=1)https://www.figma.com/proto/Trb0ehs1cwYXuRedZLfJTd/PROJETO-INTEGRADOR---ESCOLA?type=design&node-id=56-7&t=aClYvUOCDbm7kTYe-0&scaling=scale-down&page-id=0%3A1&starting-point-node-id=56%3A7&show-proto-sidebar=1](https://www.figma.com/proto/Trb0ehs1cwYXuRedZLfJTd/PROJETO-INTEGRADOR-ESCOLA?type=design&node-id=0-1&t=aClYvUOCDbm7kTYe-0&scaling=scale-down&starting-point-node-id=56%3A7&show-proto-sidebar=1)https://www.figma.com/proto/Trb0ehs1cwYXuRedZLfJTd/PROJETO-INTEGRADOR-ESCOLA?type=design&node-id=0-1&t=aClYvUOCDbm7kTYe-0&scaling=scale-down&starting-point-node-id=56%3A7&show-proto-sidebar=1](https://www.figma.com/proto/Trb0ehs1cwYXuRedZLfJTd/PROJETO-INTEGRADOR---ESCOLA?type=design&node-id=56-7&t=EMU2ZT2LlXvX7Lf3-0&scaling=scale-down&page-id=0%3A1&starting-point-node-id=56%3A7&show-proto-sidebar=1)https://www.figma.com/proto/Trb0ehs1cwYXuRedZLfJTd/PROJETO-INTEGRADOR---ESCOLA?type=design&node-id=56-7&t=EMU2ZT2LlXvX7Lf3-0&scaling=scale-down&page-id=0%3A1&starting-point-node-id=56%3A7&show-proto-sidebar=1](https://www.figma.com/proto/Trb0ehs1cwYXuRedZLfJTd/PROJETO-INTEGRADOR---ESCOLA?type=design&node-id=56-7&t=0zgLIPTuxoZP0LzV-1&scaling=scale-down&page-id=0%3A1&starting-point-node-id=56%3A7&show-proto-sidebar=1&mode=design)https://www.figma.com/proto/Trb0ehs1cwYXuRedZLfJTd/PROJETO-INTEGRADOR---ESCOLA?type=design&node-id=56-7&t=0zgLIPTuxoZP0LzV-1&scaling=scale-down&page-id=0%3A1&starting-point-node-id=56%3A7&show-proto-sidebar=1&mode=design">FIGMA NAVEGAVEL</a>
</br>
<h1 align="center">DIAGRAMA DE CASO DE USO</h1>


<div align="center">
    <img src="https://github.com/grupo-8-senac-ead/pi-dev-sistemas-oo/assets/78884474/60b5e371-6bbb-464f-8c5d-2494a9c3454d"width="600px"  />
</div>
   <p>
       
<h3>Descrição dos cenários de caso de uso.</h3>	
    	
    •	Cenário cadastro de usuário:
    1.	O usuário seleciona a opção de cadastrar uma nova pessoa física.
    2.	O sistema exibe o formulário de cadastro com os campos necessários.
    3.	O usuário preenche os dados da pessoa física (nome, CPF, endereço, RG, telefone, e-mail e sexo).
    4.	O usuário confirma o cadastro.
    5.	O sistema valida os dados inseridos e registra a nova pessoa física no sistema.
    6.	O sistema exibe uma mensagem de sucesso informando que o cadastro foi realizado.
    
<h3>Cenários Alternativos:</h3>
 
        A1: Caso algum campo obrigatório não seja preenchido corretamente:
        O sistema exibe uma mensagem de erro indicando os campos inválidos.
        O usuário corrige os campos inválidos e tenta novamente o cadastro.
       
        A2: Caso o usuário decida cancelar o cadastro:
        O usuário seleciona a opção de cancelar o cadastro.
        O sistema descarta as informações inseridas e retorna à tela anterior.
        Pré-condições: O usuário deve estar autenticado no sistema.
        Pós-condições: A pessoa física é cadastrada com sucesso no sistema.
    
<h3>Cenário primeira aula:</h3>

    1.	Professor disponibiliza material da aula para os alunos.
    2.	Pessoa física faz o pagamento da mensalidade do aluno.
    3.	Pessoa do jurídico faz recebimento do pagamento.
    4.	Aluno compra material do fornecedor para aula.
    5.	Professor ministra aula para aluno.
    6.	Aluno assiste a aula do professor.</p>

<h3>Cenários Alternativos:</h3>
 
    A1: Caso aluno não tenha o material:
    O professor disponibiliza o conteúdo da aula sem a prática.
    Aluno assiste aula sem fazer a prática.
    Professor marca outra data para o aluno fazer a prática.7

    A2: Caso aluno não tenha conteúdo da aula disponibilizado
    Aluno deve entrar em contato com o professor, explicando a falta de disponibilidade.
    Professor deve disponibilizar conteúdo para aula até um dia antes da aula. 
    Pré-condição: Aluno deve ter a mensalidade paga para assistir aula.
    Pós-condição: Aluno adquiri conhecimento para prova.

 </br>
 <h1 align="center">DIAGRAMA DE CLASSES</h1>
<div align="center">
      <img src="https://github.com/grupo-8-senac-ead/pi-dev-sistemas-oo/assets/78884474/90aa5e72-aec4-4373-bd29-85ad63132f63" width="600px"  />
   </div>

 </br>

 <h1 align="center">TELAS PROTOTIPADAS</h1>
 
  </br>
 <h2 align="center"> ALUNOS 🎒 </h2>
 <p align="center">Ao fazer login na plataforma, o aluno poderá acessar os materiais de aulas matérias do colegio e suas respectivas notas no colegio FUTURO BRILHANTE.</p>
</br>

 
  </br>
<h3> LOGIN </h3>
<div align="center">
      <img src="https://github.com/grupo-8-senac-ead/pi-dev-sistemas-oo/assets/78884474/cd0f65db-e8e6-47fd-8b33-60ee551db3f0" width="1080px"  />
   </div>

  </br>
 <h3> AREA DO ALUNO </h3>
<div align="center">
      <img src="https://github.com/grupo-8-senac-ead/pi-dev-sistemas-oo/assets/78884474/9f2fa633-1308-40df-955e-de4fb787a2f4" width="1080px" />
   </div>

  </br>
 <h3> ASSISTIR AULAS </h3>
<div align="center">
      <img src="https://github.com/grupo-8-senac-ead/pi-dev-sistemas-oo/assets/78884474/d2412a72-068a-452d-8c8b-cf92c9eb021d" width="1080px" />
   </div>

 </br>
<h3>NOTAS E FREQUENCIA </h3>
<div align="center">
      <img src="https://github.com/grupo-8-senac-ead/pi-dev-sistemas-oo/assets/78884474/0149a587-dbca-484b-b586-b6ecc843fd66" width="1080px" />
   </div>

 </br>

<h3>SUPORTE </h3>

<div align="center">
      <img src="https://github.com/grupo-8-senac-ead/pi-dev-sistemas-oo/assets/78884474/83fbdbbb-f2d3-4dcc-9090-bdf21dd4c142" width="1080px" />
   </div>


  </br>
 <h2 align="center"> PROFESSORES 👩‍🏫 </h2>
 <p align="center">Ao login na plataforma, o professor(a) poderá acessar aos registros de sala e alunos dessa sala e também poderar acompanhar a frenquencia e dar notas as provas pela plataforma do colegio FUTURO BRILHANTE.</p>
</br>

  </br>
<h3> LOGIN </h3>

<div align="center">
      <img src="https://github.com/grupo-8-senac-ead/pi-dev-sistemas-oo/assets/78884474/2957a59d-8089-4235-add8-307813ef3039" width="1080px"  />
   </div>
   
 </br>
<h3> AREA DO PROFESSOR(A) </h3>
<div align="center">
      <img src="https://github.com/grupo-8-senac-ead/pi-dev-sistemas-oo/assets/78884474/c5ef49e8-5bc6-4b05-ba2b-90b9ed092f4f" width="1080px"  />
   </div>

 </br>
<h3> NOTAS E FREQUENCIAS ALUNOS </h3>
<div align="center">
      <img src="https://github.com/grupo-8-senac-ead/pi-dev-sistemas-oo/assets/78884474/7e44af3b-5452-4da0-90f9-1c05dab60a70" width="1080px"  />
   </div>

 </br>
 <h2 align="center"> GESTÃO 🏫</h2>
 <p align="center">Ao FAZER login na plataforma, o COLABORADOR poderá acessar aos registros de sala e alunos, professores e fornecedores, pode tambem cadasatrar novos fornecedores, professores e alunos no colegio FUTURO BRILHANTE.</p>
</br>

 </br>
<h3> LOGIN </h3>
<div align="center">
      <img src="https://github.com/grupo-8-senac-ead/pi-dev-sistemas-oo/assets/78884474/e3db215e-5ad0-4d3a-b4cf-7f509ade6929" width="1080px"  />
   </div>

 </br>
<h3> AREA ADMINISTRATIVA </h3>
<div align="center">
      <img src="https://github.com/grupo-8-senac-ead/pi-dev-sistemas-oo/assets/78884474/3f61cf06-0a1b-40d1-8ac2-fd7c6e0efdb5" width="1080px"  />
   </div>
   
</br>
 <h3>GESTÃO - ALUNOS CADASTRO</h3>
 <div align="center">
      <img src="https://github.com/grupo-8-senac-ead/pi-dev-sistemas-oo/assets/78884474/0eb071f6-8844-4c40-8cc6-4ad861d7dde8" width="1080px"  />
   </div>

</br>
 <h3>GESTÃO - ALUNOS LISTA</h3>
 <div align="center">
      <img src="https://github.com/grupo-8-senac-ead/pi-dev-sistemas-oo/assets/78884474/2645994b-1147-4479-8fdb-342752e0ca86" width="1080px"  />
   </div>

</br>
 <h3>GESTÃO - PROFESSORES CADASTRO</h3>
 <div align="center">
      <img src="https://github.com/grupo-8-senac-ead/pi-dev-sistemas-oo/assets/78884474/67363e7c-6521-4676-b615-c43eca56f24a" width="1080px"  />
   </div>

</br>
 <h3>GESTÃO - PROFESSORES LISTA</h3>
 <div align="center">
      <img src="https://github.com/grupo-8-senac-ead/pi-dev-sistemas-oo/assets/78884474/67363e7c-6521-4676-b615-c43eca56f24a" width="1080px"  />
   </div>

</br>
 <h3>GESTÃO - FORNECEDORES CADASTRO</h3>
 <div align="center">
      <img src="https://github.com/grupo-8-senac-ead/pi-dev-sistemas-oo/assets/78884474/6a3eb1f9-f196-4e90-a9ef-4ae29eb3bc88" width="1080px"  />
   </div>

</br>
 <h3>GESTÃO - FORNECEDORES CADASTRO</h3>
 <div align="center">
      <img src="https://github.com/grupo-8-senac-ead/pi-dev-sistemas-oo/assets/78884474/37174c84-aa13-4e2e-9f69-87ff921b268b" width="1080px"  />
   </div>

</br>
 <h3>GESTÃO - MODAL CADASTRADO COM SUCESSO</h3>
 <div align="center">
      <img src="https://github.com/grupo-8-senac-ead/pi-dev-sistemas-oo/assets/78884474/e3e1b62e-41d7-4deb-a165-002f0d4483f9" width="1080px"  />
   </div>

</br>
 <h3>GESTÃO - MODAL ERRO CAMPOS OBRIGATORIOS</h3>
 <div align="center">
      <img src="https://github.com/grupo-8-senac-ead/pi-dev-sistemas-oo/assets/78884474/e8a6de1c-3c8f-4228-be88-c04fe70ab3d3" width="1080px"  />
   </div>
   
