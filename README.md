# Estatística Aplicada
### MBA Data Science & Advanced Analytics

Este repositório centraliza os projetos práticos, estudos de caso e análises estatísticas desenvolvidas durante a disciplina de **Estatística Aplicada**. O objetivo principal é consolidar conceitos fundamentais e avançados de inferência estatística, modelagem probabilística e análise exploratória utilizando dados reais.

---

## 📁 Estrutura do Repositório e Projetos

O repositório é composto por notebooks analíticos em Python, focados em diferentes pilares da ciência de dados:

### 1. 📊 [Análise Estatística e Descritiva: Dados de Saúde e Renda](./analise_nhanes_dados_saude.ipynb)
Estudo estatístico detalhado focado em extração de insights, comportamento de distribuições e engenharia de recursos utilizando a base de dados do **NHANES** (*National Health and Nutrition Examination Survey*).
* **Destaques Técnicos:**
  * **Análise de Associação Categórica:** Cruzamento de variáveis socioeconômicas e demográficas por meio de tabelas de contingência e gráficos de barras associados.
  * **Modelagem Probabilística:** Aplicação de distribuições teóricas (**Binomial e Poisson**) para previsão de cenários e cálculo de ocorrências baseadas em taxas amostrais.
  * **Tratamento de Assimetria:** Investigação de *skewness* na renda familiar (`INDFMPIR`) e aplicação de **Transformação Logarítmica** para aproximação da distribuição normal.
  * **Engenharia de Recursos:** Padronização e redimensionamento de escalas usando `MinMaxScaler` e `StandardScaler`.

### 🚀 2. [Validação Estatística: Testes de Hipóteses e Amostragem](./analise_Amostragens_TestesHipoteses.ipynb)
Notebook voltado à aplicação prática de estatística inferencial, tomada de decisão baseada em métricas e validação de consistência metodológica.
* **Destaques Técnicos:**
  * **Testes de Hipóteses Paramétricos:** Modelagem e execução de teste $t$-Student unilateral para comparação de médias antropométricas (altura) entre grupos comportamentais.
  * **Análise Crítica de Variáveis de Confusão:** Discussão metodológica separando *relevância estatística* de *causalidade prática*, identificando o viés oculto de gênero nas métricas brutas.
  * **Validação de Amostragem Estratificada:** Aplicação de testes estatísticos bilaterais para avaliar se uma amostra reduzida e estratificada preservou as características médias (peso) da população original.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

* **Linguagem:** Python 3
* **Manipulação de Dados:** `Pandas` e `NumPy`
* **Modelagem Estatística:** `SciPy (stats)` e `Scikit-Learn` (módulos de pré-processamento)
* **Visualização de Dados:** `Matplotlib` e `Seaborn`
