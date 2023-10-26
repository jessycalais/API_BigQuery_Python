### :dart: Objetivo:
Este repositório tem como objetivo demonstrar minhas habilidades técnicas de integração do BigQuery com arquivos em Python.  
Para visualizar minhas habilidades com SQL, [clique aqui](https://github.com/jessycalais/SQL_BigQuery.git).

### :hammer: Ferramentas utilizadas:
* API do BigQuery;
* Google Colab;
* Python;
* SQL.

### :books: Conteúdo do arquivo do repositório:
**1) O arquivo **`join_sql_pandas.ipynb`** apresenta o uso das seguintes ferramentas:**
* Conexão com a API do BigQuery no Google Colab;
* Consulta SQL realizada diretamente no notebook (.ipynb);
* Leitura de arquivo `.xlsx` com a biblioteca Pandas utilizando parâmetros personalizados;
* Utilização dos métodos `.read_excel()`, `.head()`, `.rename()`, `.merge()`, `.sort_values()`, `.drop()`, `.reset_index()`, `.insert()` da biblioteca Pandas;

**Objetivo:** 
* Utilizar o método `.merge()` da biblioteca Pandas para fazer um **JOIN** entre DataFrames.
 
> **NOTA:** Os dados utilizados nesta consulta foram retirados de um conjunto de dados público disponibilizado pela Base dos Dados.

---

**2) O arquivo **`sql_lag_pandas_shift.ipynb`** apresenta o uso das seguintes ferramentas:**
* Conexão com a API do BigQuery no Google Colab;
* Consulta SQL realizada diretamente no notebook (.ipynb);
* Utilização da instrução `CASE` e da função de janela `LAG()` em SQL;
* Utilização da função `round()` e do método `.shift()` da biblioteca Pandas.

**Objetivo:**
* Utilizar o método `.shift()` da biblioteca Pandas para realizar análise semelhante a obtida com a função de janela LAG() no SQL.
  
> **NOTA:** Os dados utilizados nesta consulta foram retirados de um conjunto de dados público disponibilizado no Big Query.
