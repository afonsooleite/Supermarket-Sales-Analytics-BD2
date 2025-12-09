# Supermarket Sales Analytics — Projeto BD2

Este repositório contém o projeto desenvolvido no âmbito da unidade curricular **Bases de Dados II (BD2)**, da Licenciatura em Engenharia e Gestão de Sistemas de Informação – Universidade do Minho.

O objetivo é analisar dados de vendas de um supermercado utilizando **três paradigmas distintos de bases de dados**, avaliando desempenho, modelação, complexidade e capacidade de resposta às necessidades analíticas:

- **MySQL** 🗄 — Modelo relacional
- **Cassandra** 📊 — Armazenamento orientado a colunas
- **Neo4j** 🕸 — Bases de dados de grafos

---

## Questões Analíticas estudadas

As consultas realizadas respondem a **13 questões reais de negócio**, incluindo:

| Tema | Exemplos |
|------|----------|
| Desempenho por filial | Total de vendas por cidade, categoria e método de pagamento |
| Comportamento do consumidor | Horários com maior movimento, preferências por produtos |
| Fiscalidade e faturação | Contribuição da taxa de imposto nas vendas |
| Insights temporais | Quais os dias/meses mais lucrativos |
| KPIs dos produtos | Categoria mais vendida, tendências sazonais |

---

## Modelação dos Dados

- Identificação do **domínio do supermercado**
- Normalização e criação do **modelo entidade-relação (MySQL)**
- **Desnormalização** para colunas chave e eficiência em **Cassandra**
- **Grafo** para explorar **relações entre clientes, lojas e produtos** em Neo4j

A modelação e diagramas encontram-se na documentação em `/docs`.

---

## Estrutura do Repositório

```text
Supermarket-Sales-Analytics-BD2/
│ README.md
│ LICENSE
│
├── docs/        # Relatórios completos das 3 fases do projeto
│   01_Modelacao_MySQL.docx/pdf
│   02_Cassandra.docx/pdf
│   03_Neo4j.docx/pdf

