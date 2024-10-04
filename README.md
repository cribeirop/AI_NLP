# Classificação de Status de Saúde Mental a Partir da Análise de Comentários

Este projeto visa analisar um conjunto de dados visando classificá-lo usando técnicas e modelos de predição, e discutir acerca do desempenho e métricas obtidas, assim como os próximos passos para sua aprimoração.

O conjunto de dados utilizado é chamado de [Sentiment Analysis for Mental Health](https://www.kaggle.com/datasets/suchintikasarkar/sentiment-analysis-for-mental-health)

## Instruções

Para rodar este projeto, siga os seguintes passos:

1. Clone este repositório:
    ```bash
    https://github.com/cribeirop/Exame_Intermediario_NLP
    ```
2. Crie um ambiente virtual e o ative:
    - Criando `venv`:
    ```bash
    python3 -m venv venv
    ```
    - Activando:
    ```bash 
    source venv/bin/activate
    ``` 
    or
    ```bash
    .\venv\bin\Activate.ps1
    ``` 
    or 
    ```bash
    .\env\Scripts\activate
    ```
3. Instalar bibliotecas:
    ```bash
    pip install -r requirements.txt
    ```

## Execução

1. Certifique-se que o dataset esteja com o nome correto (mental_health_analysis.csv), e na pasta raiz.

2. Abra o arquivo ipynb no Jupyter Notebook ou mesmo VS Code para rodá-lo.

## Tópicos abordados

- Pré-processamento dos Dados
- Uso de Bag-of-Words
- Execução do Classificador e Diferentes Tipos de Modelos
- Avaliação das Palavras Mais Importantes Para a Classificação
- Tamanho do Dataset e _Downsampling_
- Usando Modelos de Tópicos
- Classificador de Duas Camadas