![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![PySpark](https://img.shields.io/badge/Spark-3.5-orange)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-Em%20Desenvolvimento-yellow)

#  Desafio Técnico – Hackathon Forecast Big Data 2025

## Objetivo

O desafio consiste em desenvolver um modelo de previsão de vendas (forecast) para apoiar o varejo na reposição de produtos.
A tarefa é prever a quantidade semanal de vendas por PDV (Ponto de Venda) / SKU (Stock Keeping Unit) para as cinco semanas de janeiro/2023, utilizando como base o histórico de vendas de 2022.

Esse é um problema real, baseado no produto One-Click Order da Big Data.
---

## Dados Disponíveis

- **Treino (2022)**: transações (data, PDV, produto, quantidade, faturamento), cadastro de produtos e PDVs.  
- **Teste (jan/2023)**: mesma estrutura (não compartilhado, usado apenas na avaliação).  

---

## 🧾 Entregáveis

1. Arquivo **CSV (sep=;) ou Parquet**, UTF-8, com colunas:  

```text
semana;pdv;produto;quantidade
1;1023;123;120
2;1045;234;85
3;1023;456;110
````

2. Repositório no GitHub com:
- Código completo + documentação.  
- Instruções de execução.

---

## Execução
### Análise de dados

```bash
pip install requirements.txt
```

### Modelagem

```bash
pip install requirements_model.txt
```

---
## Estrutura

├── Base_de_dados/        # dados de treino
├── dados_tratados/ 
├── Notebooks/   # EDA e protótipos
├── Requerements/
├── Desafio Técnico – Hackathon Forecast Big Data 2025.docx
├── previsao_demanda.csv

└── README.md

---
## Avaliação

- Performance do modelo (métrica oficial).
- Clareza e organização do código.
- Criatividade na modelagem.
- Superar baseline da Big Data.

---

## Cronograma

- Inscrições: até 08/09
- Lançamento: 09/09
- Submissões: 09–21/09
- Validação: 22–26/09
- Vencedores: 29/09
