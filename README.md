# Challege-Data-Science-Latam
Desafio Curso Alura Oracle One
# 📊 Análise de Desempenho de Lojas para Tomada de Decisão

## 🎯 Objetivo do Projeto

Este projeto realiza uma análise comparativa do desempenho de quatro lojas fictícias, utilizando dados de vendas. O objetivo principal é fornecer informações e uma recomendação fundamentada para o "Sr. João" sobre qual loja apresenta os indicadores mais fracos e, portanto, seria a candidata mais indicada para venda, visando otimizar os negócios.

## ✨ Contexto

O Sr. João possui quatro lojas e precisa decidir qual delas vender. Para tomar uma decisão informada, foi realizada uma análise exploratória dos dados de vendas de cada loja, focando em métricas chave de desempenho financeiro e de satisfação do cliente.

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas Principais:**
    *   `Pandas`: Para manipulação e análise dos dados (leitura de arquivos Excel, cálculos de métricas).
    *   `Matplotlib`: Para criação das visualizações gráficas (gráficos de barras).
*   **Ambiente:** Google Colaboratory (Jupyter Notebook)
*   **Dados:** Arquivos `.xlsx` contendo informações de vendas, produtos, categorias, avaliações e frete para cada loja.

## 📈 Etapas da Análise

1.  **Carregamento dos Dados:** Leitura dos arquivos Excel (`loja.xlsx`, `loja2.xlsx`, `loja3.xlsx`, `loja4.xlsx`) para DataFrames do Pandas.
2.  **Cálculo de Métricas:**
    *   Faturamento Total por loja.
    *   Distribuição de Vendas por Categoria.
    *   Média de Avaliação dos Clientes por loja.
    *   Identificação dos Produtos Mais e Menos Vendidos por loja.
    *   Cálculo do Custo Médio do Frete por loja.
3.  **Visualização de Dados:** Criação de gráficos de barras comparativos utilizando Matplotlib para:
    *   Faturamento Total.
    *   Média de Avaliação dos Clientes.
    *   Custo Médio do Frete.
4.  **Geração do Relatório:** Consolidação dos resultados, discussão dos pontos fortes e fracos de cada loja e elaboração de uma recomendação final com justificativa.

## 💡 Principais Descobertas

*   **Loja 3:** Apresentou o melhor desempenho geral (maior faturamento e maior avaliação média).
*   **Loja 4:** Registrou o menor faturamento total, mas teve o custo de frete mais baixo.
*   **Loja 1:** Apesar de um faturamento intermediário, destacou-se negativamente pela **menor média de avaliação** dos clientes e pelo **maior custo médio de frete**.
*   **Loja 2:** Mostrou um desempenho sólido e equilibrado, sem grandes pontos fracos.

## ⭐ Recomendação Final

Com base na análise combinada dos indicadores, a recomendação para o Sr. João é a **venda da Loja 1**.

**Justificativa:** A combinação da pior avaliação média (indicando problemas de satisfação do cliente) e o maior custo de frete (potencial barreira de compra) sugere que a Loja 1 possui desafios operacionais ou de percepção de mercado mais críticos do que o baixo faturamento isolado da Loja 4.

## 🚀 Como Executar

1.  Certifique-se de ter Python 3 instalado.
2.  Instale as bibliotecas necessárias:
    ```bash
    pip install pandas matplotlib openpyxl
    ```
3.  Clone este repositório ou baixe os arquivos.
4.  Certifique-se de que os arquivos de dados (`loja.xlsx`, `loja2.xlsx`, `loja3.xlsx`, `loja4.xlsx`) estejam na mesma pasta que o script ou notebook.
5.  Execute o notebook Jupyter (`.ipynb`) ou o script Python (`.py`) que contém o código da análise. Os gráficos e o relatório final serão gerados como saída.

## 📝 Sueli da Hora Moreira



