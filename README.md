# Projeto de Previsão de Crédito com Árvore de Decisão

## Descrição

Neste projeto, foi utilizado o algoritmo de Árvore de Decisão para prever o crédito de clientes. O objetivo é prever se um cliente terá um crédito aprovado ou não, com base em suas características financeiras e comportamentais. O modelo foi treinado com um conjunto de dados e comparado com o desempenho de um modelo anterior que utilizava o algoritmo Naive Bayes.

Este projeto também explora a redução de variáveis, utilizando apenas as duas principais features mais relevantes para a previsão e avaliando o impacto dessa mudança no desempenho do modelo.

## Objetivos do Projeto

- **Aplicação do algoritmo de Árvore de Decisão** para prever o crédito de clientes.
- **Comparação do desempenho** do modelo de Árvore de Decisão com o modelo de Naive Bayes.
- **Análise da importância das variáveis** para prever o crédito e a seleção das 2 features mais importantes.
- **Avaliação da acurácia, precisão, recall e F1-score** para determinar a eficácia dos modelos.

## Tecnologias Utilizadas

- **Python** (linguagem de programação)
- **Pandas** (manipulação de dados)
- **Scikit-learn** (bibliotecas para aprendizado de máquina)
- **Seaborn** e **Matplotlib** (visualização de dados)
- **Jupyter Notebook** (ambiente de desenvolvimento)

## Passos do Projeto

1. **Carregamento e preparação dos dados**:
   - Os dados foram carregados a partir de arquivos CSV e preparados para o modelo, com tratamento de valores ausentes e transformação de variáveis categóricas.
   
2. **Treinamento do modelo de Árvore de Decisão**:
   - O modelo foi treinado utilizando o critério de Gini e um random state fixo para garantir a reprodutibilidade dos resultados.

3. **Avaliação do modelo**:
   - O desempenho do modelo foi avaliado utilizando a matriz de confusão, acurácia, precisão, recall e F1-score.
   - Foi comparado o desempenho do modelo de Árvore de Decisão com o modelo de Naive Bayes.

4. **Redução das variáveis**:
   - As 2 principais features mais relevantes foram identificadas e utilizadas para treinar uma nova árvore de decisão.
   - A acurácia e outros indicadores de desempenho foram avaliados novamente para verificar a eficácia da simplificação do modelo.

## Resultados

- A **acurácia do modelo de Árvore de Decisão** no conjunto de treinamento foi 99.97%, indicando um bom ajuste aos dados de treino.
- No conjunto de teste, o desempenho do modelo foi comparado com o do Naive Bayes, onde o Naive Bayes apresentou um desempenho superior em alguns casos, especialmente em relação ao recall.

## Conclusão

- O modelo de Árvore de Decisão, embora eficaz, não superou o modelo de Naive Bayes em todos os aspectos.
- A redução de variáveis para as 2 mais importantes diminuiu a complexidade do modelo, mas resultou em uma leve queda na acurácia. No entanto, esse processo é útil para simplificação e melhor interpretação do modelo.

## Como Executar

1. Instale as dependências:
   ```bash
   pip install pandas scikit-learn seaborn matplotlib
