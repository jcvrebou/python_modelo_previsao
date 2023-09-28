# CATEGORIZAR NOVOS CLIENTES COM BASE EM MODELO DE PREVISÃO

### Introdução

Este projeto tem como objetivo prever a classificação de novos clientes, a partir da análise de clientes já existentes na base de dados. O objetivo é identificar, a partir de dados categóricos e numéricos, clientes standard, good e poor. Os dados utilizados não são reais e servem apenas para estudo.

<span style="color:red">**_Case: Score de Crédito dos Clientes_**</span>

**_Você foi contratado por um banco para conseguir definir o score de crédito dos clientes. Você precisa analisar todos os clientes do banco e, com base nessa análise, criar um modelo que consiga ler as informações do cliente e dizer automaticamente o score de crédito dele: Ruim, Ok, Bom._**

## Passo a passo do Projeto

<span>**Passo 1: Importando e analisando previamente os tipos de dados inseridos na base**</span>

<span>**Passo 2: Efetuando tratamento na base de dados para posterior processamento**</span>

- Importar a base de dados
- Verificar informações vazias
- Fazer o tratamento na base de dados
- Selecionar as colunas de treino para o modelo
- Treinar 2 modelos
- Verificar o melhor modelo
- Verificar quais as características mais importantes para definir o score do cliente

<span>**Passo 3: Criar o modelo de IA**</span>

- Informações para treinar o modelo de classificação
- Separar em variáveis de treino e teste
- Modelos utilizados: [Modelo Árvore de Decisão](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html#sklearn.ensemble.RandomForestClassifier) e [Modelo Vizinhos Mais Próximos](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html#sklearn-neighbors-kneighborsclassifier)

<span>**Passo 4: Escolhendo o melhor modelo**</span>

- Aplicar os dois modelos de classificação para treinamento e verificar qual possui maior acurácia.

<span>**Passo 5: Fazer novas previsões**</span>

- A partir do modelo testado e escolhido pela maior acurácia, aplicá-lo para novos clientes já que o modelo está treinado e foi testado.

**negrito**

##### Nota: Toda a codificação foi feita por este usuário, sem cópia de código, a partir da aula "Inteligência Artificial e Previsões" do canal Hashtag Programação.

[Hashtag Programação - Python IA: Inteligência Artificial e Previsões | Jornada Python [Aula 3]](https://www.youtube.com/watch?v=V3OcwhtPgqw)
