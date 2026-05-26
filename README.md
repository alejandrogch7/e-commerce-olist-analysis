# E-Commerce Sales & Customer Experience Dashboard

This project analyzes real-world e-commerce data to uncover business insights related to sales performance, customer satisfaction, payment behavior, delivery performance, and regional revenue distribution.

The analysis was performed using Python, Pandas, and SQL querying techniques, while the interactive dashboard was built in Data Studio.

## Business Questions Explored

- Which product categories generate the highest revenue?
  
| Product Category | Revenue in Brazilian Real |
| --- | --- |
| beleza_saude | R$1.461.349,75 |
|relogios_presentes | R$1.316.696,84 |
|cama_mesa_banho | R$1.309.729,85 |
|esporte_lazer | R$1.166.307,34 |
|informatica_acessorios | R$1.077.483,63 |
|moveis_decoracao | R$931.754,14 |
|utilidades_domesticas | R$801.521,45 |
|cool_stuff | R$722.033,51 |
|automotivo | R$698.077,73 |
|ferramentas_jardim | R$595.367,38 |

- Which states drive the largest share of sales?

| State | Sales in Brazilian Real |
| --- | --- |
| SP | R$6.076.438,89 |
| RJ | R$2.167.521,77 |
| MG | R$1.890.600,24 |
| RS | R$908.920,14 |
| PR | R$812.671,95 |
| BA | R$627.081,41 |
| SC | R$616.385,81 |
| DF | R$360.530,87 |
| GO | R$355.374,39 |
| ES | R$328.955,10 |

- How do delivery delays affect customer satisfaction?

| Order Status | Score Review |
| --- | --- |
| No delay | 4.2 |
| Delay | 2.3 |

- What payment methods do customers prefer?

| Payment Method | Orders |
| --- | --- |
| credit card | 85372 |
| boleto | 22505 |
| voucher | 6181 |
| debit card | 1662 |

- Are customer review scores consistent across product categories?

| product_category_name | review_count | average_review |		
| --- | --- | --- |
| livros_interesse_geral |	549 |	4.506375 |
| construcao_ferramentas_ferramentas | 105 | 4.438095 |
| livros_tecnicos |	268 |	4.402985 |
| alimentos_bebidas |	281 |	4.387900 |
| malas_acessorios | 1148 |	4.332753 |
| alimentos |	515 |	4.289320 |
| fashion_calcados | 273 | 4.285714 |
| papelaria |	2572 | 4.240280 |
| pcs |	216 |	4.236111 |
| eletroportateis |	684 |	4.235380 |

- How is revenue evolving over time?

| purchase_year | purchase_month | Revenue in Brazilian Real |
| --- | --- | --- |
| 2016 | 9 | R$143,46 |
| 2016 | 10 | R$48.314,12 |
| 2016 | 12 | R$19,62 |
| 2017 | 1 | R$138.323,99 |
| 2017 | 2 | R$286.678,44 |
| 2017 | 3 | R$442.061,00 |
| 2017 | 4 | R$414.527,46 |
| 2017 | 5 | R$614.885,90 |
| 2017 | 6 | R$518.076,28 |
| 2017 | 7 | R$610.664,84 |
| 2017 | 8 | R$680.858,92 |
| 2017 | 9 | R$746.898,44 |
| 2017 | 10 | R$789.406,96 |
| 2017 | 11 | R$1.205.033,35 |
| 2017 | 12 | R$877.503,67 |
| 2018 | 1 | R$1.128.224,39 |
| 2018 | 2 | R$1.016.511,44 |
| 2018 | 3 | R$1.172.957,65 |
| 2018 | 4 | R$1.174.143,49 |
| 2018 | 5 | R$1.171.614,43 |
| 2018 | 6 | R$1.064.996,68 |
| 2018 | 7 | R$1.066.593,79 |
| 2018 | 8 | R$1.020.340,91 |


## Key Insights

- Revenue is heavily concentrated in São Paulo, generating nearly three times more revenue than the second highest-performing state.

- Product revenue is relatively diversified across multiple categories, suggesting a balanced marketplace rather than dependency on a single segment.

- Everyday-use categories such as health, home, sports, and household products consistently rank among the strongest revenue drivers.

- Customers overwhelmingly prefer credit card payments, indicating strong adoption of digital payment methods.

- Delivery delays have a significant impact on customer satisfaction. Orders delivered on time maintain review scores above 4/5 on average, while delayed deliveries reduce customer satisfaction close to 2/5.

- Customer reviews remain generally positive across most product categories, suggesting a stable overall shopping experience.


## Business Recommendations

- Improve logistics performance to reduce delayed deliveries and protect customer satisfaction.

- Increase marketing investment in top-performing states while exploring expansion opportunities in lower-performing regions.

- Strengthen inventory and promotional strategies around consistently high-performing everyday-use categories.

- Investigate operational or product-quality issues within lower-rated product categories.

- Continue optimizing digital payment experiences due to strong customer preference for credit card transactions.


## Dashboard Preview
<img width="1377" height="778" alt="image" src="https://github.com/user-attachments/assets/1f4b5f00-3728-45c7-9c36-6e67d805fbda" />
<img width="1375" height="776" alt="image" src="https://github.com/user-attachments/assets/e06112bc-2772-4903-a788-3825d9c5a73c" />


