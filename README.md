# 🛒 Classificador de Sentimentos para E-commerce

Classificador que lê reviews de clientes em português e
avalia se a review é positiva, negativa ou neutra

# Sobre o Problema

Experiências ruins com produtos de e-commerce diminuem a confiança
nos serviços. Para entender melhor essa insatisfação, esse projeto
classifica automaticamente o sentimento de reviws escritas em texto

# Objetivo
Classificar automaticamente o sentimento de reviews de e-commerce em português.

## 📊 Dados
- **Fonte:** dataset de reviews da Olist (Brazilian E-Commerce)
- **Principais colunas:** `review_score` (nota de 1 a 5), `review_comment_title`,
  `review_comment_message`
- **Como as notas viram sentimento:**

| Nota | Sentimento |
|------|-----------|
| 1 e 2 | Negativo |
| 3 | Neutro |
| 4 e 5 | Positivo |


## 📁 Estrutura do projeto
    ├── notebooks/
    │   ├── 01_eda.ipynb
        ├── 02_modelo_baseline.ipynb
        └── 03_avaliacao.ipynb
    │   
    ├── data/documents/     
    ├── requirements.txt
    └── README.md

## ▶️ Como rodar
1. Clone o repositório:
   git clone https://github.com/rpf991/Ecommerce_Classificador_Sentimentos.git
2. Instale as dependências:
   pip install -r requirements.txt
3. Baixe o dataset e coloque em `data/documents/`
4. Abra os notebooks em `notebooks/` com Jupyter ou VS Code


## 🛠️ Tecnologias
Python, pandas, numpy, matplotlib, seaborn
