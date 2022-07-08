TRABALHO DE PI: STUNIZADO

<b>1. COMPONENTES <br></b>
Integrantes do grupo <br>
Miguel Abreu de Matos: miguelabreumatos@gmail.com<br>
Lavínia Mariano: lavinianina@outlook.com<br>
Gianluca Scalzin: gianlucascalzisampogna@gmail.com<br>


<b>2.MINIMUNDO<br></b>
   O sistema a ser desenvolvido para o site "Stunizado" conterá as seguintes informações: dos usuários serão armazenados matrícula, nome, sexo e data de nascimento. Além disso, a respeito do curso de interesse do usuário será armazenado nome e código e a respeito da faculdade será nome, código e processo seletivo. Um usuário pode desejar mais de um curso e faculdade e faculdade e curso podem possuir mais de  um usuário. Com relação às disciplinas, armazenaremos nome e código, e com relação aos conteúdos será nome, importância, código e código da disciplina a qual pertence, sendo assim, uma disciplina pode conter mais de um conteúdo, mas um conteúdo só pode pertencer a uma disciplina. Outras importantes informações são as da disponibilidade, sendo elas id, início, fim e dia da semana, e também as da atividade agendada, sendo id, inicio, fim, dia da semana, pessoa e descrição. Um usuário pode ter diversos horários de disponibilidade e atividades agendadas e essas podem ser de vários usuários.


<b>3.PMC<br></b>
https://drive.google.com/file/d/1JB77qcl5fPhs_R1OZTYgF7XAodsZBXsY/view?usp=sharing<br>




<b>4. PERSONAS E HISTÓRIAS DE USUÁRIO<br></b>

a) inclusão dos Persons desenvolvidos pelo grupo<br>
https://drive.google.com/file/d/1R655DPkJy1uYbpS-EaEIskA1dPwTYgQw/view?usp=sharing


b) inclusão das Histórias de usuário desenvolvidas pelo grupo<br>
https://drive.google.com/file/d/1fHd5QBwyl_h0W58VLSPoNU6zlC0MMFw0/view?usp=sharing<br>


<b>5. RASCUNHOS BÁSICOS DA INTERFACE (MOCKUPS)</b><br>
https://www.figma.com/file/LpGQFtAgEowuKSbgE1vVDz/Prot%C3%B3tipos?node-id=0%3A1


<b>5.1 QUAIS PERGUNTAS PODEM SER RESPONDIDAS COM O SISTEMA PROPOSTO?</b><br>

Relatórios de objetivos e interesses dos usuários, contendo todas as suas informações com relação ao vestibular.

O sistema Stunizado precisa inicialmente dos seguintes relatórios:
* Relatório com a quantidade de usuários por cada curso de interesse incluindo as seguintes informações: curso, faculdade e nome do usuário. 
* Relatório das atividades a serem realizadas pelo usuário em cada dia contendo hora, dia da semana e descrição da atividade;
* Relatórios da agenda de cada usuário contendo nome do usuario, dia da semana e horários; 
* Relatório que informe quais são os conteúdos de cada disciplina incluindo as seguintes informações: nome do conteúdo e nome da disciplina.
* Relatório que informe quais cursos são ofertados em cada faculdade, contendo nome da faculdade, nome do curso e processo seletivo para ingresso.
    

 






<b>6. TABELA DE DADOS DO SISTEMA:</b>/<br>

https://docs.google.com/spreadsheets/d/12X_oOsdZy9QY46T7XTzUFpD0mLCGBbvlRioiAtC2MVo/edit?usp=sharing




<b>7. MODELO CONCEITUAL</b><br>
https://drive.google.com/file/d/1-HWbOHQTqD-K5Zepyn64uZKl_kgGFs-u/view?usp=sharing
	




B - Usuário, atividade agendada e faculdade.

	 
<b>7.1 Descrição dos dados</b>

<b>Usuário:</b> tabela que armazena as informações relativas ao usuário.
Nome: campo que armazena o nome do usuário.
Data_nascimento: campo que armazena a data de nascimento do usuário.
Sexo: campo que armazena o gênero do usuário.
Matrícula: campo que armazena o número de matrícula do usuário.

<b>Curso:</b> tabela que armazena as informações do curso de escolha do usuário.
Código: campo que armazena os códigos de identificação de cada curso.
Nome: campo que armazena o nome do curso de escolha.

<b>Faculdade:</b> tabela que armazena as informações da faculdade escolhida pelo usuário.
Código: campo que armazena os códigos de identificação de cada faculdade.
Nome: campo que armazena o nome do curso de escolha.
 Processo_seletivo: campo que armazena a prova a ser feita para a faculdade de escolha.
 
<b>Disponibilidade:</b> tabela que armazena os horários de disponibilidade do usuário.
Dia_semana: campo que armazena os dias disponiveis.
Início: campo que armazena o início de cada horário.
Fim: campo que armazena o fim de cada horário.
ID: campo que identifica a disponibilidade de cada usuário.

<b>Atividade agendada:</b> tabela que armazena as informações da 
Dia_semana:  campo que armazena os dias disponiveis.
Início: campo que armazena o início de cada horário.
Fim: campo que armazena o fim de cada horário.
ID: campo que identifica cada possível atividade.
Descrição: campo que descreve a atividade a ser realizada.
ID_pessoa: campo que armazena os ID’s dos usuários que realizam a atividade.

<b>Disciplinas:</b> tabela que armazena as informações das matérias que o usuário estuda.
Nome: campo que armazena o nome das disciplinas.
Importância: campo que classifica as disciplinas por nível de importância.
Código: campo que identifica cada disciplina.
 
<b>Conteúdos:</b> tabela que armazena as informações dos conteúdos a serem estudados pelo usuário.
Código: campo que identifica cada conteúdo.
Nome: campo que armazena o nome dos conteúdos.
Cod_disciplina: campo que identifica de qual disciplina o conteúdo faz parte.
	 
	 
<b> 8.RASTREABILIDADE DOS ARTEFATOS</b><br>
<b>a) Historia de usuários vs protótipo (mockup)</b><br>

https://drive.google.com/file/d/1JU2m_B8m2XXgTpften-UfvOqamXWbh_t/view?usp=sharing



<b>b) Protótipo vs Modelo conceitual</b><br>
    (não serão aceitos modelos que não estejam em conformidade)<br>
    
    https://docs.google.com/spreadsheets/d/1_Zx2nl94NHied_T2HUfNCF-OnEjv34xg3-oalWz5TDw/edit?usp=sharing<br>
    
    
<b> 9. MODELO LÓGICO</b><br>

https://drive.google.com/file/d/1m-7-KtnK3w1CP7ij8jpF8LeZjrWwMMaS/view?usp=sharing<br>

10. MODELO FÍSICO
    	/* Lógico_1: */

CREATE TABLE USUARIO (
    MATRICULA INTEGER PRIMARY KEY,
    NOME VARCHAR(50),
    SEXO VARCHAR(50),
    DATA_NASCIMENTO DATE
);

CREATE TABLE FACULDADE (
    NOME VARCHAR(100),
    CODIGO INTEGER PRIMARY KEY,
    PROCESSO_SELETIVO VARCHAR(50)
);

CREATE TABLE CURSO (
    NOME VARCHAR(50),
    CODIGO INTEGER PRIMARY KEY
);

CREATE TABLE DISPONIBILIDADE (
    ID INTEGER PRIMARY KEY,
    INICIO TIME,
    FIM TIME,
    DIA_SEMANA DATE,
    FK_ATIVIDADE_AGENDADA_ID INTEGER
);

CREATE TABLE DISCIPLINAS (
    NOME VARCHAR(50),
    CODIGO INTEGER PRIMARY KEY
);

CREATE TABLE CONTEUDOS (
    NOME VARCHAR(100),
    IMPORTANCIA VARCHAR(50),
    CODIGO INTEGER PRIMARY KEY,
    COD_DISCIPLINA INTEGER,
    FK_DISCIPLINAS_CODIGO INTEGER
);

CREATE TABLE ATIVIDADE_AGENDADA (
    ID INTEGER PRIMARY KEY,
    INICIO TIME,
    FIM TIME,
    DIA_SEMANA DATE,
    ID_PESSOA INTEGER,
    DESCRICAO VARCHAR(100),
    FK_CONTEUDOS_CODIGO INTEGER
);

CREATE TABLE FACULDADE_CURSO_FACULDADE_CURSO_USUARIO (
    FK_FACULDADE_CODIGO INTEGER,
    FK_CURSO_CODIGO INTEGER,
    FK_USUARIO_MATRICULA INTEGER
);

CREATE TABLE DISPONIBILIDADE_USUARIO (
    FK_USUARIO_MATRICULA INTEGER,
    FK_DISPONIBILIDADE_ID INTEGER
);

CREATE TABLE USUARIO_DISCIPLINA (
    FK_DISCIPLINAS_CODIGO INTEGER,
    FK_USUARIO_MATRICULA INTEGER
);
 
ALTER TABLE DISPONIBILIDADE ADD CONSTRAINT FK_DISPONIBILIDADE_2
    FOREIGN KEY (FK_ATIVIDADE_AGENDADA_ID)
    REFERENCES ATIVIDADE_AGENDADA (ID)
    ON DELETE CASCADE;
 
ALTER TABLE CONTEUDOS ADD CONSTRAINT FK_CONTEUDOS_2
    FOREIGN KEY (FK_DISCIPLINAS_CODIGO)
    REFERENCES DISCIPLINAS (CODIGO)
    ON DELETE RESTRICT;
 
ALTER TABLE ATIVIDADE_AGENDADA ADD CONSTRAINT FK_ATIVIDADE_AGENDADA_2
    FOREIGN KEY (FK_CONTEUDOS_CODIGO)
    REFERENCES CONTEUDOS (CODIGO)
    ON DELETE CASCADE;
 
ALTER TABLE FACULDADE_CURSO_FACULDADE_CURSO_USUARIO ADD CONSTRAINT FK_FACULDADE_CURSO_FACULDADE_CURSO_USUARIO_1
    FOREIGN KEY (FK_FACULDADE_CODIGO)
    REFERENCES FACULDADE (CODIGO)
    ON DELETE NO ACTION;
 
ALTER TABLE FACULDADE_CURSO_FACULDADE_CURSO_USUARIO ADD CONSTRAINT FK_FACULDADE_CURSO_FACULDADE_CURSO_USUARIO_2
    FOREIGN KEY (FK_CURSO_CODIGO)
    REFERENCES CURSO (CODIGO)
    ON DELETE NO ACTION;
 
ALTER TABLE FACULDADE_CURSO_FACULDADE_CURSO_USUARIO ADD CONSTRAINT FK_FACULDADE_CURSO_FACULDADE_CURSO_USUARIO_3
    FOREIGN KEY (FK_USUARIO_MATRICULA)
    REFERENCES USUARIO (MATRICULA)
    ON DELETE NO ACTION;
 
ALTER TABLE DISPONIBILIDADE_USUARIO ADD CONSTRAINT FK_DISPONIBILIDADE_USUARIO_1
    FOREIGN KEY (FK_USUARIO_MATRICULA)
    REFERENCES USUARIO (MATRICULA)
    ON DELETE SET NULL;
 
ALTER TABLE DISPONIBILIDADE_USUARIO ADD CONSTRAINT FK_DISPONIBILIDADE_USUARIO_2
    FOREIGN KEY (FK_DISPONIBILIDADE_ID)
    REFERENCES DISPONIBILIDADE (ID)
    ON DELETE SET NULL;
 
ALTER TABLE USUARIO_DISCIPLINA ADD CONSTRAINT FK_USUARIO_DISCIPLINA_1
    FOREIGN KEY (FK_DISCIPLINAS_CODIGO)
    REFERENCES DISCIPLINAS (CODIGO)
    ON DELETE RESTRICT;
 
ALTER TABLE USUARIO_DISCIPLINA ADD CONSTRAINT FK_USUARIO_DISCIPLINA_2
    FOREIGN KEY (FK_USUARIO_MATRICULA)
    REFERENCES USUARIO (MATRICULA)
    ON DELETE SET NULL;

  	 




11. INSERT APLICADO NAS TABELAS DO BANCO DE DADOS
    	a) inclusão das instruções de inserção dos dados nas tabelas criadas pelo script de modelo físico
    	(Drop para exclusão de tabelas + create definição de para tabelas e estruturas de dados
 <br> + insert para dados a serem inseridos)
    	b) Criar um novo banco de dados para testar a restauracao
    	(em caso de falha na restauração o grupo não pontuará neste quesito)
    	c) formato .SQL


    








