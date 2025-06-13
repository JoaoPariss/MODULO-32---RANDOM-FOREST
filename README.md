# Módulo 32 - Random Forest: Classificação Multiclasse com Avaliações de Vinhos 🍷🌲

Este projeto faz parte do **Módulo 32** do curso de Data Science, com foco na aplicação do algoritmo **Random Forest** para resolver um problema de **classificação multiclasse**. A base de dados utilizada contém **avaliações de vinhos**, e o objetivo principal é **prever a pontuação** dos vinhos com base em diversas características.

---

## 📊 1. Pré-Processamento dos Dados

### A) Análise Exploratória
- Utilização da função info() para verificar se a base continha dados faltantes e se os tipos de dados estavam corretos.
- Utilização da função `describe()` para entender a distribuição estatística dos dados e identificar possíveis **outliers**.
  
### B) Verificação do Balanceamento
- Avaliação do balanceamento da variável **Target** (pontuação do vinho).

### C) Análise de Correlação
- Visualização gráfica e/ou tabular das correlações entre as variáveis.
- Identificação das variáveis com **maior correlação positiva ou negativa** com a variável alvo.

### D) Seleção de Variáveis
- Criação de um novo DataFrame contendo apenas as variáveis com **maior relevância** para o modelo.

---

## 🧹 2. Preparação Final dos Dados

### A) Separação de Variáveis
- Separação da base em **X (features)** e **Y (target)**.

### B) Treinamento e Teste
- Divisão da base de dados em **conjuntos de treino e teste**, utilizando `train_test_split`.

---

## 🌲 3. Modelagem com Random Forest

### A) Treinamento Inicial
- Inicialização e treinamento de um modelo de **Random Forest Classifier** com parâmetros padrão.

### B) Previsão
- Aplicação do modelo sobre a base de teste.

---

## 📈 4. Avaliação do Modelo

- Cálculo e interpretação das principais **métricas de classificação**:
  - Acurácia
  - Precisão
  - Recall
  - F1-Score
  - Matriz de Confusão

- Discussão de **insights** baseados nos resultados obtidos.

---

## 🔧 5. Otimização de Hiperparâmetros

### A) Definição do Grid
- Criação de um **conjunto de hiperparâmetros** a ser testado.

### B) Random Search
- Utilização do `RandomizedSearchCV` para testar combinações de hiperparâmetros e encontrar a melhor configuração.

### C) Avaliação do Modelo Otimizado
- Avaliação final do novo modelo treinado com os **melhores hiperparâmetros** encontrados.
