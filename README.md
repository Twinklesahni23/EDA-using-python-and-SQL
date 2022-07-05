# EDA-using-Python-and-SQL
This repository contains the explanatory data analysis summer sale of clothes of Ecommerce website 'Wish' which is done using python numpy, pandas, matplotlib, seaborn and pandasql.

![Wish com-logo-1024x538](https://user-images.githubusercontent.com/99166745/177133908-77bc0e86-1aca-4161-a93d-7eeb2a70b3d6.jpeg)

The indepth analysis has been done on a dataset collected from kaggle. The data contains a lot of useful features that one can dig into to generate the important insights for both, firm as well as the customers buying from Wish. The data contains the features like 
- Price
- User Ratings
- Merchant Ratings
- Shipping Costs
- Product Sizes
- Product Colors

The insights from the analysis are as follow:
- **Discount:** *Higher the discount, higher is the number of clothes sold during the sale. For the number of products sold over 100k, the discount is of nearly 65% while number of products selling between 1k-50k have a discount range of 20%-30%. This notion confirms the price sensitive behaviour of buyers.*
![image](https://user-images.githubusercontent.com/99166745/177139193-c11a92b8-85a8-4142-a0e5-32ed9922d32a.png)

- **User Ratings:** *The frequency of user ratings is strongly correlated with number of items sold. This means that products with higher number of reviews seems to be looked upon by the customers. Hence, the comapny should put emphasis on receing the feedback in the form of ratings/reviews from a customer after making a purchase.*
![image](https://user-images.githubusercontent.com/99166745/177139279-15ded648-fc16-4b65-98d4-922c050d7f65.png)

- **This is a result of SQL query for *Top 5 sold products* during Wish summer sale**
![Screenshot (15)](https://user-images.githubusercontent.com/99166745/177259011-0a5f1833-c552-4f6f-a1cf-cc054d7cc004.png)

- **Ad Boosts:** *Ad boost has no significant impact on the sale of the products. This means that items that seller has put into advertisement expense onto does not really influence the buying patterns of customers. This is a signal for the marketing team to work on better and compelling campaigns.*
![image](https://user-images.githubusercontent.com/99166745/177259173-d11b4b41-84d6-4e45-99cc-d7b8b18cac83.png)

- **Gender:** *Roughly 94% of all the products constitute clothes in Women Category.*

- **Size:** *During the summer sale of clothes, S is the most sold size followed by XS and M. This can help in maintaining the buffer inventory for certain sizes to increase the revenue in upcoming sales.*
![image](https://user-images.githubusercontent.com/99166745/177259214-f563897e-de37-420d-88de-9e1bc48983b5.png)

- **Color:** *From the sorted data, Black is the most demanded color (19.7%) followed by White (16.4%). The category of 'Other' colors include colors like Pink, Maroon, Gold, Brown etc.*
![Screenshot (17)](https://user-images.githubusercontent.com/99166745/177259548-1fd6e077-b683-442d-b73e-98f4427da033.png)

- **Merchant Rating:** *Higher the number of Ratings of a Merchant, higher is the units sold for that merchant. Merchant 'simplevalueltd' is the highest rated merchant with a rating of 4.35 and more than 2 million rating counts. Their top selling product is a Cat imprint shirt for women. Also, it is equally important of Merchants to seek the feebacks for their services as products sold are the ones with merchant rating of 4 or more. This is a indication of buyer awareness implying that customers tend to buy products from higher rated merchants only.*
![image](https://user-images.githubusercontent.com/99166745/177259583-1051fccd-1fd6-4aba-998a-b32a7ca99573.png)
