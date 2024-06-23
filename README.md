# Projeto de Previsão de Crédito

Este projeto utiliza um conjunto de dados financeiros para prever a pontuação de crédito de clientes. O notebook principal contém análises exploratórias, limpeza de dados, e modelos de machine learning para previsão de crédito.

## Conteúdo do Repositório

- `main_notebook.ipynb`: Notebook com a análise completa.
- `train.csv`: Conjunto de dados utilizado para treinamento dos modelos.

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
9. **Conclusões**

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
