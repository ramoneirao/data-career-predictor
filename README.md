# Data Career Predictor

Este repositório contém um Jupyter Notebook desenvolvido como trabalho final da disciplina de Inteligência Artificial na Universidade Federal do Pará (UFPA). O projeto tem como objetivo prever o cargo ideal para um candidato na área de dados utilizando técnicas de Machine Learning e o conjunto de dados do estudo *State of Data Brazil 2022*.

## Sobre o Projeto
O trabalho segue o processo KDD (Knowledge Discovery in Databases) para extrair insights e construir modelos de classificação. As principais etapas envolvidas são:

1. **Seleção de Dados**: Análise exploratória e escolha dos atributos mais relevantes.
2. **Pré-processamento**: Tratamento de dados faltantes e inconsistentes, além da criação de novos atributos.
3. **Formatação**: Conversão dos dados para um formato adequado para modelagem.
4. **Mineração de Dados**: Treinamento e avaliação de dois modelos de classificação.
5. **Avaliação**: Comparação dos modelos para determinar a melhor abordagem.

## Tecnologias Utilizadas
- Python  
- Jupyter Notebook  
- Pandas, NumPy, Matplotlib, Seaborn (para análise e visualização de dados)  
- Scikit-learn (para modelagem e avaliação de classificadores)  

## Como Executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/ramoneirao/data-career-predictor.git
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Abra o Jupyter Notebook:
   ```bash
   jupyter notebook data-career-predictor.ipynb
   ```
4. Execute as células do notebook para visualizar a análise e os resultados.

## Modelos Utilizados
O projeto implementa dois modelos de Machine Learning, escolhidos entre as seguintes opções:
- Máquina de Vetor de Suporte
- Regressão Logistica

## Referências
- [State of Data Brazil 2022](https://www.kaggle.com/datasets/datahackers/state-of-data-2022)  
- Documentação oficial das bibliotecas utilizadas: [Pandas](https://pandas.pydata.org/), [Scikit-learn](https://scikit-learn.org/), [Matplotlib](https://matplotlib.org/)

---

**Autor:** Ramon Neirão Mendes  
**Contato:** ramonneirao@gmail.com
