# 📊 Análise Exploratória de Dados – Escolas de NYC

## 📌 Visão Geral
Este projeto realiza uma análise exploratória de dados (EDA) com foco no desempenho escolar
de escolas de Nova York, utilizando métricas do SAT e médias em matemática.

O objetivo é identificar:
- Escolas com melhor desempenho em matemática
- As 10 escolas com melhor desempenho geral com base na pontuação total do SAT

O projeto foi desenvolvido como parte de um projeto prático da DataCamp.

---

## 🛠️ Ferramentas Utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Fonte dos Dados
O conjunto de dados contém informações sobre escolas de NYC, incluindo:
- Nome da escola
- Média em matemática
- Média em leitura
- Média em escrita

---

## 🔍 Etapas da Análise

### 1️⃣ Importação e Preparação dos Dados
- Leitura do dataset `schools.csv`
- Inspeção inicial das colunas e valores

### 2️⃣ Análise de Desempenho em Matemática
- Filtragem de escolas com média em matemática ≥ 640  
  (equivalente a 80% da pontuação máxima de 800)
- Ordenação das escolas com melhor desempenho
- Visualização dos resultados em gráfico de barras horizontal

### 3️⃣ Cálculo da Pontuação Total do SAT
- Criação da variável `total_SAT`, somando:
  - average_math
  - average_reading
  - average_writing

### 4️⃣ Ranking das 10 Melhores Escolas
- Ordenação das escolas com maior pontuação total no SAT
- Visualização das 10 escolas com melhor desempenho geral

---

## 📈 Principais Insights
- Algumas escolas apresentam desempenho significativamente acima da média em matemática
- A pontuação total do SAT permite uma visão mais completa do desempenho geral das escolas
- O ranking facilita a identificação das escolas com melhores resultados acadêmicos

---

## 📂 Estrutura do Projeto
eda-schools-datacamp/
├── assets/
│   └── grafico_1.png
│   └── grafico_2_png
├── notebooks/
│   └── top_10_escolas_por_SAT
│   └── top_10_escolas_mat
├── data/
│   └── school_csv
└── README.md
