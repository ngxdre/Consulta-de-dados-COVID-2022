# Consulta de Dados COVID 2022

Este repositório contém scripts para análise de dados relacionados ao COVID-19, focando em informações sobre internações e evolução de pacientes.

__Funcionalidades:__

* O projeto utiliza SQL para realizar consultas e análises de dados em um banco de dados, com o objetivo de extrair informações relevantes sobre pacientes com suspeitas de COVID.

__Consultas SQL Principais:__

* Seleção do Maior e Menor Registro Numérico: Utiliza funções agregadas como MAX e MIN para identificar o maior valor de uma coluna específica, como o número de dias entre duas datas.

* Cálculo de Diferença de Datas: Realiza o cálculo da diferença em dias entre a data de internação (dt_interna) e a data de evolução (dt_evoluca) de pacientes, utilizando a função DATEDIFF.

* Agrupamento de Dados: O projeto agrupa as informações por categorias como sexo para obter insights relevantes em diferentes grupos de pacientes.

__Requisitos:__

* Databricks Community: O Databricks Community Edition é uma versão gratuita e acessível do Databricks, uma plataforma baseada em Apache Spark que permite executar notebooks, explorar dados e realizar análises avançadas de dados em um ambiente colaborativo. É útil para projetos de ciência de dados e análise de grandes volumes de dados.
  
* SQL: As consultas foram desenvolvidas utilizando SQL para análise de dados em um banco de dados relacional.


## Arquivo de Base de Dados

O arquivo da base de dados dados-sivep-esus-sao-paulo-sp-jul-dez-2022.csv está compactado em um arquivo ZIP devido ao seu tamanho (146 MB), que excede o limite do GitHub.

__Instruções:__

* Descompactar o arquivo: Antes de subir para o Databricks, descompacte o arquivo ZIP para obter o CSV.
* Subir ao Databricks: Após descompactado, você pode fazer o upload do arquivo CSV para o Databricks para iniciar a análise de dados.
