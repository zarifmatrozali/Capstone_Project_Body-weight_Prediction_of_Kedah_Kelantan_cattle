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

Reference:
1. Alemneh, T., & Getabalew, M. (2019). Factors influencing the growth and development of meat animals. Int. J. Anim. Sci, 3(3), 1048–1053.
2. Ariff, O. M., Sharifah, N. Y., & Hafidz, A. W. (2015). Status of beef industry of Malaysia. Mal. J. Anim. Sci., 18(2), 1–21.
3. Department of Statistics Malaysia. (2021, August 26). SUPPLY AND UTILIZATION ACCOUNTS SELECTED AGRICULTURAL COMMODITIES, MALAYSIA 2016–2020 [Press release]. https://www.dosm.gov.my/v1/index.php?r=column/cthemeByCat&cat=164&bul_id=cHgwanhNdU4vWXRvc3pnZU9xSjZTUT09&menu_id=Z0VTZGU1UHBUT1VJMFlpaXRRR0xpdz09
4. Habtamu, A., Solomon, A., & Yoseph, M. (2012). Influence of non-genetic factors on growth traits of Horro (Zebu) and their crosses with Holstein Friesian and Jersey cattle. International Journal of Livestock Production, 3(7), 72–77. https://doi.org/10.5897/ijlp11.015
5. Hocquette, J., Gondret, F., Baéza, E., Médale, F., Jurie, C., & Pethick, D. (2010). Intramuscular fat content in meat-producing animals: development, genetic and nutritional control, and identification of putative markers. Animal, 4(2), 303–319. https://doi.org/10.1017/s1751731109991091
6. Hozáková, K. (2020). Growth of beef cattle as prediction for meat production: A review. Acta Fytotechnica et Zootechnica, 23(2), 58–69. https://doi.org/10.15414/afz.2020.23.02.58-69
7. Irshad, A., Gurunathan, K., Kumar, S., Kumar, A., Kumar, A., MR, V., & Shukla, V. (2013). Factors Influencing Carcass Composition of Livestock: a Review. Journal of Animal Production Advances, 3(5), 177. https://doi.org/10.5455/japa.20130531093231

Credit to:
Muhammad Ismail Bin Elias



