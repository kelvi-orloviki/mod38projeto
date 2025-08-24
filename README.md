# Projeto - Credit Scoring para Cartão de Crédito
[streamlit-app_pycaret-2025-08-24-19-08-01.webm](https://github.com/user-attachments/assets/50beba56-b11c-41e1-8321-76dadf5e7266)

Este projeto tem como objetivo desenvolver um modelo de credit scoring para avaliação de risco na concessão de cartões de crédito. Utilizamos a biblioteca PyCaret para automatizar o processo de machine learning, empregando o algoritmo LightGBM para gerar um pipeline eficiente.

# Fluxo de Trabalho
Carregamento dos dados: O pipeline recebe um arquivo de dados no formato .ftr contendo as informações dos clientes.
Processamento e Previsão: O modelo realiza as previsões de risco de crédito.
Geração de Resultados: Após o processamento, um arquivo Excel é gerado com duas colunas adicionais:
prediction_label: Previsão binária (0 para baixo risco, 1 para alto risco).
prediction_score: Probabilidade associada à previsão, expressando a confiança da previsão.

# Conteúdo
Mod38Projeto.ipynb: Notebook com o código principal e explicações do processo de construção do modelo.
app_pycaret.py: Este arquivo contém o código para criar o aplicativo Streamlit com o deploy do projeto.
model_final.pkl: Pipeline do modelo LightGBM treinado gerado pelo Pycaret.
model_regressao_logistica.pkl: Pipeline do modelo de regressão logística treinado gerado pela biblioteca Joblib.
sklearn.pipeline.pkl: Pipeline do modelo de regressão logística treinado gerado pela biblioteca Pickle.
logs.log: Arquivo de log com registros das etapas de execução do pipeline.
Projeto04_streamlit.mov.webm.webm: Este vídeo apresenta o deploy criado com o aplicativo Streamlit.
