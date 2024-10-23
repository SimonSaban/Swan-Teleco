# Swan-Teleco
Classification Model for Predicting Customer Churn

This was a fun classification problem. Working with customer data from a telecommunications company the idea was to create a model that is able to predict the likelihood of a customer churning. The deliverables were:
- Identifying the demographics of customers who churn
- Identifying the factors that make customers more likely to stay in order to incentivise and direct the focus of the team who sign up new customers towards specific products that are proven to increase customer satisfaction  
- Identifying 500 customers who are the most likely to churn, in order to target them by email and keep them sweet
- Identifying the churn probability of all customers

Part of this project was a thorough data analysis, and we provided a Tableau dashboard with our findings. 
This could be found using the following link-
https://public.tableau.com/views/SwanTeleco_17175917451050/Dashboard1?:language=en-GB&publish=yes&:sid=&:display_count=n&:origin=viz_share_link

The challenges here were:
- Cleaning the data dealing with missing data and columns with inconsistent data types
- Identifying signal in the data and reducing the noise
- Mapping and converting non numerical types of data
- Choosing a ML model for the problem. Since this was a classification problem there were several modelling options. Our approach was to try several and choose the one that delivers the best results. We practiced logistic regression, a random forest and even had a go with TensorFlow
- Fine tuning hyperparameters to improve performance
