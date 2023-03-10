# Projeto-Individual-M4

#### :one: Existem outras entidades além dessas três?  
Depende do contexto e do propósito do sistema que está sendo desenvolvido. As três tabelas que mencionei anteriormente (cursos, turmas e alunos) são apenas uma representação simples e genérica de uma estrutura de dados relacional.

Se o sistema precisar de mais informações sobre os alunos: endereço, data de nascimento, e-mail, etc.  
Se o sistema precisar de informações sobre professores ou aulas: Formação, Matricula, duração da aula, etc.  

####  :two:  Quais são os principais campos e tipos?
id: um campo numérico para identificar unicamente cada aluno. Esse campo é geralmente do tipo INT e é definido como a chave primária da tabela.  
nome: um campo de string para armazenar o nome do aluno. Esse campo é do tipo VARCHAR ou CHAR e pode ter um tamanho máximo definido.
turma_id: um campo numérico que identifica a turma ao qual o aluno está associado. Esse campo é do tipo INT e é definido como uma chave estrangeira que referencia a chave primária da tabela turmas.  
curso_id: um campo numérico que identifica o curso ao qual a turma está associada.   

####  :three: Como essas entidades estão relacionadas?
cada turma está associada a um único curso. A relação entre essas duas tabelas é uma relação de um para muitos, ou seja, um curso pode ter várias turmas, mas cada turma pertence a apenas um curso.
Um curso tem várias turmas, e cada turma tem vários alunos.

#### :heavy_check_mark: TABELA ALUNO
 
![](https://raw.githubusercontent.com/poporybr/Projeto-Individual-M4/main/prints/print%20Alunos%20Resilia.png?raw=true)

#### :heavy_check_mark: TABELA CURSO

![](https://github.com/poporybr/Projeto-Individual-M4/blob/main/prints/print%20Cursos%20Resilia.png?raw=true)

#### :heavy_check_mark: TABELA TURMA

![](https://github.com/poporybr/Projeto-Individual-M4/blob/main/prints/print%20Turmas%20Resilia.png?raw=true)

#### :white_check_mark: BANCO FINAL.

![](https://github.com/poporybr/Projeto-Individual-M4/blob/main/prints/print%20Banco%20de%20dados%20Resilia.png?raw=true)

