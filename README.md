# 📊 Análise de Desempenho: Alura Store

Este projeto faz parte do primeiro desafio prático da Especialização em Data Science do programa **Oracle Next Education (ONE)**. O objetivo é atuar como analista de dados para auxiliar o Senhor João na decisão estratégica de qual unidade de sua rede de e-commerce deve ser vendida para reinvestimento em um novo negócio.

## 🎯 Objetivo do Desafio
Analisar métricas de desempenho de 4 lojas distintas para identificar a unidade com menor eficiência global, baseando-se em:
* **Faturamento Total:** Quanto cada loja gera em vendas.
* **Categorias Mais Populares:** Identificação dos nichos de maior saída.
* **Média de Avaliação:** Nível de satisfação dos clientes.
* **Eficiência Logística:** Análise do custo médio do frete.

## 🛠️ Tecnologias Utilizadas
* **Python 3**
* **Pandas**: Manipulação, limpeza e unificação de dados (ETL).
* **Matplotlib**: Criação de visualizações gráficas (Barras, Linhas e Barras Empilhadas).
* **Google Colab**: Ambiente de desenvolvimento em nuvem.

## 📈 Resultados da Análise

Após a unificação das bases de dados e aplicação de técnicas de agrupamento, chegamos aos seguintes indicadores:

* **Desempenho Financeiro:** A **Loja 4** apresentou o menor faturamento da rede (R$ 1.384.497,58), ficando significativamente atrás da unidade líder, Loja 1.
* **Satisfação:** Embora as notas sejam equilibradas, a **Loja 1** detém a menor média (3.97), enquanto a **Loja 3** é a favorita do público (4.04).
* **Logística:** A **Loja 4** possui o frete mais barato (R$ 31,27), porém essa vantagem não se traduziu em aumento de volume de vendas ou faturamento superior.
* **Mix de Produtos:** As categorias de **Móveis** e **Eletrodomésticos** são os pilares da Alura Store, enquanto as categorias de **Livros** e **Eletrônicos** específicos apresentaram os menores volumes de saída.

## 🏆 Recomendação Final

Com base nos dados extraídos, a recomendação técnica apresentada ao Senhor João é a **venda da Loja 4**.

**Justificativa:** Apesar de possuir um custo logístico eficiente, a unidade apresenta o menor retorno financeiro bruto. Para o objetivo de levantar capital imediato para um novo empreendimento, o desinvestimento na unidade com menor faturamento é a estratégia mais segura para a saúde do ecossistema de negócios do Senhor João.

## 📁 Estrutura do Repositório
* `challenge1_data_science.ipynb`: Notebook com todo o código Python, manipulação de dados e relatório final.
* `README.md`: Documentação e resumo executivo do projeto.

## 🚀 Como Executar
1. Clone este repositório.
2. Faça o upload do arquivo `.ipynb` para o [Google Colab](https://colab.research.google.com/).
3. Execute todas as células para visualizar o processamento de dados e os gráficos gerados.
