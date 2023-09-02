# **Customer Segmentation and Collaborative Filtering Project**
This project uses customer transaction data to perform customer segmentation and identify customer groups with similar purchase behaviors. Collaborative filtering techniques are then used to build recommendations models for each customer segment.

## **Project Overview**
The goal of this project is to gain insights into customer purchase behaviors and build personalized product recommendations for different types of customers.

The main steps are:

* Clean and preprocess the customer transaction data
* Identify features of customer segmentation model
* Cluster customers into distinct segments using algorithms like K-Means
* Analyze and label each customer segment based on purchase patterns
* For each segment, build a collaborative filtering model to recommend new products
* Evaluate model performance on test set and identify top recommendations

## **Data**
The dataset contains 70052 customer transactions from November 2018 — April 2019. Each transaction record includes:

* product_title
* product_type
* variant_title
* variant_sku
* variant_id
* customer_id
* order_id
* day
* net_quantity
* gross_sales
* discounts
* returns
* net_sales
* taxes
* total_sales
* returned_item_quantity
* ordered_item_quantity

## **Technologies**
The project utilizes Python with popular libraries like Pandas, NumPy, SciPy, Scikit-Learn.

Jupyter Notebooks are used for exploratory data analysis, model building and evaluation.

Use FastAPI as back-end service  and Streamilt library to build front-end.

This project can be deployed, and run by docker-compose.

## **Results**
The key results and findings are:

* 4 distinct customer segments were identified based on purchase behaviors

* Top highest score product recommendations are generated for new customers in each segment by using customer-based colabrative filtering technique.

## **Future Work**
Areas of potential improvement and expansion include:
* Build Back-end service with FastAPI
* Build Front-end service with Streamlit
* Build Dokcerfile and docker-compose file to run and deploy on AWS
* Incorporating additional customer profile data like demographics
* Testing deep learning models like Neural Collaborative Filtering
* Implementing a/b testing of recommendations
* Building an interactive dashboard to visualize insights