# Personal Loan Purchasing Prediction
The goals of this project are to predict whether the customer will purchase a loan or not using logistic regression and we implemented our model to do business simulation

## Evaluation Metric:
We used precision to evaluate our model, To make marketing budget effective and efficiency, we want to give special promotions to people who are predicted purchase loans to actually buy and give special treatment to people who are predicted not purchase the loans in order to only slightly increase the probability of buying loans. The result :

![Screen Shot 2022-08-23 at 01 44 29](https://user-images.githubusercontent.com/106853320/185995703-c7e43427-23bc-402c-8f50-14dec5f2d38b.png)

## Feature Importance:
After training the model, we extract coefficient and odds ratio to find feature importance. 

![Screen Shot 2022-08-23 at 01 45 25](https://user-images.githubusercontent.com/106853320/185996239-b45d706c-5e90-45ae-bac7-860d26831eab.png)

![Screen Shot 2022-08-23 at 01 48 24](https://user-images.githubusercontent.com/106853320/185996366-48e16af5-19d2-4dea-ad82-baa126b836fc.png)

## Insights
1. If the customers have certifcate of deposite (CD Account), their odds of accepting personal loan will increase by 21.32 times
2. If the customer have higher education level (Education), their odds of accepting personal loan will increase by 4.71 times
3. If the customer have bigger size family member (Family), their odds of accepting personal loan will increase 2.07 times
4. If the customer use Securities Account, their odds of accepting personal loan will decrease by 0.57 times
5. If the customer use Onlineinternet banking, their odds of accepting personal loan will decrese by 0.56 times
6. If the customers use CreditCard isssued by the bank, their odds of accepting personal loan will decrease by 0.44 times

## Business Simulation:
One of our simulation is trying to target customers who have Certificate of Deposite and the result is:
- Current Conversion Rate = 9.60%
- Simulation Conversion Rate After Recommendation = 24.84%
- Customer Conversion Rate Increment =  15.24
