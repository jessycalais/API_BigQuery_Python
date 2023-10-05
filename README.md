## Objetivo:
Este repositório tem como objetivo demonstrar habilidades com SQL e Python.

**1) O arquivo `join_sql_pandas.ipynb` apresenta o uso das seguintes ferramentas:**
* Conexão com a API do BigQuery no Google Colab;
* Consulta SQL realizada diretamente no notebook (.ipynb);
* Leitura de arquivo `.xlsx` com a biblioteca Pandas utilizando parâmetros personalizados;
* Utilização dos métodos `.read_excel()`, `.head()`, `.rename()`, `.merge`, `.sort_values`, `.drop`, `.reset_index`, `.insert` da biblioteca Pandas;

É importante ressaltar que o método `.merge` do Pandas nos permite fazer um **JOIN** entre DataFrames.
> **NOTA:** Os dados utilizados nesta consulta foram retirados de um conjunto de dados público disponibilizado pela Base dos Dados.
---

**2) O arquivo `sql_subconsulta_case.md` apresenta utilização da linguagem SQL fazendo uso de diversas habilidades, tais como:**
* Uso de subconsultas;
* Uso da cláusula CASE;
* Uso de INNER JOIN.

> Caso queira utilizar estes mesmos dados, utilize essas tabelas disponibilizadas no BigQuery:
> * `bigquery-public-data.austin_bikeshare.bikeshare_trips`;
> * `bigquery-public-data.austin_bikeshare.bikeshare_stations`.
