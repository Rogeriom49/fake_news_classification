# 📢 Fake News Classifier

## 📌 Descrição
Este projeto tem como objetivo desenvolver um modelo de Machine Learning para classificação de fake news. A solução utiliza técnicas de Processamento de Linguagem Natural (NLP) e aprendizado de máquina para identificar se uma notícia é verdadeira ou falsa.

## 📂 Estrutura do Projeto
```
├── datasets                                               # Conjunto de dados utilizado no projeto
├── fakenews_classification.ipynb                          # Código-fonte do projeto
├── best_model_count_vectorizer_logistic_regression.pkl    # Melhor modelo BoW
├── best_model_tfidf_decision_tree.pkl                     # Melhor modelo TF-IDF
├── README.md                                              # Documentação do projeto
```

## 🛠️ Tecnologias Utilizadas
- Python 3.x
- Pandas e NumPy para manipulação de dados
- Seaborn e Matplotlib para visualização de dados
- Scikit-learn para modelagem e avaliação
- NLTK para Processamento de Linguagem Natural

## 🚀 Como Executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/Rogeriom49/fake_news_classification.git
   cd fake-news-classifier
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute o treinamento do modelo:
   ```bash
   python src/train.py
   ```
4. Faça previsões com um novo texto:
   ```bash
   python src/predict.py "Seu texto aqui"
   ```

## 📈 Métricas de Avaliação
O modelo será avaliado utilizando:
- Acurácia
- Precisão, Recall e F1-Score

## 📌 Melhorias Futuras
- Melhorar o pré-processamento dos textos
- Implementação de um modelo utilizando Deep Learning
- Criar uma API para disponibilizar previsões

