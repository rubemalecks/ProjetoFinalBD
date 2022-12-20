

|![](Aspose.Words.b48db382-f2c4-4ef4-949d-79997e01d789.001.png)|**INSTITUTO FEDERAL DE EDUCAÇÃO, CIÊNCIA E TECNOLOGIA PARAÍBA CAMPUS CAMPINA GRANDE**|
| - | :- |
|**PROFESSORA: IANA DAYA PASSOS**|**CURSO: SUBSEQUENTE EM INFORMÁTICA**|**DISCIPLINA: BANCO DE DADOS**|
|**DATA: 20/DEZ**  |**ALUNO (A): RUBEM ÁLECKS, RAUDINEY E LEANDRO.** |
**ATIVIDADE PRÁTICA SQL** 

Tomando como base os esquemas de relação do Banco de Dados representado abaixo, realize as consultas a seguir:

**PROFESSOR (Nome, SNome, Matricula, DataNasc, Sexo, Salario, Matric\_Represent\_Area, Depto)**

Chave estrangeira referente a DEPARTAMENTO = Depto

**DEPARTAMENTO (Nome, Sigla, Codigo, Coordenador)** Chave estrangeira referente a PROFESSOR = Coordenador

**PROJETO (Nome, Codigo, Depto, Duraçao)**

Chave estrangeira referente a DEPARTAMENTO = Depto

**DEPENDENTE (MatricProf, Nome, RG, Sexo, DataNasc)** Chave estrangeira referente a PROFESSOR = MatricProf

**EMAIL (MatricProf, Email)**

Seguem as tabelas PROFESSOR e DEPARAMENTO devidamente povoadas para viabilizar as consultas.

**PROFESSOR**



|**Nome**|**SNome**|**Matricula**|**DataNasc**|**Sexo**|**Salario**|**Matric\_Repre sent\_Area**|**Depto**|
| - | - | - | - | - | - | :-: | - |
|Pedro|Pereira da Silva|121003|25/03/1982|M|4000,00||121|
|José Maria|Campos|121031|10/04/1978|M|7000,00|121003|121|
|Bento|Diniz Costa|122045|27/11/1980|M|4000,00||122|
|Ana Clara|Araújo Santos|122047|30/12/1994|F|7200,00|122045|122|
|Joana Maria|Campos Pereira|125332|12/06/1990|F|4500,00||125|
|João Carlos|Matos Cavalcanti|125335|22/07/1976|M|3700,00|125332|125|
|Maria Luiza|Machado|125331|16/08/1974|F|6800,00|125332|125|
**DEPARTAMENTO**



|**Nome**|**Sigla**|**Código**|**Coordenador**|
| - | - | - | - |
|Tec. Telemática|DTT|121|121031|
|Tec. Construção de Edifícios|DCE|122|122047|
|Eng. Computação|DEC|125|125331|
IMPORTANTE: o preenchimento das demais tabelas criadas ficará a seu critério, todavia é necessário destacar que deverá atender a algumas situações específicas da consulta, como por exemplo, a tabela Dependente ter pessoas de ambos os sexos.

**CONSULTAS**

1. Exiba o nome, o RG e a data de nascimento de todos os dependentes do sexo feminino.
1. Relacione em ordem decrescente os (diferentes) salários dos professores da instituição.
1. Atualize o nome do projeto “Aplicações BD” para “Aplicações de Big Data”.
1. Exiba a matrícula e o nome dos professores que nasceram a partir de 1970, ordenados pelo nome em ordem ascendente.
5. Exiba em ordem decrescente da data de nascimento todos os dados dos professores que nasceram na década de 80 e que têm Pereira no sobrenome.
5. Exiba o nome, sobrenome e matrícula dos professores que são representantes de área;
5. Exiba o nome e a data de nascimento do dependente mais jovem.
5. Exibir a matrícula e o nome de todas as professoras que tenham Maria em qualquer parte do nome ordenados pelo nome em ordem decrescente.
5. Exiba nome, sobrenome dos empregados cuja segunda letra do nome é “O” e tenha “Campos” no sobrenome;
5. Para cada departamento, exiba o código do departamento e a quantidade de projetos lá alocados.
5. Exiba o nome e o código dos departamentos que têm mais de 2 professores nele lotados.
5. Selecione o nome, o sobrenome e a matrícula dos professores que trabalham no Departamento de Tecnologia em Telemática. 
5. Exiba o e-mail do professor cujo nome é João Carlos.
5. Exiba o nome do(a) coordenador(a) do Departamento de Engenharia de Computação
5. Exiba os nomes dos professores que não têm dependentes.
