TRABALHO DE PI: STUNIZADO

<b>1. COMPONENTES <br></b>
Integrantes do grupo <br>
Miguel Abreu de Matos: miguelabreumatos@gmail.com<br>
Lavínia Mariano: lavinianina@outlook.com<br>
Gianluca Scalzin: gianlucascalzisampogna@gmail.com<br>


2.MINIMUNDO<br>
   O sistema a ser desenvolvido para o site "Stunizado" conterá as seguintes informações: dos usuários serão armazenados matrícula, nome, sexo e data de nascimento. Além disso, a respeito do curso de interesse do usuário será armazenado nome e código e a respeito da faculdade será nome, código e processo seletivo. Um usuário pode desejar mais de um curso e faculdade e faculdade e curso podem possuir mais de  um usuário. Com relação às disciplinas, armazenaremos nome e código, e com relação aos conteúdos será nome, importância, código e código da disciplina a qual pertence, sendo assim, uma disciplina pode conter mais de um conteúdo, mas um conteúdo só pode pertencer a uma disciplina. Outras importantes informações são as da disponibilidade, sendo elas id, início, fim e dia da semana, e também as da atividade agendada, sendo id, inicio, fim, dia da semana, pessoa e descrição. Um usuário pode ter diversos horários de disponibilidade e atividades agendadas e essas podem ser de vários usuários.


3.PMC<br>
https://drive.google.com/file/d/1JB77qcl5fPhs_R1OZTYgF7XAodsZBXsY/view?usp=sharing




4. PERSONAS E HISTÓRIAS DE USUÁRIO<br>

a) inclusão dos Persons desenvolvidos pelo grupo
https://drive.google.com/file/d/1R655DPkJy1uYbpS-EaEIskA1dPwTYgQw/view?usp=sharing


b) inclusão das Histórias de usuário desenvolvidas pelo grupo
https://drive.google.com/file/d/1fHd5QBwyl_h0W58VLSPoNU6zlC0MMFw0/view?usp=sharing


5. RASCUNHOS BÁSICOS DA INTERFACE (MOCKUPS)
https://www.figma.com/file/LpGQFtAgEowuKSbgE1vVDz/Prot%C3%B3tipos?node-id=0%3A1


5.1 QUAIS PERGUNTAS PODEM SER RESPONDIDAS COM O SISTEMA PROPOSTO?

Relatórios de objetivos e interesses dos usuários, contendo todas as suas informações com relação ao vestibular.

O sistema Stunizado precisa inicialmente dos seguintes relatórios:
* Relatório com a quantidade de usuários por cada curso de interesse incluindo as seguintes informações: curso, faculdade e nome do usuário. 
* Relatório das atividades a serem realizadas pelo usuário em cada dia contendo hora, dia da semana e descrição da atividade;
* Relatórios da agenda de cada usuário contendo nome do usuario, dia da semana e horários; 
* Relatório que informe quais são os conteúdos de cada disciplina incluindo as seguintes informações: nome do conteúdo e nome da disciplina.
* Relatório que informe quais cursos são ofertados em cada faculdade, contendo nome da faculdade, nome do curso e processo seletivo para ingresso.
    

 






6. TABELA DE DADOS DO SISTEMA:

https://docs.google.com/spreadsheets/d/12X_oOsdZy9QY46T7XTzUFpD0mLCGBbvlRioiAtC2MVo/edit?usp=sharing




7. MODELO CONCEITUAL
https://drive.google.com/file/d/1-HWbOHQTqD-K5Zepyn64uZKl_kgGFs-u/view?usp=sharing
	




B - Usuário, atividade agendada e faculdade.

	 
7.1 Descrição dos dados

	Usuário: tabela que armazena as informações relativas ao usuário.
           Nome: campo que armazena o nome do usuário.
	Data_nascimento: campo que armazena a data de nascimento do usuário.
           Sexo: campo que armazena o gênero do usuário.
           Matrícula: campo que armazena o número de matrícula do usuário.

          Curso: tabela que armazena as informações do curso de escolha do usuário.
          Código: campo que armazena os códigos de identificação de cada curso.
          Nome: campo que armazena o nome do curso de escolha.

          Faculdade: tabela que armazena as informações da faculdade escolhida pelo usuário.
          Código: campo que armazena os códigos de identificação de cada faculdade.
          Nome: campo que armazena o nome do curso de escolha.
          Processo_seletivo: campo que armazena a prova a ser feita para a faculdade de escolha.
 
          Disponibilidade: tabela que armazena os horários de disponibilidade do usuário.
          Dia_semana: campo que armazena os dias disponiveis.
          Início: campo que armazena o início de cada horário.
          Fim: campo que armazena o fim de cada horário.
          ID: campo que identifica a disponibilidade de cada usuário.

          Atividade agendada: tabela que armazena as informações da 
          Dia_semana:  campo que armazena os dias disponiveis.
          Início: campo que armazena o início de cada horário.
          Fim: campo que armazena o fim de cada horário.
          ID: campo que identifica cada possível atividade.
          Descrição: campo que descreve a atividade a ser realizada.
          ID_pessoa: campo que armazena os ID’s dos usuários que realizam a atividade.

          Disciplinas: tabela que armazena as informações das matérias que o usuário estuda.
Nome: campo que armazena o nome das disciplinas.
Importância: campo que classifica as disciplinas por nível de importância.
Código: campo que identifica cada disciplina.
 
          Conteúdos: tabela que armazena as informações dos conteúdos a serem estudados pelo usuário.
          Código: campo que identifica cada conteúdo.
          Nome: campo que armazena o nome dos conteúdos.
          Cod_disciplina: campo que identifica de qual disciplina o conteúdo faz parte.

