# Financial Statement Analysis

## 📌 Project Overview
The company is reviewing financial reports from September 2013 through the end of 2014 to assess the feasibility of meeting its 2015 targets, which project revenue of $39.58 million and a net profit of $16.65 million. This project analyzes whether these targets are achievable or not based on the company's historical financial data, it examines customer distribution, production cost and marketing cost to identify areas for optimization or evaluation in pursuit of the projected goals. The project aims to assist stakeholders in making data driven strategic decisions to maximize the company's potential.

## 🛠️ Tech Stack & Libraries
• Microsoft Excel
• Python -Pandas
• Google Colab
• Tableau

## 📈 Key Insight & Visualization

<img width="1347" height="706" alt="Sales   Revenue" src="https://github.com/user-attachments/assets/6473a349-04c9-4323-baa2-9a0a2cd189a0" />

- The number of products sold during the observation period exceeded 1 million units, generating total revenue of $135.2 million for the company. Meanwhile, the company’s total gross profit reached $37.8 million, with a net profit of $16.7 million.
- Monthly revenue report during the observation period fluctuated significantly, ranging from a high of over $13 million to a low of approximately $6 million.
- A revenue forecast for the upcoming year based on historical data and using an ARIMA model, model predicts that the company could generate over $100 million revenue in 2015, with an average monthly revenue of approximately $8 million.
- The ARIMA model (1,0,0) was selected based on the AIC, with MAPE 18.51% and RMSE 2,503,296.35. The model produced forecast point estimate and 95% prediction interval ranging from approximately $46.57 million to $154.16 million to illustrate forecast uncertainty.
- Consequently, the 2015 revenue target of $39.58 million appears relatively conservative compared to the company's historical performance that reached approximately $135 million, three times higher than the 2015 target, and this assessment is reinforced by the model's prediction of over $100 million revenue for 2015.
- In contrast, the 2015 net profit target of $16.65 million is quite challenging, based on company's historical data, net profit has hovered around 12% of total revenue. This implies that achieving the profit target would require revenue of approximately $133 million, whereas the predicted total revenue is around $100 million.
- Regarding revenue distribution by buyer segment, the government segment is dominant, its generating $56.9 million revenue. The revenue is higher than other segments, which generated only around $20 million each.
- Regarding revenue distribution by destination country, Mexico generated the least revenue only $22.9 million, whereas other destination countries exceeded $25 million. Although the revenue gap between Mexico and the other countries is not substantial, this point warrants consideration during the decision-making process.
- Finally, Amarilla and VTT emerged as the highest revenue products, with Amarilla generating $50 million and VTT generating $46.9 million

<img width="1340" height="698" alt="Cost   Product" src="https://github.com/user-attachments/assets/f672ec17-8648-436a-b084-64273b7616f9" />


- In terms of the percentage of total costs, production costs represent the largest expense, around 72% of total revenue generated.
- The product with the highest demand is Paseo, with over 300,000 units sold, far surpassing other products, no one of them reached the 200,000 units sold. Although Paseo has the highest demand, its revenue is significantly lower than several products, such as Amarilla and VTT.
- Although VTT is classified as a high revenue product, unlike Amarilla where production costs remain within a safe range, VTT’s production costs are extremely high, in fact they are the highest among all products, with total production costs reaching nearly 90% of revenue. In addition, Velo also incurs relatively high production costs, with a cost structure amounting to approximately 70% of total revenue, although this is not as high as VTT's, the magnitude of Velo's production costs warrants attention.
- Furthermore, although Amarilla generates the highest revenue, its gross profit margin remains well below than Carretera and Montana, Carretera’s gross profit margin exceeds 80%, while Montana’s is over 60%. However, in terms of gross profit, Amarilla is the product with the highest gross profit, reaching $18.9 million.
- Furthermore, regarding discount effectiveness, the difference between gross profit and total discount costs for the VTT product was only around 1 million dollars, that is the smallest compared to other products. Meanwhile, the gap between gross profit and total discount costs for Amarilla is the largest, reaching approximately $14 million.
- When examining sales volume by discount level, the "low discount" category achieved the highest sales, with over 230,000 units sold. This finding indicates that high sales volume does not necessarily require a high discount level, however the causal relationship between discount levels and sales volume warrants further investigation, taking into account factors such as product type, market segment, destination country, and price.
- Amarilla emerged as the product with the highest revenue and gross profit, with gross profit margin around 30%, while VTT was the product with the lowest gross profit margin only around 10%.

## 💡 Recommendations

- Achieving a revenue target of $39.58 million in 2015 is a realistic and relatively conservative goal, provided the company maintains its sales volume trends and avoids significant increases in production costs, this is supported by model projections indicating that the company could generate revenue 2,5 times higher than the target or approximately $100 million in 2015.
- Meanwhile, the net profit target $16.65 million for 2015 is quite challenging; achieving it requires the company to increase sales volume and cut costs including production and administrative expenses. Based on the ARIMA prediction model, the company would need to increase revenue by approximately 33% (or about $133 million) in 2015 to meet the target, or alternatively raise its net profit margin to 17% for the year.
- Regarding trend in sales volume, it is highly advisable to maintain a positive image and strong communication with the government segment, as it is the largest revenue contributor. However, there is a concentration risk with the government segment 42% of total revenue, therefore while this segment must be retained as a core revenue contributor, the company also needs to boost contributions from channel partners, small businesses, enterprises, and the mid-market to reduce reliance on a single customer segment.
- In addition, the situation in Mexico requires further analysis to determine whether low revenue stems from low demand, product mix, pricing, or customer segmentation factors before the company increases marketing investment in the region.
- Regarding the high demand for the Paseo product, it is recommended to slightly increase the selling price from $20 per unit to $25 per unit to boost revenue, based on the following simulation:

| Simulation | Price | Product Sold | Revenue |
| --- | --- | --- | --- |
| Current | $ 20 | 338.226 | $ 6,7 M |
| Decrease 10% | $ 25 | 304.404 | $ 7,6 M |
| Decrease 15% | $ 25 | 287.493 | $ 7,1 M |
| Decrease 20% | $ 25 | 270.581 | $ 6,7 M |

- Production costs for several products also need to be reduced, VTT warrants particular attention, as its production costs are exceptionally high reaching 90%, the highest among all products. This high-cost structure results in a very slim gross profit margin and makes the product highly vulnerable to increases in raw material prices. In addition to VTT, the production costs for Velo which around 70% also need to be lowered, although the absolute cost figure is lower than that of VTT, Velo’s gross profit margin is considered very small relative to the revenue it generates.
- In addition to reducing VTT production costs, the discount costs associated with the product must also be evaluated, these costs are relatively high compared to other products, yet they are not commensurate with the gross profit generated.
- Prioritize “low discount” as the primary discount option, as they have been proven to generate relatively high sales volumes, reserve other types of discounts for specific situations, tailoring them to consumer preferences, market segments, and country of origin.
- Furthermore, the company must sustain and boost the sales trend for Amarilla, as it generates the highest revenue and gross profit compared to other products. Sales trends for Carterra and Montana must also be improved, although they generate lower revenue and gross profit than other products, they boast the highest gross profit margins.
- Finally, the company also needs to reduce administrative, operational, and other expenses particularly production costs, which account for 72% of the total cost in order to maximize profits. Prioritize cost optimization for VTT and Velo, as their respective manufacturing costs stand at approximately 90% and 70%.
