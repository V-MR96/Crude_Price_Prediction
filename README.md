# 0. Oil Price Prediction

## Objective:

Oil is a product that goes completely in a different direction for a single market event as the oil prices are rarely based on real-time data, instead, it is driven by externalities making our attempt to forecast it even more challenging As the economy will be highly affected by oil prices our model will help to understand the pattern in prices to help the customers and businesses to make smart decisions.


 # The Following folder contains 
 
 - Non-darts_all_Models.ipynb 		: Which contains all the models we have explored without darts library and has high space and time complexity.
 - Darts_All_Models.ipynb 		: Which contains all the models we have explored with the help of darts library which has less space and time complexity relative to Non-darts_all_models.ipynb
 - Deployment_Prophet_Model.ipynb 	: Which contains prophet model which is used in deployment. 
 - oil data update.csv 			: contains the crude oil price data which is used for model training.
 - model5.pkl 				: Is the serialized prophet model which we trained
 - Streamlit.py 			: It is the file which has the web app code.
 
 ### Python packages required: 
 
 - 1. streamlit
 - 2. numpy
 - 3. pandas
 - 4. darts
 - 5. pickle
 - 6. Streamlit --> Deployment
 
 ### How to deploy web app code: 
 
 In your respective python environment run the below code
 
 ```
 streamlit run Streamlit.py
 ```
 
 
