# BigData_SparkSQL

## Descrição Projeto

**Conjunto de dados:** 
Conjunto de dados com informações de transações bancárias, via PIX. O conjunto de dados inclui as seguintes informações para cada transação:
Detalhes da transação: identificação da transação, valor, nome e número da conta da parte debitada e creditada, banco debitado e creditado, tipo de chave pix e data da transação. 

**Arquivo:** .csv

**Objetivo:**
Utilizar linguagem SQL para analisar dados de um grande banco de dados com informações de transações bancárias. 

**Observação:**

O Spark SQL é um módulo do Apache Spark que permite processar dados estruturados, ele é altamente otimizado e pode ser usado para processar grandes conjuntos de dados. Podemos utilizá-lo para executar operações semelhantes ao SQL em dados armazenados em memória. Você pode usá-lo para executar consultas SQL em arquivos CSV, JSON, Parquet e outros formatos de arquivo. Além disso, você pode usar o Spark SQL para executar operações de agregação, como contagem, soma, média e muito mais.  

**IDE:** Colab

**Linguagem:** Python e SQL

**Principais bibliotecas utilizadas:**

•	PySpark, para explorar e analisar big data;
•	Spark.sql, módulo para executar comandos SQL em Big Data.

**Resultado:**
Utilizando comandos SQL foi possível responder as seguintes perguntas dentro do banco de dados analisado:

•	Descobrir a quantidade total de transações na base de dados.
•	Qual foi a quantia total de dinheiro transacional em cada ano?
•	Descobrir a quantidade de dinheiro que entrou na Nubank em todo o período.
•	Retornar a quantidade de transações agrupadas por tipo de chave.
•	Descobrir qual é a média, mínima e máxima do valor de todas as transações.
•	Quais foram as 5 maiores transações durante todo o período?
•	Para o banco BTG, mostre qual é a chave pix mais utilizada para enviar ou receber transações. 
•	Descobrir qual foi a maior transação de cada mês na base de dados.
•	Criar uma nova coluna que contenha o valor da transação em dólar. 
