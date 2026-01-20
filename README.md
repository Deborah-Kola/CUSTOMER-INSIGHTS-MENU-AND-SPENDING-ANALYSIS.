# CUSTOMER-INSIGHTS-MENU-AND-SPENDING-ANALYSIS.
![image alt](https://github.com/Deborah-Kola/CUSTOMER-INSIGHTS-MENU-AND-SPENDING-ANALYSIS./blob/main/danny's%20Diner%20github/dany_diner_github.jpg?raw=true)

SQL case study analyzing customer visiting patterns, spending, and menu preferences to support a loyalty program.
___
## BY DEBORAH KOLA, TEMITOPE.
___
## INTRODUCTION.

This repository contains a SQL case study focused on analyzing customer behavior for a restaurant.
The goal of this analysis is to uncover insights into customer visiting patterns, spending habits, and menu preferences to support decisions around expanding and improving the loyalty program.
i demonstrated how SQL can transform raw data into actionable business insights that help the restaurant create a more personalized and engaging experience for its customers.
___

## PROBLEM STATEMENT.
Danny, the restaurant owner, wants to better understand his customers to improve the loyalty program.
He is particularly interested in analyzing how often customers visit, how much they spend, and which menu items are most popular.
Due to privacy concerns, only a sample of the overall customer data was provided. I will be using the provided data to write fully functioning SQL queries and generate datasets that can be easily inspected without needing to run SQL.
___

## BUSINESS QUESTIONS.
I answered the following questions provided by the restaurant owner:

- Points Calculation: If each $1 spent equates to 10 points and sushi has a 2× points multiplier, how many points would each customer have? 
- **Visit Frequency:** How many days has each customer visited the restaurant?  
- **First Purchased Item:** What was the first item from the menu purchased by each customer?  
- **Most Purchased Item Overall:** Which item was purchased the most by all customers, and how many times?  
- **Customer-Specific Favorite:** Which item was the most popular for each customer?  
- **First Purchase After Membership:** Which item was purchased first by the customer after they became a member?  
- **Purchase Before Membership:** Which item was purchased just before the customer became a member?  
- **Total Items & Spending Before Membership:** What is the total number of items and total amount spent for each customer before they became a member?  
- Customer Spending:What is the total amount each customer spent at the restaurant? 
- **Points in First Week of Membership:** In the first week after joining (including the join date), customers earn 2× points on all items (not just sushi). How many points do Customer A and Customer B have at the end of January?  

Each question is answered using SQL queries, and the results are documented in this repository to provide actionable insights for the restaurant owner.
___
## RESULTS, INSIGHT AND RECOMMENDATION.
- Points Calculation: If each $1 spent equates to 10 points and sushi has a 2× points multiplier, how many points would each customer have?

![image alt](https://github.com/Deborah-Kola/CUSTOMER-INSIGHTS-MENU-AND-SPENDING-ANALYSIS./blob/main/danny's%20Diner%20github/carbon%20(12).png?raw=true)
![image alt](https://github.com/Deborah-Kola/CUSTOMER-INSIGHTS-MENU-AND-SPENDING-ANALYSIS./blob/main/danny's%20Diner%20github/If%20each%20$1%20spent%20equates%20to%2010%20points%20and%20sushi%20has%20a%202x%20points%20multiplier%20-%20how%20many%20points%20would%20each%20customer%20have.png?raw=true)

### INSIGHTS
- Customer B is the top spender: With 940 points, Customer B has the highest total, indicating either frequent purchases or a preference for high-value items like sushi.
- Sushi drives point accumulation: The 2x multiplier for sushi significantly boosts point totals. Customers who favor sushi earn more rewards.
- Customer C lags behind: With only 360 points, Customer C is far behind A and B, suggesting lower engagement or less interest in premium items.

### RECOMMENDATIONS
- Target high-value customers with exclusive offers:
  - Create a VIP loyalty tier for customers like B who consistently spend more.
  - Offer early access to new menu items or personalized discounts.
- Promote sushi to boost engagement:
  - Highlight the 2x points multiplier in marketing campaigns.
  - Bundle sushi with other items to encourage trial and increase average spend.
- Re-engage low-point customers:
  - Send personalized emails to Customer C with incentives like “Double Points Week” or “Try Sushi for Bonus Rewards.”
  - Offer a welcome-back discount or free item after a period of inactivity.
- Refine the loyalty program:
  - Consider adding more product-specific multipliers to influence purchasing behavior.
  - Track redemption rates and adjust point thresholds to maintain profitability.
___

- **Visit Frequency:** How many days has each customer visited the restaurant?
![image alt](https://github.com/Deborah-Kola/CUSTOMER-INSIGHTS-MENU-AND-SPENDING-ANALYSIS./blob/main/danny's%20Diner%20github/carbon%20(3).png?raw=true)
![image alt](https://github.com/Deborah-Kola/CUSTOMER-INSIGHTS-MENU-AND-SPENDING-ANALYSIS./blob/main/danny's%20Diner%20github/HOWMANYDAYSHASEACHCUSTOMERVISITEDTHERESTAURANT.png?raw=true)
___

- **First Purchased Item:** What was the first item from the menu purchased by each customer?
![image alt](https://github.com/Deborah-Kola/CUSTOMER-INSIGHTS-MENU-AND-SPENDING-ANALYSIS./blob/main/danny's%20Diner%20github/carbon%20(4).png?raw=true)
![image alt](https://github.com/Deborah-Kola/CUSTOMER-INSIGHTS-MENU-AND-SPENDING-ANALYSIS./blob/main/danny's%20Diner%20github/WHAT%20WAS%20THE%20FIRST%20ITEM%20FROM%20THE%20MENU%20PURCHASED%20BY%20EACH%20CUSTOMER.png?raw=true)
___


- **Most Purchased Item Overall:** Which item was purchased the most by all customers, and how many times?
![image alt](




