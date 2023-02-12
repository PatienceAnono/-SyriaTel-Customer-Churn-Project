# -SyriaTel-Customer-Churn-Project

![image](https://user-images.githubusercontent.com/116062465/218259787-663028fe-fecb-4461-a472-08971c85394f.png)
)


## 1. INTRODUCTION
Build a classifier to predict whether a customer will ("soon") stop doing business with SyriaTel, a telecommunications company

## 2. BUSINESS PROBLEM
### The Problem statement
Customer churn is one of the most important metrics for a growing business to evaluate as it is much less expensive to retain existing customers than it is to acquire new customers. Customers in the telecom industry can choose from a variety of service providers and actively switch from one to the next.The technical progress and the increasing number of operators has raised the level of competition. Companies are working hard to survive in this competitive market depending on multiple strategies. This becomes a problem, as Telecom companies usually incur huge costs to attract subscribers.Since it is costly to lose customers, the goal is to use this data to build a classifier that can predict which customers will stop dealing with them for another provider, and identify how the company can avoid the loss of those customers.


### Main Objective
Due to the direct effect on the revenues of the companies, especially in the telecom field, SyriaTel is seeking to develop means to predict potential customers to churn using Machine learning Techniques

## 3. NOTEBOOK STRUCTURE
The notebook is [here](http://localhost:8888/notebooks/SyriaTel%20Customer%20Churn.ipynb#3.5.2.-Decision-Tree-Classifier)
The python notebook is structured as follows:
1. Data cleaning
2. Exploratory Data Analysis
3. Feature selection 
4. Data Modelling and evaluation

## 4. DATA UNDERSTANDING
### The Data
The data used in this project was downloaded from [Kaggle ](https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset) 
and these are the features.
- state                    
- account length           
- area code                 
- phone number            
- international plan       
- voice mail plan          
- number vmail messages    
- total day minutes       
- total day calls          
- total day charge        
- total eve minutes       
- total eve calls           
- total eve charge        
- total night minutes     
- total night calls        
- total night charge      
- total intl minutes      
- total intl calls         
- total intl charge       
- customer service calls   
- churn                     
- Lastly, to validate this data reference was made to an article by [Database Marketing Institute](http://www.dbmarketing.com/telecom/churnreduction.html#:~:text=Annual%20churn%20rates%20for%20telecommunications,the%20way%20they%20are%20treated.)

### Data Preparation
The data was read and then checked for anomalies, outliers, missing values and duplicates. This was to determine the next course of action that would ensure the data would be set for use. During this process, it was established that our dataset did not have duplicates nor missing values.However it had outliers.The outliers were kept because they were essential for training the model.


### Exploratory Data Analysis
By carrying out EDA on the cleaned data as seen in this notebook, various patterns were discovered.
These are some of the questions that were answered:
1.What is the total percentage of churn?  
2..How much a client is charged for all phone call categories (international, evening, night, and day)?  
3.What are the charges for day calls?  
4.What is the relationship between customer service calls and customer churn?  
5..Find out what attributes have the highest correlation with churn  
6.Which customers are likely to churn


![image](https://user-images.githubusercontent.com/116062465/218260430-b70bfe79-f299-412a-83bd-74c4538bc7d7.png)
)
![image](https://user-images.githubusercontent.com/116062465/218260606-e3b5427c-ac30-4744-8231-edb03d907402.png)

### Modeling
test accuracy results before hyperparameter tuning
![image](https://user-images.githubusercontent.com/116062465/218260778-9070c833-5924-4bd9-82d9-778446018927.png)


## 5.CONCLUSIONS 
-Customers who called customer service more than 3 times tend to leave.  
-Customer who has international plan churn at a higher rate than the customer who has not.

## 6.RECOMMENDATIONS
- Improve the quality of the customer service by offering more training.
- Customer service should follow-up with the customers who call 3 times and offer promotions or discounts like a free month.
- Syriatel should revisit its international plan and adjust the pricing.
- Syriatel should offer free voice mail plan for everyone.


## 7.REPOSITORY GUIDE
- The data set used can be found [here](https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset)
- The data report can be found [here](https://docs.google.com/document/d/1O5D6JFYrI-r6pv-e7zAtOJ6FaOYzyCF9HsA6f3iITfU/edit#)
- The notebook can be found [here](http://localhost:8888/notebooks/SyriaTel%20Customer%20Churn.ipynb#3.5.2.-Decision-Tree-Classifier)
- The Presentation Slides can be found [here](https://docs.google.com/presentation/d/1GbwvpXN6El28v2S36Ipdy0Vcbu_7y9_38WnSY-loi2w/edit#slide=id.gc6f9e470d_0_126)
