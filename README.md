# InstaCart--Super-Market-Analysis
Data Science final project for Instacart dataset retrieved through Kaggle to perform Market Basket Analysis

**TO RUN THE CODE, DOWNLOAD THE PYTHON FILE AND USE PyScripter, PyDev, PyCharm, Google Colab or any other tools supported to open the .ipynb file**

## Abstract
Super Market Order Analysis is a modelling technique based upon the hypothesis that if you purchase a specific group of items, you are probably going to purchase another group of items. For example, if you are in an Irish pub and you buy a pint of beer and for some reason you decide not to buy a bar meal, you are more likely to buy chips simultaneously than someone who didn't buy a dip. In this analysis, a forecasting model is developed using machine learning algorithms to improve the accurate forecasts of product sales.

*The aim of this project is to predict the products the customer is most likely to buy in their next order based on the products which have been purchased previously.*

## Tools Utilized
These are the tools I have utilized for the following project:
* Jupyter Notebook
* Python

### Python Libraries 
* Keras
* NumPy
* Matplotlib
* Pandas
* Scikit-learn


## Dataset Information

**Data Set Name:** 'Instacart Market Basket Analysis'    [`link to Kaggle Dataset`](https://www.kaggle.com/c/instacart-market-basket-analysis/data) which contains information on anonymized grocery orders from more than 200,000 Instacart Users.

**Source:**  Instacart from Kaggle Competitions

#### File Descriptions 
* Aisles.csv - This dataset contains the listing of all the aisles present in the store.
* Department.csv - This dataset contains the listing of all the departments present in the store. (eg. Frozen foods, Bakery etc.)
* Order_Product_Prior.csv - It has details of all the previous customer orders.
* Order_Product_Train.csv - This dataset contains information about the products (product_id) that were ordered by the customers. It also contains information about the order (add_to_cart_order) which tells us the products that were put into the cart and the information if the product was re-ordered (1) or not (0)
* Orders.csv - It is the main table containing details about the customer orders and tells which record belongs to which table, train, prior or test.
* Products.csv - This dataset contains the listing of all the products with their product_id. It also contains the aisles and the departments that are included. 
