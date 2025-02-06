# PowerBi-dashboards
Dashboards that i did during PowerBi learning journey

# 1. Credit breton

I took on the role of a freelance consultant contacted by a new client, a historic network of banking agencies specializing in retail banking: Credit Breton. The employees of Credit Breton have observed that:
- the quality of mortgage loan applications varies across the network, and
- the decision-making process for approving or rejecting loans is excessively lengthy.

<b>French:</b>
Executant cet exercice, je me mets dans la peau d’un consultant freelance contacté par un nouveau client, un réseau d’agences bancaires historique, spécialisé en banque de détail : le Crédit Breton. Les collaborateurs du Crédit Breton constatent que la qualité des dossiers de prêts immobiliers accordés diverge au sein du réseau, et que les délais de prise de décision sur l’accord ou le rejet des prêts sont beaucoup trop longs.

### Summary of Crédit Breton Loan Process Issues

- **Problems Identified:**
  - Inconsistent quality of mortgage loan files.
  - Excessive decision-making delays on loan approvals.

- **User Stories Developed:**
  - Bank advisors need visibility on unprocessed loan requests and client details.
  - Agency directors require alerts on high-value transactions and historical data.
  - Central loan approval team seeks performance metrics and historical tracking.

- **Decision Criteria for Loans:**
  - Age plus loan duration over 82 years results in automatic rejection.
  - Irregular income leads to automatic rejection.
  - Detailed calculations needed for loan affordability assessments.

- **Functionalities:**
  - DAX
  - Power Query Editor
  - Role based for confidentiality
    
### Резюме проблем с ипотечными кредитами в Crédit Breton

- **Выявленные проблемы:**
  - Непостоянное качество ипотечных дел.
  - Долгие сроки принятия решений по кредитам.

- **Пользовательские истории:**
  - Консультанты хотят видеть незавершенные заявки и данные клиентов.
  - Директора агентств нуждаются в уведомлениях о крупных сделках и исторических данных.
  - Центральная команда по кредитам требует метрики производительности и отслеживание истории.

- **Критерии принятия решений:**
  - Возраст плюс срок кредита более 82 лет — автоматический отказ.
  - Нерегулярный доход — автоматический отказ.
  - Необходимы расчеты для оценки платежеспособности.
 
- **Функциональные возможности:**
  - DAX
  - Мощный редактор запросов
  - Конфиденциальность на основе ролей
 
## Example

1. Agency performance per city(France)
![image](https://github.com/user-attachments/assets/bc2700ca-1d58-48d8-8e1f-4dfdaf8c5de1)
2. Loan application per year and quartile
![image](https://github.com/user-attachments/assets/ec7691e5-7ee2-4881-94ff-0f5ba89b7292)
 
# 2. Financial Performance Analysis

**Dataset:** The multi-company financial datasets available on Kaggle. 

**Project Idea:**

- Utilize funnel charts for expense flow, combo charts for trends in revenue and profits, and waterfall charts for cumulative changes in financial metrics.
- Implement cards to highlight key metrics like total revenue and net income, supported by combo and funnel charts to analyze income sources.
- Use tables for detailed asset and liability reporting, and cards to summarize key balance sheet items such as total assets and liabilities.

**Key Business Questions to Explore**

- What are the trends in revenue, expenses, and profit over time?
- Which areas have the highest financial outflows, and how can they be optimized?
- What are the most critical components of the company’s balance sheet page?
- How do financial metrics compare across multiple companies or divisions?
