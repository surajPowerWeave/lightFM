# lightFM
Here, We will see all activities deals in lightFM model training and using 

lightFM_CF-CopyGit:
In this file, you will see how to save and load  model. Here, model is pure collaborative filter 

The idea is that though we deal with users as point of contact but we need to avoid redundancy of product recommendations to multiple users of same company. Here, company is the actual customer in Bussiness to Bussiness e-commerce.
So, We are predicting 50 products at users level and 200 products at Company level. using function named 'recommendation_dataframe'.
And then by using function named 'user_products_filtering', select common 20 products from users and his company recommended products. If common set of products is less than 20 then add rest of the products of users bucket.
