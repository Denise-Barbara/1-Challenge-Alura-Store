# 1-Challenge-Alura-Store
# Projeto de Análise de Eficiência da Rede Alura Store

## 🎯 Propósito da Análise

Este projeto tem como objetivo principal auxiliar o Senhor João, proprietário da rede Alura Store, a tomar uma decisão estratégica: **qual das suas quatro lojas (Loja, Loja 2, Loja 3, Loja 4) deve ser vendida para iniciar um novo empreendimento.**

Para isso, realizamos uma análise detalhada de dados de vendas, desempenho e avaliações de cada loja, buscando identificar a loja com menor eficiência com base em métricas-chave.

## 📁 Estrutura do Projeto e Organização dos Arquivos

O projeto é organizado da seguinte forma:

* `loja_1.csv`: Dados transacionais da Loja 1.
* `loja_2.csv`: Dados transacionais da Loja 2.
* `loja_3.csv`: Dados transacionais da Loja 3.
* `loja_4.csv`: Dados transacionais da Loja 4.
* `seu_notebook_do_colab.ipynb` (ou o nome que você deu ao seu arquivo no Colab): O notebook principal contendo todo o código Python para a análise, incluindo carregamento de dados, cálculos de métricas e geração de visualizações.
* `./graficos/` (ou na mesma pasta do notebook): Pasta onde os gráficos gerados são salvos.

## 📊 Análises Realizadas e Insights Obtidos

A análise foi focada nas seguintes métricas para cada loja:

* **Faturamento Total:** A soma total das vendas de produtos.
* **Vendas por Categoria:** A contagem de vendas para cada categoria de produto.
* **Média de Avaliação das Lojas:** A satisfação média dos clientes com as compras.
* **Produtos Mais e Menos Vendidos:** Quais produtos se destacam positiva e negativamente em volume de vendas.
* **Frete Médio por Loja:** O custo médio do frete associado às vendas.

### Exemplos de Gráficos e Insights:

Durante a análise, foram gerados diversos gráficos para facilitar a visualização e comparação. Abaixo estão exemplos dos tipos de visualizações criadas:

* **Faturamento Total por Loja:**
    ![Faturamento Total por Loja](faturamento_total_por_loja.png)
    *Insight:* Este gráfico permite identificar rapidamente qual loja tem a maior e a menor receita total.

* **Média de Avaliação dos Clientes por Loja:**
    ![Média de Avaliação dos Clientes por Loja](media_avaliacao_por_loja.png)
    *Insight:* Compara a percepção geral dos clientes sobre cada loja.

* **Média de Frete por Loja:**
    ![Média de Frete por Loja](media_frete_por_loja.png)
    *Insight:* Ajuda a entender as variações nos custos de frete e sua possível influência na eficiência da loja.

* **Top 10 Vendas por Categoria (Exemplo Loja 1):**
    ![Vendas por Categoria Loja 1](vendas_por_categoria_loja1.png)
    *Insight:* Mostra as categorias de produtos que mais contribuem para o volume de vendas de cada loja.

* **Top 10 Produtos Mais Vendidos (Exemplo Loja):**
    ![Top 10 Produtos Mais Vendidos Loja](top10_produtos_mais_vendidos_loja.png)
    *Insight:* Destaca os produtos que são os "carros-chefes" de cada unidade.

* **Top 10 Produtos Menos Vendidos (Exemplo Loja):**
    ![Top 10 Produtos Menos Vendidos Loja](top10_produtos_menos_vendidos_loja.png)
    *Insight:* Aponta os produtos com baixo desempenho que podem estar impactando negativamente a loja.

### Recomendação Preliminar (Baseada nas análises):

Após a análise dos dados de faturamento, avaliações, categorias e produtos mais/menos vendidos, e o frete médio, a **Loja 4** foi identificada como a provável candidata para ser vendida. Embora apresente o menor frete médio, é a loja com o menor faturamento total entre todas, indicando uma menor eficiência geral em termos de geração de receita. As outras lojas demonstram maior performance em faturamento e/ou avaliações.

## 🚀 Como Executar o Notebook

Para replicar as análises e visualizar os resultados, siga os passos abaixo:

1.  **Faça o Upload dos Dados:**
    * No seu ambiente Google Colab, clique no ícone de pasta (arquivos) no painel esquerdo.
    * Clique no ícone de "upload" (seta para cima) e faça o upload dos arquivos `loja_1.csv`, `loja_2.csv`, `loja_3.csv`, e `loja_4.csv` para o ambiente do Colab.
2.  **Abra o Notebook:**
    * Abra o arquivo `.ipynb` do projeto no Google Colab.
3.  **Execute as Células:**
    * Execute cada célula do notebook sequencialmente. Você pode fazer isso clicando no botão "Play" de cada célula ou usando `Shift + Enter`.
    * Certifique-se de que todas as bibliotecas necessárias (Pandas, Matplotlib) estão instaladas (o Colab geralmente já vem com elas).
4.  **Visualize os Resultados:**
    * Os resultados de texto serão impressos diretamente no output das células.
    * Os gráficos serão exibidos abaixo das células onde foram gerados e também serão salvos como arquivos PNG no diretório do Colab.

---
*Este README.md foi criado como parte de um desafio de análise de dados para o projeto Alura Store.*
