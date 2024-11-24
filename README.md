# Análise Preditiva de Cogumelos

## **Inteligência Artificial**

<table>
    <tr> <td bgcolor="red"> Grupo </td> <td bgcolor="red"> RA </td>
    <tr> <td> Bruno Castro Tomaz </td> <td> 10389988 </td>
    <tr> <td> Tomás Fiorelli Barbosa </td> <td> 10395687 </td>
</table>

**Atividade**                                                                                 \
1º Bimestre (N1) - A Proposta, Dataset, Análise Exploratória/Preparação dos Dados e Relatório \
2º Bimestre (N2) - Desenvolvimento, Resultados e Relatório Completo

# Classificação de Cogumelos Comestíveis e Venenosos com Aprendizado de Máquina

Este projeto utiliza algoritmos de aprendizado de máquina para classificar cogumelos como comestíveis ou venenosos com base em suas características físicas e ecológicas. O modelo foi treinado com um dataset público e busca contribuir para a segurança alimentar, evitando o consumo acidental de cogumelos venenosos.

## Objetivo

O principal objetivo deste projeto é desenvolver um modelo preditivo que classifique cogumelos em duas categorias: **comestíveis** ou **venenosos**. A classificação é realizada utilizando técnicas de aprendizado supervisionado, com base em atributos como cor, formato, altura e habitat do cogumelo.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação utilizada para o desenvolvimento do modelo.
- **Scikit-learn**: Biblioteca utilizada para a implementação dos algoritmos de aprendizado de máquina.
- **Jupyter Notebook**: Ambiente de desenvolvimento interativo usado para análise exploratória e execução dos experimentos.
- **Pandas**: Biblioteca para manipulação e análise de dados.
- **Matplotlib e Seaborn**: Bibliotecas para visualização de dados.

## Dataset

O dataset utilizado neste projeto contém aproximadamente **61.000 registros** de cogumelos baseados em **173 espécies reais**. Cada registro inclui **22 características** que descrevem atributos físicos e ecológicos dos cogumelos. A variável alvo indica se o cogumelo é **comestível (edible)** ou **venenoso (poisonous)**.

### Principais Atributos:

- **cap-shape**: Forma do chapéu
- **cap-color**: Cor do chapéu
- **stem-height**: Altura do caule
- **gill-spacing**: Espaçamento das lamelas
- **habitat**: Habitat natural do cogumelo
- **class**: Classificação (comestível ou venenoso)

## Algoritmos Utilizados

Diversos algoritmos de aprendizado supervisionado foram testados para a tarefa de classificação:

- **K-Nearest Neighbors (KNN)**
- **Árvore de Decisão (CART)**
- **Regressão Logística**
- **Naive Bayes**
- **Support Vector Machine (SVM)**
- **Random Forest**
- **AdaBoost**

## Resultados

Os modelos foram avaliados utilizando **acurácia**, **precisão** e **recall**. Os resultados foram os seguintes:

| Algoritmo                 | Acurácia |
|---------------------------|----------|
| **Random Forest**          | 99,98%   |
| **K-Nearest Neighbors (KNN)** | 99,86%   |
| **Decision Tree**          | 99,76%   |
| **Support Vector Machine (SVM)** | 89,66%   |
| **AdaBoost**               | 79,99%   |
| **Logistic Regression**    | 78,13%   |
| **Naive Bayes**            | 66,92%   |

Os modelos **Random Forest**, **KNN** e **Decision Tree** apresentaram desempenho excepcional, com acurácia superior a 99%.

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/identificacao-cogumelos.git
   ```

2. Instale as dependências:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

3. Abra o Jupyter Notebook e execute as células para visualizar a análise exploratória e os resultados dos modelos:
   ```bash
   jupyter notebook
   ```

3. Execute os notebooks na ordem e acompanhe os resultados.