# Learning what factors lead sales(Item_Outlet_Sales)
Athor: Nanping Li

# Business Problem:
What facotors affect item sales?

# Data:
First I see pairplot chart all numeric factors have no obvious linear effect with sales(Item_Outlet_Sales)
So Decesion tree have better performance in this project.

# Results:
A unit increase on the Item_MRP is associated with a increase with a increase of 800 Item_Outlet_Sales.
Other numeric value have little or negtive effect with 800 Item_Outlet_Sales.

The most outstanding valuable Catgorical factor is Item_Type which includes 16 types of foods. 
In pie chart we can see fruit vegetables and snack foods take up great distribution. Other type foods have 
its own distribution percentage. 
[item_sales.pdf](https://github.com/pingli10/project-1-final-/files/9222557/item_sales.pdf)










# Model:
My final model is decesion tree.
We can split node on Item_Type to see specific value in different food types

#Recommendations:
According to the Item_Type and sales(Item_Outlet_Sales), factory pay more attention on fruit,vegetables and snack foods
than other type foods or factory can bind other food with snack or fruit, for example if you buy bread will get vegetable or snack promotion.


