# Modelagem de Score de Crédito

## Contexto
Desenvolvi este projeto como parte de um desafio técnico para uma posição de Analista de Data Science Pleno/Sênior. 
O objetivo foi criar um modelo preditivo para estimar a probabilidade de inadimplência de clientes com base em seu comportamento histórico. O modelo desenvolvido obteve uma das melhores métricas do desafio, conforme feedback do gestor técnico.

## Conjunto de Dados
- **Base 1:** Lista de clientes com operações de crédito nos últimos 24 meses, incluindo características e comportamentos.
- **Base 2:** Clientes que tomaram crédito no mês seguinte à implementação do modelo, usada para avaliar seu desempenho.

## Objetivo
Construir um modelo de Machine Learning para estimar a probabilidade de inadimplência, auxiliando decisões de crédito.

## Metodologia
### 1. Diagnóstico e Preparo dos Dados
- Análise exploratória para identificar padrões e distribuições.
- Seleção de features relevantes.
- Tratamento de outliers e valores ausentes.
- Avaliação da proporção de inadimplentes e seu impacto no modelo.

### 2. Treinamento e Validação
- Implementação de **Regressão Logística**.
- Avaliação com métricas:
  - **KS Statistic:** 0,43 (forte poder preditivo).
  - **AUC-ROC:** 0,76 (alta capacidade de diferenciação entre adimplentes e inadimplentes).
- Testes para evitar overfitting.
- Identificação das variáveis mais impactantes na inadimplência.

### 3. Apresentação e Discussão
- Explicação detalhada do código ao gestor técnico.
- Feedback positivo sobre a performance e abordagem do modelo.

## Business Performance
Com o modelo de Regressão Logística desenvolvido, a instituição financeira pode estimar com precisão a probabilidade de inadimplência de cada cliente antes da concessão do crédito. O modelo atingiu uma pontuação AUROC de 0,76 e uma estatística KS de 0,426, indicando uma boa capacidade de separação entre clientes adimplentes e inadimplentes.

Com base em 100 mil clientes analisados, e considerando uma taxa de inadimplência média de 10%, estima-se que cerca de 10.000 clientes se tornariam inadimplentes. Em um cenário conservador baseado nas previsões do modelo, é possível evitar aproximadamente 30% dessas ocorrências, o que equivale a 3.000 clientes.

Assumindo um prejuízo médio de R$ 5.000 por cliente inadimplente, o uso do modelo representa uma economia potencial de R$ 15 milhões por ciclo de concessão de crédito. Ao longo de um ano, esse valor pode ultrapassar R$ 100 milhões, dependendo da frequência de renovação das carteiras.

Considerando um faturamento anual de R$ 1 bilhão para uma instituição financeira de grande porte, essa economia representa um aumento de cerca de 10% no faturamento anual.


## Resultados e Conclusão
O feedback que recebi do gestor técnico em relação a esse case foi que meu modelo alcançou uma das melhores performances do desafio.

