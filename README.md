# Supermarket Sales Analysis

Projeto completo de análise de dados utilizando Python, SQL, PostgreSQL e Power BI,
simulando um cenário real de análise de vendas no varejo.

O objetivo é extrair insights estratégicos sobre faturamento, comportamento de clientes
e desempenho de produtos a partir de dados de vendas de um supermercado.

---

## Objetivos do Projeto
- Analisar o desempenho de vendas por categoria, produto e cidade
- Comparar o comportamento de compra entre diferentes tipos de clientes
- Integrar análise exploratória em Python, consultas SQL e visualização em BI
- Construir um projeto de portfólio com pipeline completo de dados

---

## Tecnologias Utilizadas
- **Python** (Pandas, Matplotlib, Seaborn)
- **Jupyter Notebook**
- **PostgreSQL**
- **SQL**
- **Power BI**
- **Git & GitHub**

---

## Estrutura do Projeto

📁 supermarket-sales-analysis
├── 📁 notebooks
│ ├── 01_data_exploration.ipynb
│ └── 02_sql_analysis_postgresql.ipynb
│
├── 📁 sql
│ └── create_and_insert_sales.sql
│
├── 📁 powerbi
│ └── supermarket_sales_dashboard.pbix
│
├── 📁 data
│ └── sales.csv
│
└── README.md


---

## Análise Exploratória em Python
A análise inicial foi realizada em Python com Pandas, incluindo:
- Verificação de dados nulos
- Análise estatística descritiva
- Distribuição de vendas por categoria
- Produtos mais vendidos
- Comparações entre tipos de clientes e gênero

---

## Análise com SQL (PostgreSQL)
Os dados foram carregados em um banco PostgreSQL para simular um ambiente real
de análise corporativa.

### Principais análises SQL:
- Faturamento total por categoria
- Faturamento por cidade
- Produtos mais vendidos
- Comparação entre tipos de clientes
- Análise de quantidade vendida e ticket médio

As consultas estão documentadas no notebook:
📁 `02_sql_analysis_postgresql.ipynb`

---

## Power BI — Dashboard Analítico

O projeto conta com um dashboard desenvolvido no Power BI, conectado diretamente
ao banco de dados PostgreSQL.
Tabelas e dados do Power BI na pasta 📁images
-PDF
-PBRX
-PNG

### Principais métricas (KPIs):
- Faturamento total
- Total de vendas
- Quantidade vendida
- Ticket médio

### Análises visuais disponíveis:
- Faturamento por categoria
- Faturamento por cidade
- Produtos mais vendidos
- Comparação de vendas por gênero
- Distribuição de clientes (Member vs Normal)

### Recursos aplicados:
- Conexão direta com PostgreSQL
- Modelagem de dados
- Medidas DAX
- Filtros interativos (slicers)

📁 Arquivo do dashboard:
- powerbi/supermarket_sales_dashboard.pbix


---

## Principais Insights
- Categorias como **Personal Care** e **Fruits** lideram o faturamento
- Clientes do tipo **Member** apresentam maior participação nas vendas
- Algumas categorias apresentam diferenças relevantes de consumo entre gêneros
- O desempenho varia significativamente entre cidades, indicando oportunidades
  de estratégias regionais

---

## Próximos Passos e Melhorias Futuras
- Criar uma modelagem em estrela no banco de dados
- Automatizar a carga de dados (ETL)
- Implementar análises temporais
- Publicar o dashboard no Power BI Service
- Criar alertas e métricas avançadas no BI

---

## Fonte dos Dados
Dataset disponível no Kaggle:
Supermarket Sales Dataset

---

## Autor
**Cauã Marcelo Machado**
[LinkedIn][(https://www.linkedin.com/](https://www.linkedin.com/in/caua-machado-dev/))  
Projeto desenvolvido para fins de estudo e portfólio em Análise de Dados.
