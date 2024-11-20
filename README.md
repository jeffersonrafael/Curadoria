# Estude ciência de dados de ponta a ponta com a ajuda da metodologia CRISP-DM
<!-- ![Capa do readme](https://github.com/jeffersonrafael/Curadoria/blob/main/Assets/studying-hard.gif)-->

<p align="center">
  <img src="https://github.com/jeffersonrafael/Curadoria/blob/main/Assets/studying-hard.gif" alt="Capa do readme" width="500" height="393">
</p>


# Conceitos importantes de cada etapa

---

## Índice

- [Conceitos importantes de cada etapa](#conceitos-importantes-de-cada-etapa)
  - [Índice](#índice)
  - [Etapa 2 - Data understanding](#etapa-2---data-understanding)
  - [Etapa 3 - Data preparation](#etapa-3---data-preparation)
  - [Etapa 4 - Modeling](#etapa-4---modeling)
  - [Etapa 5 - Evaluation](#etapa-5---evaluation)
  - [Etapa 6 - Deployment](#etapa-6---deployment)
- [Links importantes](#links-importantes)



## Etapa 2 - Data understanding

- Quais dados são categóricos?
- Quais dados são numéricos?
- Quais dados object são strings?
- O tipo das datas esta correto?
- Balanceamento dos dados
  - https://en.wikipedia.org/wiki/Data_augmentation
- Cardinalidade dos dados categóricos
- Quais são os significados dos valores desta feature (coluna ou variável)?
- O que significa esta feature?
- dados estruturados
    - dados tabulares
- dados não estruturados
    - textos
    - imagem
- Análise exploratória dos dados
    - Estatistica descritica
    - Fazendo perguntas
- Visualização
  - t-SNE
    - https://observablehq.com/@robstelling/t-sne
    - https://observablehq.com/@robstelling/abrindo-a-caixa-preta-do-t-sne/2
    - https://en.wikipedia.org/wiki/T-distributed_stochastic_neighbor_embedding
    - https://medium.com/@violante.andre/an-introduction-to-t-sne-with-python-example-47e6ae7dc58f
    - https://distill.pub/2016/misread-tsne/
    - Kullback–Leibler divergence (Entropia relativa): https://en.wikipedia.org/wiki/Kullback%E2%80%93Leibler_divergence
- Processamento de sinal

## Etapa 3 - Data preparation

- Limpeza dos dados
    - Missing values: Dados ausentes. Há 3 tipos de dados ausentes.
        - **Missing completely at random (MCAR)**
        - **Missing at random (MAR)**
        - **Missing not at random (MNAR)**
- Data Leakage
    - A necessidade de separar os dados de treino e teste para evitar a “contaminação” das informações presentes no conjunto de dados de treino no conjunto de dados de teste.
- Transformação dos dados ou Feature scaling
- Feature Selection
- Feature Extraction
    - Redução de dimensionalidade
        - PCA
- Remoção dos Outiliers

## Etapa 4 - Modeling

- Modelo de classificação
- Modelo de regressão
- Modelo de linguagem
- Series Temporais
  - https://otexts.com/fpp2/
- Dados sequenciais
- Fine Tuning
- Algoritmos de otimização
    - Otimização de hiperparametros
        - Grid Search
        - Random Search
        - Bayes Search
        - Heuristicas
        - Meta-heuristicas
    - Gradiente descendente
        - estocastico
        - batch
    - Algoritmo genético
- Transfer learning
- Self-supervised learning
- Aprendizado supervisionado
- Aprendizado Não-supervisionado
- Aprendizado por reforço
- Aprendizado semi-supervisionado
- Aprendizado por reforço com feedback humano
- Ensemble learning
    - Voting
    - Boosting
    - Bagging
    - One-vs-One
    - One-vs-Rest
- Forecasting
- Nowcasting
- Deep learning

## Etapa 5 - Evaluation

- Interpretabilidade
    - Interpretando arvores
    - Shapley values
    - Feature importance
    - Permutation importance
- Bias and Variance
    - Overfiting
    - Underfiting
- Classificação
    - acuracia
    - precisão
    - recall
    - sensitividade
    - especificidade
- Regressão
    - RMSE
    - MSE
- Imagem
- Geodata
- Processamento de sinais
- Audio
- Classificação de token
- Classificação de texto

## Etapa 6 - Deployment

- Streamlit
- Relatorio
- Apps
- Algoritmos de recomendação
- 

# Links importantes

---

PPT do CRISP-DM: https://docs.google.com/presentation/d/1wHHAKpbymizqoLf2VDALYVQqgOBwjmDePuHtvFTXx5A/edit?usp=sharing

Limpeza dos dados 1: https://ealexbarros.medium.com/principais-tipos-de-dados-faltantes-missing-em-um-dataset-49aa35cf18c8

Limpeza dos dados 2: https://medium.com/data-hackers/feature-engineering-técnicas-para-lidar-com-dados-faltantes-em-um-projeto-de-ciência-de-dados-debdd57eb662

Feature Engeneering: https://www.bing.com/search?q=feature+engineering+for+machine+learning&qs=SC&pq=featue+engen&sk=SC2&sc=9-12&cvid=60451BC494134768B7977FD254F02314&FORM=QBRE&sp=3&ghc=1&lq=0

Deplo: https://chatgpt.com/c/671704f8-c6a8-800c-a08d-439fd78e72b4

Pasta com uma curadoria de conteúdos: https://drive.google.com/drive/folders/1chwXQtiQgxrGr7EdwN8YW-P2VU9StV6T?usp=sharing

https://medium.com/@shawn.chumbar/the-crisp-dm-process-a-comprehensive-guide-4d893aecb151
