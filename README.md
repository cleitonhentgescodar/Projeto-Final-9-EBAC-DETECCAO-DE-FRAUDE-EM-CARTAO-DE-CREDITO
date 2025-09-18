# 🛡️ Detecção de Fraude em Cartão de Crédito  

Este projeto tem como objetivo desenvolver e avaliar modelos de *Machine Learning* para **detecção de fraudes em transações com cartão de crédito**.  

## 📊 Sobre o Dataset  
- Arquivo: **Base_M43_Pratique_CREDIT_CARD_FRAUD.csv**  
- Tamanho: ~143 MB  
- Registros: 284.807 transações  
- Atributos: 31 colunas  
  - `Time`: tempo em segundos desde a primeira transação  
  - `V1` a `V28`: variáveis geradas por **PCA** (dados confidenciais protegidos)  
  - `Amount`: valor da transação  
  - `Class`: variável alvo (0 = normal, 1 = fraude)  

O dataset é altamente **desbalanceado**, com uma minoria de transações fraudulentas.  

## 🔍 Etapas do Projeto  
1. **Análise Exploratória (EDA)**  
   - Distribuição de valores (`Amount`)  
   - Identificação de outliers  
   - Análise de classes (`Class`)  

2. **Pré-processamento**  
   - Remoção de valores ausentes  
   - Normalização/Escalonamento  
   - Divisão em treino e teste  

3. **Modelagem**  
   - Aplicação de algoritmos de classificação para detecção de fraude  
   - Tratamento do desbalanceamento de classes  

4. **Avaliação**  
   - Matrizes de confusão  
   - Métricas: *Acurácia, Precisão, Recall, F1-score, AUC-ROC*  

## 🛠️ Tecnologias Utilizadas  
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)  
- Jupyter Notebook  

## 📌 Observações  
- O foco principal é **lidar com dados desbalanceados** e treinar modelos capazes de identificar fraudes com alta sensibilidade.  
- Este projeto faz parte da formação da **EBAC**.  
