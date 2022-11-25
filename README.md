TRABALHO DE PI: STUNIZADO

<b>1. COMPONENTES <br></b>
Integrantes do grupo <br>
Miguel Abreu de Matos: miguelabreumatos@gmail.com<br>
Lavínia Mariano: lavinianina@outlook.com<br>
Gianluca Scalzin: gianlucascalzisampogna@gmail.com<br>
<br>

<b>2.MINIMUNDO<br></b>
   O sistema a ser desenvolvido para o site "Stunizado" conterá as seguintes informações: dos usuários serão armazenados matrícula, nome, sexo e data de nascimento. Além disso, a respeito do curso de interesse do usuário será armazenado nome e código e a respeito da faculdade será nome, código e processo seletivo. Um usuário pode desejar mais de um curso e faculdade e faculdade e curso podem possuir mais de  um usuário. Com relação às disciplinas, armazenaremos nome e código, e com relação aos conteúdos será nome, importância, código e código da disciplina a qual pertence, sendo assim, uma disciplina pode conter mais de um conteúdo, mas um conteúdo só pode pertencer a uma disciplina. Outras importantes informações são as da disponibilidade, sendo elas id, início, fim e dia da semana, e também as da atividade agendada, sendo id, inicio, fim, dia da semana, pessoa e descrição. Um usuário pode ter diversos horários de disponibilidade e atividades agendadas e essas podem ser de vários usuários.<br>
<br>

<b>3.PMC<br></b>
![Alt text](https://github.com/ninamariano/template_projeto_integrador/blob/main/arquivos/PMC.PNG)<br>
https://drive.google.com/file/d/1JB77qcl5fPhs_R1OZTYgF7XAodsZBXsY/view?usp=sharing<br>
<br>



<b>4. PERSONAS E HISTÓRIAS DE USUÁRIO</b><br>
<b>a) Personas</b><br>
![Alt text](https://github.com/ninamariano/template_projeto_integrador/blob/main/arquivos/Personas.PNG)<br>
https://drive.google.com/file/d/1R655DPkJy1uYbpS-EaEIskA1dPwTYgQw/view?usp=sharing


<b>b) Histórias de usuário</b><br>
![Alt text](https://github.com/ninamariano/template_projeto_integrador/blob/main/arquivos/Historia%20de%20Usuario.PNG)<br>
https://drive.google.com/file/d/1fHd5QBwyl_h0W58VLSPoNU6zlC0MMFw0/view?usp=sharing<br>
<br>

<b>5. RASCUNHOS BÁSICOS DA INTERFACE (MOCKUPS)</b><br>
![Alt text](https://github.com/ninamariano/template_projeto_integrador/blob/main/arquivos/Prototipo.PNG)<br>
https://www.figma.com/file/LpGQFtAgEowuKSbgE1vVDz/Prot%C3%B3tipos?node-id=0%3A1


<b>5.1 QUAIS PERGUNTAS PODEM SER RESPONDIDAS COM O SISTEMA PROPOSTO?</b><br>

Relatórios de objetivos e interesses dos usuários, contendo todas as suas informações com relação ao vestibular.

O sistema Stunizado precisa inicialmente dos seguintes relatórios:
* Relatório que informa a quantidade de planejamentos que realizarão cada disciplina.
* Relatório que informa quantos conteúdos há em cada disciplina.
* Relatório que informa a quantidade de horas disponíveis por dia da semana de um planejamento.
* Relatório que informa a quantidade de disciplinas que cada planejamento está cadastrado para estudar.
* Relatório que informa a quantidade total de horas disponíveis por semana de um planejamento.

 






<b>6. TABELA DE DADOS DO SISTEMA:</b>/<br>
https://docs.google.com/spreadsheets/d/1Ot_mDXuw85-kzCVTcoxdcMph8FFAR2LkpkrWs1eN5R0/edit?usp=sharing<br>
<br>



<b>7. MODELO CONCEITUAL</b><br>
![Alt text](https://github.com/ninamariano/template_projeto_integrador/blob/main/arquivos/Conceitual.png)<br>
<br>	




B - Usuário, Planejamento, Plan_dia, Plan_disc. Um dos principais fluxos é o fluxo Usuário_Planejamento, que é o que de fato cumpre o principal papel da aplicação que é o cronograma.

	 
<b>7.1 Descrição dos dados</b>

<b>Usuário:</b> tabela que armazena as informações relativas ao usuário. <br>
Id: campo que armazena o número de matrícula do usuário. <br>
Nome: campo que armazena o nome do usuário. <br>
Sobrenome: campo que armazena o sobrenome do usuário. <br>
Email: campo que armazena o email do usuário. <br>
Celular: campo que armazena o número de celular do usuário. <br>
Genero: campo que armazena o gênero do usuário. <br>
Senha: campo que armazena a senha do usuário. <br>
 
<b>Dia_semana:</b> tabela que armazena as informações dos dias da semana. <br>
Id: campo que armazena o código do dia da semana. <br>
Nome: campo que armazena o nome do dia da semana. <br>

<b>Planejamento:</b> tabela que armazena as informações de cada planejamento. <br>
Nome:  campo que armazena o nome do planejamento. <br>
Dt_inicio: campo que armazena a data de início do planejamento. <br>
Dt_fim: campo que armazena a data de fim do planejamento. <br>

<b>Plan_dia:</b> tabela de relação que armazena a quatidade de horas disponíveis em cada dia da semana de um planejamento. <br>
Id: campo que armazena o código do dia/plano. <br>
Qtd_horas: campo que armazena a quantidade de horas disponíveis no dia do planejamento. <br>

<b>Plan_disc:</b> tabela de relação que armazena as disciplinas que serão feitas pelo usuário. <br>
Fazer: armazena quais disciplinas serão e não serão feitas. <br>
Id: campo que armazena o código do plano/disc. <br>

<b>Disciplinas:</b> tabela que armazena as informações das matérias que o usuário estuda. <br>
Nome: campo que armazena o nome das disciplinas. <br>
Id: campo que identifica cada disciplina. <br>
 
<b>Conteúdos:</b> tabela que armazena as informações dos conteúdos a serem estudados pelo usuário. <br>
Id: campo que identifica cada conteúdo. <br>
Nome: campo que armazena o nome dos conteúdos. <br>
Cod_disciplina: campo que identifica a qual disciplina o conteúdo pertence.
<br>	 
	 
<b> 8.RASTREABILIDADE DOS ARTEFATOS</b><br>
<b>a) Historia de usuários vs protótipo (mockup)</b><br>

https://drive.google.com/file/d/1JU2m_B8m2XXgTpften-UfvOqamXWbh_t/view?usp=sharing



<b>b) Protótipo vs Modelo conceitual</b><br>
    (não serão aceitos modelos que não estejam em conformidade)<br>
    
    https://docs.google.com/spreadsheets/d/1_Zx2nl94NHied_T2HUfNCF-OnEjv34xg3-oalWz5TDw/edit?usp=sharing<br>
<br>    
    
<b> 9. MODELO LÓGICO</b><br>
![Alt text](https://github.com/ninamariano/template_projeto_integrador/blob/main/arquivos/Logico.png)<br>
<br>

<b>10. MODELO FÍSICO</b>
    	[/* Lógico_1: */

CREATE TABLE DISCIPLINAS (
    NOME VARCHAR(50),
    ID INTEGER PRIMARY KEY
);

CREATE TABLE CONTEUDOS (
    NOME VARCHAR(100),
    ID INTEGER PRIMARY KEY,
    COD_DISCIPLINA INTEGER,
    FK_DISCIPLINAS_ID INTEGER
);

CREATE TABLE PLANEJAMENTO (
    NOME VARCHAR(50),
    DT_INICIO DATE,
    DT_FIM DATE,
    FK_USUARIO_ID SERIAL
);

CREATE TABLE DIA_SEMANA (
    ID INTEGER PRIMARY KEY,
    NOME VARCHAR(100)
);

CREATE TABLE PLAN_DISC (
    FK_DISCIPLINAS_ID INTEGER,
    FAZER INTEGER,
    ID INTEGER PRIMARY KEY
);

CREATE TABLE PLAN_DIA (
    FK_DIA_SEMANA_ID INTEGER,
    QTD_HORAS INTEGER,
    ID INTEGER PRIMARY KEY
);
 
ALTER TABLE CONTEUDOS ADD CONSTRAINT FK_CONTEUDOS_2
    FOREIGN KEY (FK_DISCIPLINAS_ID)
    REFERENCES DISCIPLINAS (ID)
    ON DELETE RESTRICT;
 
ALTER TABLE PLANEJAMENTO ADD CONSTRAINT FK_PLANEJAMENTO_1
    FOREIGN KEY (FK_USUARIO_ID)
    REFERENCES USUARIO (ID)
    ON DELETE CASCADE;
 
ALTER TABLE PLAN_DISC ADD CONSTRAINT FK_PLAN_DISC_2
    FOREIGN KEY (FK_DISCIPLINAS_ID)
    REFERENCES DISCIPLINAS (ID)
    ON DELETE RESTRICT;
 
ALTER TABLE PLAN_DIA ADD CONSTRAINT FK_PLAN_DIA_2
    FOREIGN KEY (FK_DIA_SEMANA_ID)
    REFERENCES DIA_SEMANA (ID)
    ON DELETE RESTRICT;<br>
<br>
  	 




<b>11. INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br><b><br>	
https://drive.google.com/file/d/10hQCMYtjn9bouKQjCITbFcnBPOK0N1oD/view?usp=sharing <br>	
	
<b>12 TABELAS E PRINCIPAIS CONSULTAS</b><br>

<b>12.1 CONSULTAS DAS TABELAS COM TODOS OS DADOS INSERIDOS (Todas)</b><br>	
https://drive.google.com/file/d/17W5BFJCm7hwwIqx9rbyNW7XqMNxqOAqs/view?usp=sharing<br>	

<b>12.2 PRINCIPAIS CONSULTAS DO SISTEMA</b><br>
<br>

<b>12.3 ANTEPROJETO VERSÃO 1</b><br>
https://docs.google.com/document/d/1N03VWSGvzWUp4_SWPR_GeCNuyEGG8_AAB9fOHay2AtI/edit?usp=sharing




    








