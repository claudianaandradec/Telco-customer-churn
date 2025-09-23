# Telco Customer Churn Dataset

## 📊 Descrição
Dataset contendo informações de clientes de uma empresa de telecomunicações para prever churn (cancelamento).

*Fonte Original*: [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## 📁 Estrutura dos Dados
- *Arquivo principal*: WA_Fn-UseC_-Telco-Customer-Churn.csv
- *Registros*: 7.043 clientes
- *Variáveis*: 21 colunas

### Principais Variáveis
- customerID: Identificador único
- Churn: Indicador de cancelamento (Yes/No)
- tenure: Tempo de permanência (meses)
- MonthlyCharges: Cobrança mensal
- TotalCharges: Cobrança total

## 🚀 Como Usar

### Python
```python
import pandas as pd

# Carregar dados
df = pd.read_csv('data/WA_Fn-UseC_-Telco-Customer-Churn.csv')
print(df.shape)
print(df.columns)
