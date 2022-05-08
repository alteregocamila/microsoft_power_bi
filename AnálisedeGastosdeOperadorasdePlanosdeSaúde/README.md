# Case Análise de Gastos de Operadoras de Planos de Saúde

Case of the Data Science Academy's [Microsoft Power BI Para Data Science](https://www.datascienceacademy.com.br/course/microsoft-power-bi-para-data-science).

## Análise de Gastos de Operadoras de Planos de Saúde

![Imagem Análise de Gastos de Operadoras de Planos de Saúde](./AnálisedeGastosdeOperadorasdePlanosdeSaúde.PNG 'Análise de Gastos de Operadoras de Planos de Saúde')

The directors of a health plan operator that serves in four regions of Brazil have noticed that health insurance expenses have increased considerably and need to monitor the evolution of expenses.

Directors need answers to the following questions:

1. What is the operator's total expense?
2. What is the average age of the operator's users?
3. What is the average spending by region?
4. Which age group has the highest expenditure on health insurance by region?
5. Does increasing age influence BMI?
6. Who spends more, men or women?
7. If the user is a woman, is the BMI above or below average?
8. If you are a man, over 50 years old and from the Southeast region, is your expenditure higher or lower than the average expenditure in the region?

However, the received data contains "problems", errors that must be solved before building the dashboard.

Among the problems identified in the dataset are:

-The header was on duplicate lines.
Solution: One of the lines was removed.

-It is not possible with the data to determine whether the column "criança" informs that the user is a child or not. However, the fact that the lowest age in the dataset is 18 indicates that there are no children among the users.

-There were blank cells in the columns: sex, smoker and region
Solution: these cells were hidden in the dataset.
