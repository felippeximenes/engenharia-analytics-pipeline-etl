# 📊 Engenharia de Analytics: Pipeline ETL com AWS Glue

## 🧠 Sobre o Projeto

Este repositório faz parte de um projeto pessoal que desenvolvi como forma de aprofundar meus conhecimentos em **Engenharia de Dados** e **processos de ETL usando a AWS**.

A proposta é simular um cenário real de trabalho com ingestão e tratamento de dados, utilizando serviços da AWS como Glue, Athena e S3. A estrutura do projeto segue o conceito de criação de camadas de dados (Bronze e Silver), separando os dados brutos dos dados transformados.

---

## 🎯 Objetivo

O objetivo principal foi criar um **pipeline de ETL completo na AWS**, partindo de arquivos de dados brutos armazenados no Amazon S3 até a geração de dados prontos para análise, utilizando o Glue para orquestrar e transformar as informações.

O pipeline contempla:

- Upload de arquivos no S3
- Criação de catálogo de dados no Glue (Crawler)
- Criação das camadas Bronze e Silver
- Desenvolvimento de transformações no Glue Studio (ETL com PySpark)
- Consultas ad-hoc com Athena
- Possibilidade de visualização com QuickSight

---

## 📂 Dados Utilizados

Durante a execução do projeto, utilizei três conjuntos de dados simulando diferentes áreas de uma empresa:

- `vendas_zoop_bronze.parquet`
- `estoques_zoop_bronze.parquet`
- `redes_sociais_zoop_bronze.parquet`

Esses dados foram tratados e organizados para análises futuras.

---

## 🧰 Tecnologias e Ferramentas

- **Amazon S3**
- **AWS Glue Crawler**
- **AWS Glue Data Catalog**
- **AWS Glue Studio (ETL com PySpark)**
- **AWS Glue Data Quality**
- **Athena**
- **SQL**
- **Python**
- **Apache Spark**

---

## 👨‍💻 Público-alvo

Este projeto é útil para profissionais ou estudantes que desejam entender na prática como funciona a criação de pipelines de dados na AWS. A ideia é mostrar como transformar dados brutos em dados prontos para análise utilizando os principais serviços do ecossistema AWS.

---

## 🧠 Pré-requisitos

É importante ter noções básicas de:
- Python
- PySpark (para uso no Glue Studio)
- SQL (para consultas no Athena)
- Conceitos
