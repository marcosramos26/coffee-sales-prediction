☕ Coffee Sales Prediction – EDA & Machine Learning
📌 Sobre o Projeto

Este projeto tem como objetivo analisar um dataset de vendas de café e aplicar técnicas de Análise Exploratória de Dados (EDA) e Machine Learning para prever o valor gasto por transação (money) a partir de variáveis como tipo de café, horário da compra e período do dia.

O fluxo seguido foi:

Exploração inicial dos dados (EDA)

Limpeza e pré-processamento

Geração de insights estatísticos

Construção de modelo de Machine Learning (Regressão Linear)

Validação e avaliação de performance

📊 Dataset

Fonte: Coffee Sales Dataset (arquivo .csv)

Principais colunas:

hour_of_day → Hora da compra (0–23)

coffee_name → Tipo de café comprado

money → Valor gasto na transação

Time_of_Day → Período do dia (Morning, Afternoon, Night)

Weekday / Weekdaysort → Dia da semana

Month_name / Monthsort → Mês da compra

Date, Time → Data e hora da compra

🔍 Análise Exploratória (EDA)

Distribuição de valores (money) → maioria entre 27 e 35, sem outliers significativos.

Mais vendidos: Americano with Milk e Latte.

Horários de pico: entre 9h e 11h, e entre 15h e 17h.

Meses de maior movimento: Fevereiro, Março e Outubro.

Meses mais fracos: Janeiro, Abril e Junho.

🤖 Machine Learning
Modelo aplicado: Regressão Linear

Features: hour_of_day, coffee_name, Time_of_Day, Weekdaysort, Monthsort.

Target: money.

Pré-processamento:

StandardScaler para variáveis numéricas.

OneHotEncoder para variáveis categóricas.

📈 Resultados:

MSE (Treino/Teste): 0.53 / 0.54

R² (Treino/Teste): 0.98 / 0.98

✅ O modelo apresentou excelente performance, generalizando bem e sem sinais de overfitting.

🛠️ Tecnologias Utilizadas

Python (pandas, numpy, matplotlib, seaborn, scikit-learn)

Jupyter Notebook
