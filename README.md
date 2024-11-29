# Projeto de Análise Musical de Tyler, the Creator




## Visão Geral
Este projeto aplica técnicas avançadas de aprendizado de máquina para analisar o catálogo musical de Tyler, the Creator, utilizando metodologias de ciência de dados que incluem regressão, classificação e agrupamento para revelar insights sobre as características musicais do artista.

## Objetivos do Projeto
O projeto visa explorar a paisagem musical de Tyler, the Creator por meio de três abordagens distintas de aprendizado de máquina:

### 1. Previsão de Popularidade (Regressão)
**Objetivo:** Desenvolver um modelo de regressão para prever a popularidade das músicas com base em atributos musicais.

**Características Principais:**
- Recursos de Entrada: Valência (positividade musical) e Tempo (BPM)
- Variável Alvo: Popularidade da Música
- Metodologia: Análise de regressão preditiva para compreender como características musicais influenciam a recepção das músicas

### 2. Classificação de Álbuns
**Objetivo:** Criar um modelo de classificação para prever o álbum de origem das músicas de Tyler.

**Características Principais:**
- Recursos de Entrada:
  - Volume (Loudness)
  - Energia
  - Dançabilidade
  - Acousticidade
  - Valência
  - Ano de Lançamento
- Metodologia: Algoritmo de classificação de aprendizado de máquina para categorizar músicas por seu álbum de origem

### 3. Agrupamento de Estilo Musical
**Objetivo:** Realizar agrupamento não supervisionado para agrupar músicas com características musicais semelhantes.

**Características Principais:**
- Atributos de Agrupamento:
  - Instrumentalidade
  - Acousticidade
  - Discursividade (Speechiness)
  - Dançabilidade
- Metodologia: Aprendizado não supervisionado para identificar agrupamentos naturais no estilo musical de Tyler

## Stack Técnico
- Linguagem de Programação: Python
- Bibliotecas Principais:
  - Pandas (Manipulação de Dados)
  - Scikit-learn (Aprendizado de Máquina)
  - Matplotlib/Seaborn (Visualização)
  - NumPy (Computação Numérica)

## Resultados Esperados
- Modelo preditivo de popularidade musical
- Sistema de classificação de álbuns
- Insights de agrupamento de estilo musical
- Visualização da evolução musical de Tyler, the Creator

## Limitações
- Análise baseada em recursos do dataset disponivel
- Dependência da qualidade e abrangência do conjunto de dados
- Possíveis vieses nos modelos de machine learning

## Contribuições
Contribuições são bem-vindas! Por favor, abra um issue ou envie um pull request.
