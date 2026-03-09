# Challenge Data Science: Análise de Churn da Telecom X 📡

![Python](https://img.shields.io/badge/python-3.13-blue.svg)
![Pandas](https://img.shields.io/badge/pandas-2.0+-green.svg)
![Seaborn](https://img.shields.io/badge/seaborn-0.12-orange.svg)
![Oracle-ONE](https://img.shields.io/badge/Program-Oracle%20Next%20Education-red.svg)

---

## 📋 Sobre o Projeto

Este projeto faz parte do **Challenge 2** do programa **Oracle Next Education (ONE)**.

O objetivo foi desenvolver um pipeline completo de **ETL (Extract, Transform, Load)** e realizar uma **Análise Exploratória de Dados (EDA)** para identificar os principais fatores associados à **evasão de clientes (Churn)** em uma empresa de telecomunicações.

A partir de dados brutos extraídos de uma API, o projeto transforma as informações em dados estruturados, permitindo analisar padrões **demográficos, financeiros e contratuais** que influenciam a retenção de clientes.

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Python 3.13  
- **Manipulação de Dados:** Pandas  
- **Visualização de Dados:** Seaborn e Matplotlib  
- **Protocolos e Formatos:** Requests (API) e JSON  

---

## 📑 Etapas de Implementação

### 1. Extração e Tratamento (ETL)

- **Extração:**  
  Coleta de dados via API e normalização (*flattening*) de objetos JSON aninhados.

- **Limpeza:**  
  Identificação de inconsistências, como espaços vazios em campos numéricos, e tratamento de valores ausentes (`NaN`).

- **Transformação:**  
  - Tradução de variáveis para o português  
  - Binarização de colunas categóricas (conversão de "Sim/Não" para **1/0**)  
  - Tipagem correta de variáveis financeiras para `float64`

- **Engenharia de Atributos:**  
  Criação das colunas `Valor_Diario` e `Total_Servicos` para aprofundar a análise de consumo.

---

### 2. Análise Exploratória de Dados (EDA)

A análise seguiu quatro etapas principais:

1. **Análise Descritiva:**  
   Uso de métricas de tendência central (**Média, Mediana e Moda**) e dispersão (**Desvio Padrão**) para compreender o comportamento das variáveis.

2. **Distribuição da Evasão:**  
   Visualização da frequência absoluta e percentual da variável alvo (**Churn**).

3. **Cruzamento Categórico:**  
   Avaliação do impacto de variáveis como **tipo de contrato** e **método de pagamento** na taxa de cancelamento.

4. **Cruzamento Numérico:**  
   Análise de distribuição e relacionamento entre variáveis utilizando **Boxplots** e **Matriz de Correlação**.

---

## 📈 Principais Insights

- **Fator de Fidelidade:**  
  Clientes com menos de **10 meses de contrato** apresentam maior probabilidade de evasão.

- **Sensibilidade ao Preço:**  
  Existe uma correlação positiva entre **valor mensal elevado (`Valor_Mensal`)** e a interrupção do serviço.

- **Método de Pagamento:**  
  O pagamento via **Electronic Check** apresenta uma taxa de evasão significativamente superior aos métodos automáticos.

- **Correlação:**  
  O tempo de permanência (`Meses_Contrato`) aparece como o principal **preditor inverso de evasão** (-0.35).

---

## 📂 Estrutura do Repositório

- `challgene2_TelecomX_BR.ipynb`  
  Notebook com o código documentado e toda a análise estatística.

- `TelecomX_Dados_Processados.csv`  
  Dataset final gerado após a fase de **Carga (Load)** do processo ETL.

---

## 👨‍💻 Autor

**Artur Soares**  
Estudante de Ciência da Computação — **UFPB**  
Programa **Oracle Next Education (ONE) — Trilha Data Science**
