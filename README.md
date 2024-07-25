# Projeto de Previsão de Crédito

Este projeto utiliza um conjunto de dados financeiros para prever a pontuação de crédito de clientes. O código principal contém análises exploratórias, limpeza de dados, e modelos de aprendizado de máquina para previsão de crédito.

## Conteúdo do Repositório

- `main_notebook.ipynb`: Notebook com a análise completa (Código principal).
- `train.csv`: Conjunto de dados utilizado para treinamento dos modelos.
- `requirements.txt`: Arquivo de dependências.
- `Raphael Benedeti-Final.pdf`: Arquivo PDF do Trabalho de Conclusão de Curso

## Estrutura do Notebook

1. **Importação das Bibliotecas**
2. **Carregamento dos Dados**
3. **Análise Exploratória de Dados (EDA)**
4. **Limpeza de Dados**
5. **Feature Engineering**
6. **Divisão dos Dados**
7. **Treinamento de Modelos**
    - Regressão Logística
    - Árvore de Decisão
    - Floresta Aleatória
    - K-Nearest Neighbors
    - Support Vector Machine
8. **Avaliação dos Modelos**

## Conjunto de Dados

O conjunto de dados `train.csv` contém as seguintes colunas:

- `ID`: Identificador único do cliente.
- `Customer_ID`: Identificador único do cliente.
- `Month`: Mês da transação.
- `Name`: Nome do cliente.
- `Age`: Idade do cliente.
- `SSN`: Número do Seguro Social.
- `Occupation`: Ocupação do cliente.
- `Annual_Income`: Renda anual do cliente.
- `Monthly_Inhand_Salary`: Salário mensal do cliente.
- `Num_Bank_Accounts`: Número de contas bancárias.
- `Num_Credit_Card`: Número de cartões de crédito.
- `Interest_Rate`: Taxa de juros.
- `Num_of_Loan`: Número de empréstimos.
- `Type_of_Loan`: Tipo de empréstimo.
- `Delay_from_due_date`: Atraso em dias para o pagamento.
- `Num_of_Delayed_Payment`: Número de pagamentos atrasados.
- `Changed_Credit_Limit`: Limite de crédito alterado.
- `Num_Credit_Inquiries`: Número de consultas de crédito.
- `Credit_Mix`: Mix de crédito.
- `Outstanding_Debt`: Dívida pendente.
- `Credit_Utilization_Ratio`: Taxa de utilização de crédito.
- `Credit_History_Age`: Idade do histórico de crédito.
- `Payment_of_Min_Amount`: Pagamento do valor mínimo.
- `Total_EMI_per_month`: Total de EMI por mês.
- `Amount_invested_monthly`: Quantidade investida mensalmente.
- `Payment_Behaviour`: Comportamento de pagamento.
- `Monthly_Balance`: Saldo mensal.
- `Credit_Score`: Pontuação de crédito.

## Requirements

Este projeto utiliza as seguintes dependências, especificadas no arquivo `requirements.txt`:

- `pandas==2.2.2`
- `numpy==1.26.4`
- `seaborn==0.13.2`
- `matplotlib==3.9.0`
- `plotly==5.22.0`
- `scikit-learn==1.5.0`
- `yellowbrick==1.5`
- `notebook==7.2.1`
- `jupyterlab==4.2.2`

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/raphaelbenedeti/credit-score-prediction.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd credit-score-prediction
   ```
3. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt
   ```
3. Abra o notebook:
   ```bash
   jupyter notebook main_notebook.ipynb
   ```
