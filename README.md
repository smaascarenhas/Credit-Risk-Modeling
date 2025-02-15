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

## Resultados e Conclusão
O feedback que recebi do gestor técnico em relação a esse case foi que meu modelo alcançou uma das melhores performances do desafio.

