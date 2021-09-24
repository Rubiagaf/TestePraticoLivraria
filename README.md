# 
Parte teórica:
1. Para você, o que significa Business Inteligence? 
	Pra mim, BI é uma ferramenta onde tem a finalidade de agilizar os processos de análises deixando os dados de uma forma dinâmica e de fácil manipulação.

2. Cite duas ferramentas de ETL.
	Integration service e Pentaho

3. Cite três ferramentas de apresentação de Dados.
	Powe Bi e Tableau		

4. O que é uma Tabela Fato e o que é uma tabela Dimensão?
	A tabela fato é a tabela principal, onde é concetrada a maior wquantidade de regustros. Já a tabela Dimenção, são feitas para auxiliar a 
tabela fato e normalizar o datawerehouse.

5. Quais tipos de modelagens são as mais utilizadas em um projeto de BI?
	 Estrela, had hoc

6. O que significa Surrogate Key?
	Storrogate Key é a chave usada para conectar as tabelas dimenção na tabela Fato. 

7. Explique a diferença entre relacionamento 1 para 1 e 1 para N.
	 No relacionamento 1:1 temos um unico registro na t1, que irá se conectar a apenas um registro tambémna T2. 
Já no relacionamento de 1:N, temos um único registro na T1 que pode se conectar e aparecer em vários ouyros registros na T2.

8. O que significa Drill Down / Drill Up?
	Ao usar o drill Down, estamos abrindo a informação no menor nível de granularidade, ou seja, iremos abrir os detalhes. 
Já o Drill Up iremos condensar a informação no maior nível de granularidade, não tera detalhe. 

Parte técnica - Caso:
Um cliente de uma pequena livraria contratou seus serviços de consultoria para realizar algumas análises e apresentar 
os resultados em Power BI. Este cliente possui um DataWarehouse que foi exportado para um arquivo XLSX. 
(ver anexo)
Você precisa criar um painel no Power BI com as seguintes análises:
1 – Faça um Desenho da modelagem deste DataWarehouse relacionando as tabelas.
	Imagem 
1.1 - Qual a modelagem projetada?
	Modelo relacional.
