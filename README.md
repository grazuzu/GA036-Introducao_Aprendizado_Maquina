# GA036-Introducao_Aprendizado_Maquina

## Classificação de Cálculos Biliares

Este repositório contém o código para classificação de pacientes com diagnóstico de cálculos biliares utilizando **Regressão Logística** e **Random Forest**.

## Estrutura do Repositório

- `dataset/` : dados brutos e processados
- `notebooks/` : notebooks com análise exploratória e visualizações

## Notebooks por Conjunto de Dados

O repositório contém notebooks organizados em quatro conjuntos de dados, permitindo avaliar o impacto da seleção de features e do tratamento de outliers pelo intervalo interquartil (IQR) nos modelos de aprendizado de máquina.

- **Conjunto 1**  
  Todas as features do conjunto original **com remoção de outliers pelo IQR**. Inclui pré-processamento, treino de Regressão Logística e Random Forest, validação cruzada e avaliação das métricas.

- **Conjunto 2**  
  Todas as features do conjunto original **sem aplicação do IQR**. Permite comparar o efeito do tratamento de outliers no desempenho dos modelos.

- **Conjunto 3**  
  Features selecionadas, removendo variáveis com desbalanceamento significativo (com base nas distribuições da Figura de referência), **com aplicação de IQR**. Avalia o impacto combinado da seleção de atributos e remoção de outliers.

- **Conjunto 4**  
  Mesmas features selecionadas do Conjunto 3, **sem aplicação do IQR**. Permite comparar o efeito isolado da seleção de atributos sem tratamento de outliers.
