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



<b>4. PERSONAS E HISTÓRIAS DE USUÁRIO<br></b>
a) inclusão dos Persons desenvolvidos pelo grupo<br>
![Alt text](https://github.com/ninamariano/template_projeto_integrador/blob/main/arquivos/Personas.PNG)<br>
https://drive.google.com/file/d/1R655DPkJy1uYbpS-EaEIskA1dPwTYgQw/view?usp=sharing


b) inclusão das Histórias de usuário desenvolvidas pelo grupo<br>
![Alt text](https://github.com/ninamariano/template_projeto_integrador/blob/main/arquivos/Historia%20de%20Usuario.PNG)<br>
https://drive.google.com/file/d/1fHd5QBwyl_h0W58VLSPoNU6zlC0MMFw0/view?usp=sharing<br>
<br>

<b>5. RASCUNHOS BÁSICOS DA INTERFACE (MOCKUPS)</b><br>
![Alt text](https://github.com/ninamariano/template_projeto_integrador/blob/main/arquivos/Prototipo.PNG)<br>
https://www.figma.com/file/LpGQFtAgEowuKSbgE1vVDz/Prot%C3%B3tipos?node-id=0%3A1


<b>5.1 QUAIS PERGUNTAS PODEM SER RESPONDIDAS COM O SISTEMA PROPOSTO?</b><br>

Relatórios de objetivos e interesses dos usuários, contendo todas as suas informações com relação ao vestibular.

O sistema Stunizado precisa inicialmente dos seguintes relatórios:
* Relatório com a quantidade de usuários por cada curso de interesse incluindo as seguintes informações: curso, faculdade e nome do usuário.
* Relatório que informe quantos conteúdos há em cada disciplina incluindo as seguintes informações: nome da disciplina e quantidade de conteúdos.
* Relatório das atividades a serem realizadas pelo usuário em cada dia contendo hora, dia da semana e descrição da atividade;
* Relatório que apresente quantos horários cada usuário tem disponível.
* Relatório que relacione cada usuário ao curso e a faculdade desejada, incluindo: nome do usuário, nome da faculdade, nome do curso.
 <br>   

 






<b>6. TABELA DE DADOS DO SISTEMA:</b>/<br>
https://docs.google.com/spreadsheets/d/12X_oOsdZy9QY46T7XTzUFpD0mLCGBbvlRioiAtC2MVo/edit?usp=sharing<br>
<br>



<b>7. MODELO CONCEITUAL</b><br>
![Alt text](https://github.com/ninamariano/template_projeto_integrador/blob/main/arquivos/Modelo%20Conceitual.png)<br>
https://drive.google.com/file/d/1-HWbOHQTqD-K5Zepyn64uZKl_kgGFs-u/view?usp=sharing
<br>	




B - Usuário, atividade agendada e faculdade. Um dos principais fluxos é o fluxo usuário_disponibilidade_atividadeagendada, que é o que de fato cumpre o principal papel da aplicação que é o cronograma.

	 
<b>7.1 Descrição dos dados</b>

<b>Usuário:</b> tabela que armazena as informações relativas ao usuário.
Id:campo que armazena o número de matrícula do usuário.
Nome: campo que armazena o nome do usuário.
Sobrenome: campo que armazena o sobrenome do usuário.
Email: campo que armazena o email do usuário.
Celular: campo que armazena o número de celular do usuário.
Genero: campo que armazena o gênero do usuário.
Senha: campo que armazena a senha do usuário.
 
<b>Dia_semana:</b> tabela que armazena as informações dos dias da semana.
Id: campo que armazena o código do dia da semana.
Nome: campo que armazena o nome do dia da semana.

<b>Planejamento:</b> tabela que armazena as informações da 
Nome:  campo que armazena o nome do planejamento.
Dt_inicio: campo que armazena a data de início do planejamento.
Dt_fim: campo que armazena a data de fim do planejamento.

<b>Plan_dia:</b> tabela de relação que armazena a quatidade de horas disponíveis em cada dia da semana de um planejamento.
Id: campo que armazena o código do dia/plano.
Qtd_horas: campo que armazena a quantidade de horas disponíveis no dia do planejamento.

<b>Plan_disc:</b> tabela de relação que armazena as disciplinas que serão feitas pelo usuário.
Fazer: armazena quais disciplinas serão e não serão feitas.
Id: campo que armazena o código do plano/disc.

<b>Disciplinas:</b> tabela que armazena as informações das matérias que o usuário estuda.
Nome: campo que armazena o nome das disciplinas.
Id: campo que identifica cada disciplina.
 
<b>Conteúdos:</b> tabela que armazena as informações dos conteúdos a serem estudados pelo usuário.
Id: campo que identifica cada conteúdo.
Nome: campo que armazena o nome dos conteúdos.
Cod_disciplina: campo que identifica a qual disciplina o conteúdo pertence.<br>
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
  	 




<b>11. INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br><b>
    	a) inclusão das instruções de inserção dos dados nas tabelas criadas pelo script de modelo físico
    	(Drop para exclusão de tabelas + create definição de para tabelas e estruturas de dados
 <br> + insert para dados a serem inseridos)
    	b) Criar um novo banco de dados para testar a restauracao
    	(em caso de falha na restauração o grupo não pontuará neste quesito)
    	c) formato .SQL
<br>	
	
<b>12 TABELAS E PRINCIPAIS CONSULTAS</b><br>
OBS: Incluir para cada tópico as instruções SQL + imagens (print da tela) mostrando os resultados.<br>

<b>12.1 CONSULTAS DAS TABELAS COM TODOS OS DADOS INSERIDOS (Todas)</b>

<b>12.2 PRINCIPAIS CONSULTAS DO SISTEMA</b><br>
<br>

<b>12.3 ANTEPROJETO VERSÃO 1</b><br>
https://docs.google.com/document/d/1N03VWSGvzWUp4_SWPR_GeCNuyEGG8_AAB9fOHay2AtI/edit?usp=sharing




    








