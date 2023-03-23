📊 Desafio de Classificação da [TERA](https://somostera.com/)

Este desafio é parte da minha formação na pós-graduação de [Data Science & Machine Learning](https://somostera.com/cursos/data-science-machine-learning) da TERA.

## 🧑🏼‍🔬 Sobre o Desafio.

### Problema:
Desenvolver uma solução para um problema de classificação de transações de cartão de crédito como fraude ou normal.

### Etapas do desafio:
- Parte 1: Revisão Bibliográfica.
  - Leitura de artigos sobre o problema para entender o ciclo completo da solução, as principais técnicas já aplicadas e onde a solução desenvolvida neste trabalho se encaixa na solução geral.
- Parte 2: Tratamento de dados.
  - Definir algumas regras de negócio para dividir dados em categorias, aplicar feature engineering e preparar os dados para os cálculos do modelo.
- Parte 3: Treinar e aplicar ML.
  - Separar os dados em teste e treino e inseri-los nos modelos de machine learning utilizados para solucionar este problema.
- Parte 4: Melhorar a solução.
  - Alterar parâmetros e técnicas utilizadas para melhorar o modelo que teve o melhor desempenho e obter os resultados finais.

## 🗂️ Sobre as fontes dos dados.

Os dados estão relacionados a transações com cartão de crédito, que possem as seguintes informações:
* Hora da transação
* ID de quem fez
* ID de quem recebeu
* Saldo inicial de quem fez
* Saldo inicial de quem recebeu
* Saldo depois da transação de quem fez
* Saldo depois da transação de quem recebeu
* Quantidade transacionada
* Se é fraude ou não [target]
* se foi marcada como fraude (variável sintética criada através do conhecimento do negócio, que marca como fraude p valores altos de transação)

Para mais informações pesquisar [neste trabalho](https://somostera.com/) do Kaggle.



## 🎯 Objetivo do estudo

Criar uma modelo que consiga classificar com precisão e baixa latência uma transação no momento em que ela foi feita. No notebook disponibilizado neste repositório existe a parte de contextualização do problema onde é possível entender todo ciclo da solução e as particularidades deste desenvolvimento.
