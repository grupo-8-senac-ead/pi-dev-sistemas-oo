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
 
  </br>
<h3> LOGIN </h3>
<div align="center">
      <img src="https://github.com/grupo-8-senac-ead/pi-dev-sistemas-oo/assets/78884474/cd0f65db-e8e6-47fd-8b33-60ee551db3f0" width="1080px"  />
   </div>

  </br>
 <h2 > Introdução </h2>
<div align="center">
      <img src="https://github.com/grupo-8-senac-ead/pi-dev-sistemas-oo/assets/78884474/90aa5e72-aec4-4373-bd29-85ad63132f63" width="1080px" />
   </div>


