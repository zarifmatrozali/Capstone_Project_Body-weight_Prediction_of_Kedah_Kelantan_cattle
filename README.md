# Capstone_Project_Body-weight_Prediction_of_Kedah_Kelantan_cattle
This Capstone project for Forward School
Title: Body weight Prediction of Kedah-Kelantan cattle

Introduction:

Malaysia is home to the local breed of cattle known as Kedah-Kelantan (KK) cattle. A small cattle with a fatty hump and an underdeveloped dewlap. 
KK cattle herd have mostly brown coat, a strong body conformation, and reddish, black, and grey spots. It is a well-adapted but slower growth performance cattle. 
However, KK cattle possess high fertility with an excellent mothering ability. Other than high fertility, it also has high survivability and well-adapted to 
Malaysia climate (Islam et al., 2021).

Problem Statement:

determining the growth of cattle to be slaughtered to obtain the maximum amount of meat possible is crucial to support local meat demand which as of now the 
local meat production are unable to cater the local demand. According to Department of Statistics Malaysia (2021), the local meat production can only supply 
about 22.2 percent of demand in Malaysia whereas the rest of it is dependent on importation. to curb this issue, analysing the factor influencing the growth of 
cattle is needed, hence this warrants the need of this project

Model Selection:

![Screenshot 2022-10-15 222711](https://user-images.githubusercontent.com/110704325/195991756-d5cac8a4-eacc-4304-aa97-7d4a8fe4223d.png)


![Picture1](https://user-images.githubusercontent.com/110704325/195991825-25a79c53-b4d9-43ca-9865-00682b0e225d.png)

RandomForestRegressor model is the best model since it's produce low RMSE and high R squared.

Model Tuning

![Screenshot 2022-10-15 223029](https://user-images.githubusercontent.com/110704325/195991915-c833bd0b-a093-41a7-b500-f26f790f27d1.png)

After tuning the model, the result seems decrease the R squared value. So we will remain use the prediction model without tuning the model.

Conclusion:
In conclusion, there are many factors that influence the body weight of cattle that current researchers do not explore yet in terms of formulating prediction 
models based on discussed factors. Hence there is gap of knowledge that can be filled in term of body weight prediction of cattle.

