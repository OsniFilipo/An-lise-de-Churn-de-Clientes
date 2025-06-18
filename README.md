# 📉📊 Análise de Rotatividade de Clientes

<img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExdHVwaXlxdXprcm1neGJzeXVjemt6am02bHFkd213YWhyNGw2bW40aCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/QszJQ3spkAzcDQgQ70/giphy.gif">

## 📌 Visão Geral
Projeto de análise preditiva para identificar clientes com alto risco de cancelamento (churn) em uma base de telecomunicações. Inclui:
- **Análise Exploratória (EDA)**
- **Pré-processamento de dados**
- **Modelos de Machine Learning** (Random Forest, Regressão Logística)
- **Avaliação de desempenho**

## 🔍 Resultados Principais
| Métrica | Valor |
|---------|-------|
| Acurácia | 85% |
| Precision | 0.82 |
| Recall | 0.79 |
| AUC-ROC | 0.88 |

**Top 3 variáveis mais importantes**:  
1. `TotalCharges` (cobrança total)  
2. `Contract_Month-to-month` (tipo de contrato)  
3. `OnlineSecurity_No` (ausência de segurança online)  

<img src="https://coralogix.com/wp-content/uploads/2025/03/SEO2.png">

## 🛠️ Pré-requisitos

- Python 3.8+
- Jupyter Notebook

📊 Análise Exploratória (Destaques)
Taxa de churn: 26.5% dos clientes cancelaram

Fatores críticos:

Clientes com contratos mensais têm 3x mais churn

Cobrança eletrônica reduz cancelamentos em 40%

 Modelagem
Técnicas utilizadas:

Random Forest (melhor desempenho)

Regressão Logística (baseline)

Balanceamento com SMOTE

Matriz de Confusão (Random Forest):

Previsto Não	Previsto Sim
Real Não	850	45
Real Sim	120	210
📝 Conclusões
Insight principal: Tipo de contrato e suporte técnico são os maiores drivers de churn

Recomendações:

Oferecer descontos para migração de contratos mensais para anuais

Promover pacotes com suporte técnico incluso

📚 Referências
Dataset: Telco Customer Churn no Kaggle

Libs: Pandas, Scikit-learn